# ChefSphere -Chef Booking App

## Overview-
ChefSphere is an Android application designed to connect users with professional chefs for on-demand culinary experiences. Built using modern Android technologies, ChefSphere offers a user-friendly interface and a robust backend to facilitate seamless chef bookings.

## Features-
Chef Profiles: Browse detailed chef profiles, including their specialties, experience, and ratings.

Booking Management: Easily book chefs for specific dates and times.

Secure Authentication: User authentication and authorization using Firebase Authentication.

Real-time Updates: Real-time data synchronization using Firebase Realtime Database.

Location Services: Find chefs near you using the Google Maps SDK.

Search and Filters: Search for chefs by cuisine, location, and availability.

User Reviews and Ratings: Provide and view feedback on chef services.



## Technologies Used-
Jetpack Compose: Modern UI toolkit for building native Android apps.

MVVM Architecture: Model-View-ViewModel architecture for a clean and maintainable codebase.

Hilt: Dependency injection library for Android.

Kotlin: Primary programming language.

Firebase Authentication: User authentication and authorization.

Firebase Firestore: NoSQL database for storing structured data.

Firebase Realtime Database: Real-time database for data synchronization.

Google Maps SDK: Integration of Google Maps for location-based features.




## Installation-
Clone the repository.

Open the project in Android Studio.

Set up Firebase project and configure the google-services.json file.

Obtain a Google Maps API key and add it to your local.properties file:
```bash
MAPS_API_KEY="YOUR_API_KEY"
```

Build and run the application.



## Architecture
ChefSphere follows the MVVM (Model-View-ViewModel) architecture:

Model: Data layer responsible for handling data.

View: UI layer built with Jetpack Compose.

ViewModel: Acts as a bridge between the Model and the View, handling UI logic and data presentation.

Hilt is used for dependency injection, providing a way to manage dependencies throughout the application.


## Firebase Setup
To run ChefSphere, you need to set up a Firebase project and configure the following:

Firebase Project: Create a new project in the Firebase Console.

Authentication: Enable the desired authentication methods (e.g., email/password, Google Sign-in).

Firestore: Create a Firestore database to store application data.

Realtime Database: Create a Realtime Database for real-time updates.

Google Maps API Key: Enable the Maps SDK for Android and obtain an API key.

google-services.json: Download the google-services.json file from your Firebase project and add it to the app directory of your Android Studio project.


## Google Maps API Key
Enable the Maps SDK for Android in the Google Cloud Console.

Create an API key.

Restrict the API key to the Maps SDK for Android.

Add the API key to your local.properties file:
```bash
MAPS_API_KEY="YOUR_API_KEY"
```


## Contributing
Contributions are welcome! If you'd like to contribute to ChefSphere, please follow these steps:

Fork the repository.

Create a new branch for your feature or bug fix.

Make your changes and commit them.

Push your changes to your fork.

Submit a pull request.

