# uludus/fightingapp android

Android application for an AI assisted martial arts learning platform.

Initially created for Tesonet's AI-only hackathon where we won 3rd place. Heavily vibe-coded, but fairly understandable, just very messy and not really clean.

# How to launch yourself?
No apk because I can't make releases for this and it'd be large, so you'll have to build it yourself.

You build it pretty much as any other android app - download android studio, clone this project, sync, run in emulator or on device. [This is a great resource if you've never had to do this.](https://developer.android.com/courses/pathways/android-basics-compose-unit-1-pathway-2)

# App layout
As any other android app - go to app/src/com/arnasmat/fightingapp to see the app files.

FightingApplication is for Dependency injection (Hilt)

MainActivity is the application entrypoint.


# Technologies
- Kotlin & coroutines
- General android libs & viewmodels  
- Jetpack Compose & Material3 for UI
- MVVM architecture
- Dagger-Hilt for DI
- Camerax
- Datastore
- Retrofit on OKHttp
- Coil
