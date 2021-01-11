<h1 align="center">
  Submission Dicoding MADE : Movie App
</h1>
<p align="center">
  Submission MADE (Menjadi Android Developer Expert) in Dicoding Course.
</p>
<p align="center">
  <a href="http://developer.android.com/index.html"><img alt="Platform" src="https://img.shields.io/badge/platform-Android-green.svg"></a>
  <a href="http://kotlinlang.org"><img alt="Kotlin" src="https://img.shields.io/badge/kotlin-1.4.20-blue.svg"></a>
  <a href="https://developer.android.com/studio/releases/gradle-plugin"><img alt="Gradle" src="https://img.shields.io/badge/gradle-4.1.1-yellow.svg"></a>
  <a href="https://github.com/Adithya-13/MadeSubmsission/"><img alt="Star" src="https://img.shields.io/github/stars/Adithya-13/MadeSubmsission"></a>
  <a href="https://github.com/Adithya-13/MadeSubmsission/"><img alt="Circle CI" src="https://circleci.com/gh/Adithya-13/MadeSubmsission.svg?style=shield"></a>
</p>

<p align="center">
  <img src="assets/thumbnail.png"/>
</p>

## Table of Contents
- [Introduction](#introduction)
- [Installation](#installation)
- [Demo](#demo)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Dependencies](#dependencies)

## Introduction

This project is made to fulfill a Submission in Dicoding course and the last course in Android Learning path.

As you can see, this repos have 4 Branch, master, circle-ci-project-setup, submission1, submission2, You can see at Branch submission1 if you want to look at the code, and clone it with [DownGit](https://downgit.github.io/), and the branch master & submission2 is exactly same, because i merged it into branch master from branch submission2, just clone or download it if you want to see the code, thanks.

In this project, I learned many things, such as Clean architecture, Design Pattern, Networking with Retrofit, Reactive Programming with Coroutines Flow, Dependency Injection with Koin, Local Database with Room Persistence, Modularization, Dynamic Feature, Security, Useful Library, Continuous Integration, Performance, and many things.

For the 3rd Party Library i used in this project, you can look [here](#dependencies), and for the Tech Stack, i used the MVVM Architecture Pattern, Dependency Injection (DI) with Koin, and so many things that you can see at [here](#tech_stack).

I Use the [TheMovieDatabase](https://www.themoviedb.org/) for the data source. first thing first, you have to get the API Key from [TheMovieDatabase](https://www.themoviedb.org/), then, follow the instruction [here](#installation).

I Hope this Project will help someone, if you feel helped with this project, you can give stars to support me, thank you very much :)

## Installation

Clone or Download and Open it into Android Studio for Submission 2
```
    https://github.com/Adithya-13/MadeSubmsission.git
```  

You can use the [DownGit](https://downgit.github.io/) for download Submission1 separately, Copy this

```
    https://github.com/Adithya-13/MadeSubmsission/tree/submission1
```

and Paste it into DownGit, after that click Download Button, and voila, you can clone the code.

## Demo

|All Movies|All Tv Shows|Detail Movies|Detail Tv Shows|
|--|--|--|--|
|<a href="https://iphoto.net/i/lSiea"><img src="https://m.iphoto.net/lSiea.gif" alt="All Movies"></a>|<a href="https://iphoto.net/i/lSqeh"><img src="https://m.iphoto.net/lSqeh.gif" alt="All Tv Shows"></a>|<a href="https://iphoto.net/i/lS7cV"><img src="https://m.iphoto.net/lS7cV.gif" alt="Detail Movies"></a>
|<a href="https://iphoto.net/i/lSELZ"><img src="https://m.iphoto.net/lSELZ.gif" alt="Detail Tv Shows"></a>|

|Search Movies|Search Tv Shows|Favorite Movies|Favorite Tv Shows|
|--|--|--|--|
|<a href="https://iphoto.net/i/lS5yK"><img src="https://m.iphoto.net/lS5yK.gif" alt="Search Movies"></a>|<a href="https://iphoto.net/i/lS156"><img src="https://m.iphoto.net/lS156.gif" alt="Search Tv Shows"></a>
|<a href="https://iphoto.net/i/lS8ux"><img src="https://m.iphoto.net/lS8ux.gif" alt="Favorite Movies"></a>|<a href="https://iphoto.net/i/lSFfA"><img src="https://m.iphoto.net/lSFfA.gif" alt="Favorite Tv Shows"></a>|

## Features
- Get All the Movies and Tv Shows
- Search the Movies and Tv Shows
- Favorited Movies and Tv Shows
- Sort the Movies and Tv Shows by: Popularity, Vote, Release Date, and Random
- Share the Movies and Tv Shows to other Application

## Tech Stack
- MVVM (Model-View-ViewModel) Architecture Pattern
- Modularization (core module)
- Dynamic Feature (favorite module)
- Clean Architecture (data, domain, presentation)
- Dependency Injection with Koin
- Coroutines Flow
- ViewBinding
- Room Persistence
- RawQuery
- Obfuscation with Proguard
- Encryption with SQLCipher
- Certificate Pinning with OkHttp
- Continuous Integration with Circle-CI

## Dependencies
- [Bubble Navigation](https://github.com/gauravk95/bubble-navigation)
- [Custom FAB](https://github.com/Clans/FloatingActionButton)
- [Rounded Image View](https://github.com/vinc3m1/RoundedImageView)
- [Material Search View](https://github.com/MiguelCatalan/MaterialSearchView)
- [Glide](https://github.com/bumptech/glide)
- [Ken Burns View](https://github.com/flavioarfaria/KenBurnsView)
- [Lottie](https://github.com/airbnb/lottie-android)
- [Shimmer](https://github.com/facebook/shimmer-android)
- [AndroidX](https://mvnrepository.com/artifact/androidx)
- [Lifecycle & LiveData](https://developer.android.com/jetpack/androidx/releases/lifecycle)
- [Koin](https://github.com/InsertKoinIO/koin)
- [Retrofit](https://square.github.io/retrofit/)
- [Coroutines Flow](https://developer.android.com/kotlin/flow)
- [Room](https://developer.android.com/training/data-storage/room?gclid=Cj0KCQiA0MD_BRCTARIsADXoopYlw1cozWjwyR-ucLYa-aoqYlZeJmxG34JnhByjApMNwuchOcAzcy0aAgGHEALw_wcB&gclsrc=aw.ds)
- [SQLCipher](https://github.com/sqlcipher/sqlcipher)
- [SQLite](https://developer.android.com/jetpack/androidx/releases/sqlite)
- [Leak Canary](https://github.com/square/leakcanary)
