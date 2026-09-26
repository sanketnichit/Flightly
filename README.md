# Flightly ✈️

A simple Android flight itinerary interface built with **Kotlin**, **XML**, **ConstraintLayout**, and **Skyscanner Backpack**.

## Overview

Flightly is a small Android UI project created as part of the **Skyscanner Software Engineering Virtual Experience**. It demonstrates how Skyscanner's Backpack Android components can be used to build a clean flight itinerary screen.

The current app presents a static itinerary for flight **SK123** from **BOM** to **LHR**.

## Features

- Flight information card
- Departure card with airport and time
- Arrival card with airport and time
- Skyscanner Backpack `BpkCardView` components
- Skyscanner Backpack typography components
- ConstraintLayout-based responsive positioning
- Android XML View system

## Tech Stack

- **Kotlin**
- **Android**
- **XML layouts**
- **ConstraintLayout**
- **Skyscanner Backpack for Android 43.0.0**
- **Gradle Kotlin DSL**

## Flight Details

| Field | Value |
|---|---|
| Flight | SK123 |
| Departure | BOM |
| Departure Time | 09:30 |
| Arrival | LHR |
| Arrival Time | 14:50 |

## Project Structure

```text
Flightly/
├── app/
│   └── src/
│       ├── main/
│       │   ├── java/
│       │   │   └── com/example/flightscry/
│       │   │       └── MainActivity.kt
│       │   ├── res/
│       │   │   └── layout/
│       │   │       └── activity_main.xml
│       │   └── AndroidManifest.xml
│       └── androidTest/
├── gradle/
├── build.gradle.kts
├── settings.gradle.kts
├── gradlew
└── gradlew.bat
```

## Running Locally

1. Clone the repository.
2. Open the project in **Android Studio**.
3. Allow Gradle to sync and download dependencies.
4. Use an Android device or emulator with the required SDK.
5. Run the **app** configuration.

Or from the project root on Windows:

```powershell
.\gradlew.bat assembleDebug
```

## Project Context

Built as part of the **Skyscanner Software Engineering Virtual Experience**, with a focus on implementing a flight itinerary UI using Skyscanner's Backpack design system.

## Status

✅ Working UI prototype  
🚧 Static flight data; no live flight search or backend integration