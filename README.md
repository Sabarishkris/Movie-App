# Movie App

## Description

The Movie App is an Android application that allows users to browse and search for movies using the OMDB API. It utilizes modern Android development practices such as MVVM architecture, Jetpack components like Paging 3, Retrofit for network requests, and Dagger Hilt for dependency injection.

## Screen Shot
![Movie IMbd](https://github.com/Sabarishkris/Movie-App/assets/159115255/699ea69d-55e1-4961-9e3f-7438aa5fd16b)


## Features

- Browse and search movies by title.
- View detailed information about each movie, including plot, ratings, and year of release.
- Pagination for smooth scrolling through large lists of movies.
- Integration with OMDB API for retrieving movie data.

## Libraries Used

- Retrofit for network requests.
- Glide for image loading.
- Paging 3 for pagination of movie lists.
- Dagger Hilt for dependency injection.
- GsonConverterFactory for JSON parsing.

## Installation

### Prerequisites

- Android Studio Arctic Fox (2020.3.1) or newer
- Android SDK with minimum SDK version 21 

### Setup
- Open the project in Android Studio.
- Build and run the project on an emulator or device.

## Usage
- Navigate through the app to browse movies.
- Use the search functionality to find specific movies.
- Tap on a movie to view detailed information.

## Architecture
The app follows the MVVM (Model-View-ViewModel) architecture pattern:

- Model: Data models representing movies and their details.
- View: Fragments displaying movie lists and details.
- ViewModel: Manages UI-related data in a lifecycle-conscious way, communicating with the data model.
  
## API Reference
The app uses the OMDB API to fetch movie data. You'll need an API key to use the service.


