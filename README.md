# s8069133Assesment2

# Assessment2 Android Application

## Project Overview
Assessment2 is an Android application designed as part of a project for handling user authentication with a login screen, dashboard, and integration of various Android components. This project demonstrates the usage of Hilt for dependency injection, Retrofit for API calls, and lifecycle-aware components such as ViewModel and LiveData.

## Features
- User authentication (Login Screen).
- Dashboard with user information.
- Dependency injection using Hilt.
- API calls integrated using Retrofit.
- ViewModel and LiveData for lifecycle management.
- Use of Navigation component for navigating between screens.
- RecyclerView for displaying lists of items.
- ViewBinding enabled for easy view interaction.

## Setup Instructions

### Prerequisites
- Android Studio (latest stable version recommended).
- Minimum SDK: 26
- Target SDK: 34
- Java version: 1.8

### Getting Started

1. Clone this repository to your local machine.
    ```bash
    git clone https://github.com/your-repo/assessment2.git
    ```
2. Open the project in Android Studio.
3. Sync the project with Gradle files.
4. Ensure you have the following installed:
   - Kotlin 1.9.24
   - Android SDK 34
5. If you encounter any issues with dependencies, ensure that your `build.gradle` files are correctly set up.

### Build and Run

1. To build the project, click on `Build > Make Project` or run:
    ```bash
    ./gradlew assembleDebug
    ```
2. To run the application, use `Run > Run 'app'` in Android Studio or:
    ```bash
    ./gradlew installDebug
    ```

## Dependencies

The following dependencies are used in this project:

- **AndroidX Libraries**
  - Core KTX: `androidx.core:core-ktx:1.13.1`
  - AppCompat: `androidx.appcompat:1.7.0`
  - Material Components: `com.google.android.material:material:1.12.0`
  - ConstraintLayout: `androidx.constraintlayout:constraintlayout:2.1.4`
  - Navigation: `androidx.navigation:navigation-fragment-ktx:2.8.2`, `androidx.navigation:navigation-ui-ktx:2.8.2`
  - RecyclerView: `androidx.recyclerview:recyclerview:1.2.1`

- **Hilt for Dependency Injection**
  - Hilt: `com.google.dagger:hilt-android:2.42`
  - Hilt Compiler: `com.google.dagger:hilt-compiler:2.42`

- **Retrofit for API Calls**
  - Retrofit: `com.squareup.retrofit2:retrofit:2.9.0`
  - Retrofit Gson Converter: `com.squareup.retrofit2:converter-gson:2.9.0`

- **Lifecycle Components**
  - ViewModel KTX: `androidx.lifecycle:lifecycle-viewmodel-ktx:2.6.1`
  - LiveData KTX: `androidx.lifecycle:lifecycle-livedata-ktx:2.6.1`
  - Lifecycle Runtime KTX: `androidx.lifecycle:lifecycle-runtime-ktx:2.6.1`

- **Testing**
  - JUnit: `junit:junit:4.13.2`
  - Mockito: `org.mockito:mockito-core:3.9.0`
  - AndroidX Test: `androidx.test.ext:junit:1.2.1`, `androidx.test.espresso:espresso-core:3.6.1`

## Folder Structure
The project follows a standard Android project structure:

