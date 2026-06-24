# Movie Catalog App

## Overview

Movie Catalog App is a Flutter-based mobile application designed to provide users with a complete and user-friendly platform for exploring movie information. The app retrieves real-time movie data from The Movie Database (TMDB) API using Dio and displays it through a clean mobile interface.

The application supports user authentication using Firebase Authentication, allowing users to register and log in securely. After logging in, users can browse popular and top-rated movies, explore movie categories, search for specific movies, view detailed movie information, add or remove movies from their favorites list, and view statistics based on their favorite movies.

The app also includes additional screens such as settings, dark mode support, an about page, and a team members page. Overall, the project demonstrates practical use of Flutter, REST API integration, Firebase services, Firestore, asynchronous programming, and layered application architecture.

---
## Features

* Splash Screen
* Introduction / Onboarding Screen
* User Registration
* User Login
* Firebase Authentication
* Home Screen
* Popular Movies
* Top Rated Movies
* Movie Categories
* Movie Search
* Movie Details Screen
* Add / Remove Favorites
* Favorites Screen
* Favorite Movie Statistics
* Settings Screen
* Dark Mode
* About App Page
* Team Members Page

## Technologies Used

* Flutter
* Dart
* Dio
* Firebase Authentication
* Cloud Firestore
* TMDB API

---

## Architecture

The application follows a Layered Architecture Pattern consisting of:

* Presentation Layer
* Service Layer
* Model Layer

This separation improves maintainability and keeps networking logic independent from UI components.

---

## Key Technical Concepts

* REST API Integration
* JSON Parsing
* MovieModel Data Mapping
* Async / Await
* FutureBuilder
* State Management using setState()
* Firebase Authentication
* Cloud Firestore Integration
* Dio HTTP Requests
* Error Handling
* Navigation between Screens

---

## Screenshots

### Introduction Screen
![Introduction](assets/images/intro.jfif)
![Introduction](assets/images/int.jfif)

### Login Screen
![Login](assets/images/login.jfif)

### Home Screen
![Home](assets/images/home.jfif)

### Search Screen
![Search](assets/images/search.jfif)
![Search](assets/images/search11.jfif)

### Movie Details Screen
![Movie Details](assets/images/details.jfif)

### Favorites Screen
![Favorites](assets/images/fav.jfif)

### Favorite Statistics Screen
![Statistics](assets/images/favstat.jfif)

### Settings Screen
![Settings](assets/images/setting.jfif)

## Setup Note
Before running the project, add your own TMDB API key inside MovieService.

If Firebase configuration files are not included in the repository, add your own Firebase setup files before running the application.





---
