# Amphibians App

Welcome to the Amphibians App! This project is a practice exercise from the [Android Basics with
Compose](https://developer.android.com/courses/android-basics-compose/course) course on
[Developer(Android)](https://developer.android.com/). The app displays a list of amphibians along
with their details and images.

## Screenshot
![]( )

## Features

The app is expected to do the following:

* **Make a network request:** Retrieve amphibian data from a remote server using Retrofit.
* **Parse JSON data:** Use Gson to parse the response.
* **Display data:** Asynchronously download and display images of the amphibians along with their names,
  types, and descriptions.
* **Implement best practices:** Separate the UI and data layer by using a repository pattern.


## Data Source

The amphibian JSON data is hosted
at: [Api](https://android-kotlin-fun-mars-server.appspot.com/amphibians)


## Objectives

The goal of this project is twofold:

1. **Practice the concepts:** Apply all the concepts you've learned in this unit into a practical
   project.
2. **Work with a REST API:** Gain experience working with a new REST API, reading documentation, and
   applying your skills to develop a new app, just like you would as a professional Android
   developer.

## Technologies used

### Lenguajes y Frameworks

* Kotlin
* Jetpack Compose

### Loading images

* Coil

### Architecture

* MVVM (Model-View-ViewModel)

### Reactive Programming

* Coroutines
* Flows

### Networking

* Retrofit

### Version Control

* Git
* GitHub


## Course Information

* **Course:** [Android Basics with Compose](https://developer.android.com/courses/android-basics-compose/course)

* **Project Unit:** [Amphibians App Practice](https://developer.android.com/codelabs/basic-android-kotlin-compose-practice-amphibians-app?continue=https%3A%2F%2Fdeveloper.android.com%2Fcourses%2Fpathways%2Fandroid-basics-compose-unit-5-pathway-2%23codelab-https%3A%2F%2Fdeveloper.android.com%2Fcodelabs%2Fbasic-android-kotlin-compose-practice-amphibians-app#0)


## Installation

To get a local copy up and running, follow these simple steps:

1. Clone the repository:

```bash
git clone https://github.com/nikollquinteroc/Amphibians.git
```

2. Open the project in Android Studio.
3. Build and run the project on an emulator or a physical device.


## Usage

Upon launching the app, you will see a list of amphibians. Each amphibian's card displays its name,
type, description, and image directly.
