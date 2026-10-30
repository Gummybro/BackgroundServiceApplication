# Background Service Application

Android coursework project scaffold for a background-service application.

## Current status

The checked-in project is incomplete: `settings.gradle.kts` references an `app` module, but that module, the Gradle version catalog, and the Gradle wrapper directory are missing.

The original ignore rules excluded `/app/` and `/gradle/`. Those exclusions have been removed so the missing source and build files can be committed.

## Restore the project

1. Recover the original `app/` and `gradle/` folders from the development machine or a backup.
2. Add them alongside `settings.gradle.kts`.
3. Open this directory in Android Studio and sync Gradle.
4. Document the service behavior and required permissions once the source is restored.

The repository cannot build from its current contents. The missing application has not been reconstructed or replaced with a different implementation.
