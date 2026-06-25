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

<table>
<tr>
<td align="center">
<b>Introduction Screen 1</b><br>
<img src="assets/images/intro.jfif" width="180">
</td>
<td align="center">
<b>Introduction Screen 2</b><br>
<img src="assets/images/int.jfif" width="180">
</td>
<td align="center">
<b>Login Screen</b><br>
<img src="assets/images/login.jfif" width="180">
</td>
</tr>

<tr>
<td align="center">
<b>Home Screen</b><br>
<img src="assets/images/home.jfif" width="180">
</td>
<td align="center">
<b>Search Screen</b><br>
<img src="assets/images/search.jfif" width="180">
</td>
<td align="center">
<b>Search Results</b><br>
<img src="assets/images/search11.jfif" width="180">
</td>
</tr>

<tr>
<td align="center">
<b>Movie Details Screen</b><br>
<img src="assets/images/details.jfif" width="180">
</td>
<td align="center">
<b>Favorites Screen</b><br>
<img src="assets/images/fav.jfif" width="180">
</td>
<td align="center">
<b>Favorite Statistics Screen</b><br>
<img src="assets/images/favstat.jfif" width="180">
</td>
</tr>

<tr>
<td align="center">
<b>Settings Screen</b><br>
<img src="assets/images/setting.jfif" width="180">
</td>
<td align="center">
</td>
<td align="center">
</td>
</tr>
</table>

---

## Setup Note

Before running the project, add your own TMDB API key inside MovieService.

If Firebase configuration files are not included in the repository, add your own Firebase setup files before running the application.
