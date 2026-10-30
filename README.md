# GabyFlix

GabyFlix is a personal Android application in development for browsing movie and television information. This repository is the project's public-facing information page; the Android source code and APK are not currently hosted here.

## Project overview

- **Developer:** [gaby401](https://github.com/gaby401)
- **Platform:** Android (Kotlin and Jetpack Compose)
- **Status:** Development prototype; a debug APK has been built and launched on a device. Live metadata browsing is awaiting configuration of a valid TMDB API key.
- **Project URL:** https://github.com/gaby401/gabyflix

## Intended use of TMDB

GabyFlix is designed to use The Movie Database (TMDB) API to display movie and TV metadata, including titles, posters, descriptions, ratings, release dates, and cast information. The prototype includes sections for Airing Today, Trending TV, and Popular Movies.

TMDB integration is for metadata discovery. A TMDB API key does not provide movie or TV video streams. This project page does not host or distribute movie or TV content.

## API configuration

The Android project reads a developer's TMDB v3 API key from `local.properties` at build time:

```properties
TMDB_API_KEY=YOUR_TMDB_V3_API_KEY
```

A valid key and a rebuild are required for live browsing. Do not commit API keys, access tokens, or `local.properties` to this repository.

## TMDB attribution

This product uses the TMDB API but is not endorsed or certified by TMDB.

Movie and TV information and images are provided by [The Movie Database](https://www.themoviedb.org/) when the integration is configured. Required TMDB attribution and branding should also be included in the application's About or Credits screen before distribution.

## Contact

For project questions, [open an issue](https://github.com/gaby401/gabyflix/issues).
