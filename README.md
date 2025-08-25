

# Pokemon Android Application
This is a Pokémon Android application built using Kotlin, Jetpack Compose, Hilt for dependency injection, and the MVVM (Model-View-ViewModel) pattern. The application fetches a list of Pokémon from a server, and upon clicking an item, navigates to a details page to show more information about the selected Pokémon.

<div align="center">
  <img width="268" height="890" alt="image" src="https://github.com/user-attachments/assets/515cfe21-4127-4605-89bd-6bdc85566711" />
  <img width="268" height="890" alt="image" src="https://github.com/user-attachments/assets/31cdca2e-2862-4dff-bda8-31b90b8b9294" />
</div>

## Features
- Fetch Pokémon list from the server.
- Display Pokémon list using Jetpack Compose.
- Navigate to a details page on item click.
- Show detailed information of the selected Pokémon.

## Architecture
The application follows the MVVM architecture pattern:

- Model: Represents the data and business logic of the app. In this app, it includes data classes and repository classes for fetching Pokémon data from the server.
- View: Composes UI elements using Jetpack Compose.
- ViewModel: Acts as a bridge between the Model and the View. It holds and manages UI-related data in a lifecycle-conscious way.
## Dependencies
- Kotlin: A modern programming language that makes developers happier.
- Jetpack Compose: Android’s modern toolkit for building native UI.
- Hilt: A dependency injection library for Android that reduces the boilerplate of doing manual dependency injection.
- Retrofit: A type-safe HTTP client for Android and Java.
- Coroutines: For managing background threads and simplifying code to run asynchronously.

## Usage
Launch the app on an Android device or emulator.
The main screen will display a list of Pokémon fetched from the server.
Click on any Pokémon item to navigate to the details page and view more information.
Code Overview
Download App.

[Download Pokémon App][(https://drive.google.com/file/d/1vydt6_G-GEWlmZiDNJ6S0sETwFJ42eJg/view?usp=sharing))

## Directory Structure

```plaintext
├── data
├── di
├── model
├── repository
├── utility
├── view
    ├── graph
    ├── ui
        ├── customUi
        ├── screen
        ├── theme
├── viewModel
├── MainActivity.kt
└── MainApplication
```

<div align="center">
  
[![Android](https://img.shields.io/badge/Android-3DDC84?style=for-the-badge&logo=android&logoColor=white)](https://developer.android.com)
[![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white)](https://kotlinlang.org)
[![Jetpack Compose](https://img.shields.io/badge/Jetpack%20Compose-4285F4?style=for-the-badge&logo=jetpackcompose&logoColor=white)](https://developer.android.com/jetpack/compose)

<!-- Архитектура -->
[![MVVM](https://img.shields.io/badge/Architecture-MVVM-FF9800?style=for-the-badge&logo=android&logoColor=white)]()
[![Clean Architecture](https://img.shields.io/badge/Clean-Architecture-4CAF50?style=for-the-badge&logo=android&logoColor=white)]()

<!-- База данных и сеть -->
[![Room](https://img.shields.io/badge/Room-Database-4CAF50?style=for-the-badge&logo=android&logoColor=white)](https://developer.android.com/jetpack/androidx/releases/room)
[![Retrofit](https://img.shields.io/badge/Retrofit-Network-FF5722?style=for-the-badge&logo=square&logoColor=white)](https://square.github.io/retrofit)
[![Coil](https://img.shields.io/badge/Coil-Images-9C27B0?style=for-the-badge&logo=android&logoColor=white)](https://coil-kt.github.io/coil)
</div>


