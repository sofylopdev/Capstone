# Capstone

Capstone project for the Android Developer Nanodegree: SeriesTracker.

App that allows the user to track it's favorite shows.


## Project Overview

In Stage 1, you designed and planned your Capstone app. Now, it's time to build it!


## Why this Project?

In this project, you will demonstrate the skills you've learned in your Nanodegree journey, and apply them to creating a unique app experience of your own. By the end of this project, you will have an app that you can submit to the Google Play Store for distribution.


## What Will I Learn?

The Capstone project will give you the experience you need to own the full development cycle of an app.


## Project Requirements

 - App conforms to common standards found in the [Android Nanodegree General Project Guidelines](http://udacity.github.io/android-nanodegree-guidelines/core.html)

 - App is written solely in the Java Programming Language

 - App utilizes stable release versions of all libraries, Gradle, and Android Studio.
 
 - App integrates a third-party library.

 - App validates all input from servers and users. If data does not exist or is in the wrong format, the app logs this fact and does not crash.

 - App includes support for accessibility. That includes content descriptions, navigation using a D-pad, and, if applicable, non-audio versions of audio cues.

 - App keeps all strings in a strings.xml file and enables RTL layout switching on all layouts.

 - App provides a widget to provide relevant information to the user on the home screen.

 - App integrates two or more Google services. Google service integrations can be a part of Google Play Services or Firebase.

 - Each service imported in the build.gradle is used in the app.

 - If Location is used, the app customizes the user’s experience by using the device's location.

 - If Admob is used, the app displays test ads. If Admob was not used, student meets specifications.

 - If Analytics is used, the app creates only one analytics instance. If Analytics was not used, student meets specifications.

 - If Maps is used, the map provides relevant information to the user. If Maps was not used, student meets specifications.

 - If Identity is used, the user’s identity influences some portion of the app. If Identity was not used, student meets specifications.

 - App theme extends AppCompat.

 - App uses an app bar and associated toolbars.

 - App uses standard and simple transitions between activities.

 - App builds from a clean repository checkout with no additional configuration.

 - App builds and deploys using the installRelease Gradle task.

 - App is equipped with a signing configuration, and the keystore and passwords are included in the repository. Keystore is referred to by a relative path.

 - All app dependencies are managed by Gradle.

 - App stores data locally either by implementing a ContentProvider OR using Firebase Realtime Database OR using Room. No third party frameworks nor Persistence Libraries may be used.

 - Must implement at least one of the three
If it regularly pulls or sends data to/from a web service or API, app updates data in its cache at regular intervals using a SyncAdapter or JobDispacter.
OR
If it needs to pull or send data to/from a web service or API only once, or on a per request basis (such as a search application), app uses an IntentService to do so.
OR
It it performs short duration, on-demand requests(such as search), app uses an AsyncTask.

 - If Content provider is used, the app uses a Loader to move its data to its views.

 - If Room is used then LiveData and ViewModel are used when required and no unnecessary calls to the database are made.
 
 
## Extra Implementations

 - Parallax scrolling implemented in DetailsActivity
 - App has notifications that remind users about the release of new episodes
 - Users can share information about a series in the SeriesDetails
 

## Languages, libraries and tools used

 - Java
 - Android Support Libraries
 - [LiveData](https://developer.android.com/topic/libraries/architecture/livedata)
 - [ViewModel](https://developer.android.com/topic/libraries/architecture/viewmodel)
 - [Room](https://developer.android.com/topic/libraries/architecture/room)
 - [Retrofit](https://github.com/square/retrofit)
 - [Gson](https://github.com/google/gson) (as a converter in Retrofit)
 - [Picasso](https://github.com/square/picasso)
 - [Butterknife](https://github.com/JakeWharton/butterknife)
 - [Timber](https://github.com/JakeWharton/timber)
 - [Google Analytics](https://developers.google.com/analytics/)
 - [Google AdMob](https://developers.google.com/admob/android/quick-start)
 - [Stetho](https://github.com/facebook/stetho)
 - [RoundedImageView](https://github.com/vinc3m1/RoundedImageView)
 - [ThreeTen Android Backport](https://github.com/JakeWharton/ThreeTenABP)
 - [Firebase JobDispatcher](https://github.com/firebase/firebase-jobdispatcher-android)


## Screenshots

|Explore| MySeries Empty | MySeriesWatching | MySeriesWatched |
| --- | --- | --- | --- |
| ![alt text](https://github.com/sofylopdev/Capstone/blob/master/Explore.png) | ![alt text](https://github.com/sofylopdev/Capstone/blob/master/MySeriesEmpty.png) | ![alt text](https://github.com/sofylopdev/Capstone/blob/master/MySeriesWatching.png) | ![alt text](https://github.com/sofylopdev/Capstone/blob/master/MySeriesWatched.png) | 

|SeriesDetails top| SeriesDetails bottom | SeasonDetails | SeasonDetails Show More open|
| --- | --- | --- | --- |
| ![alt text](https://github.com/sofylopdev/Capstone/blob/master/SeriesDetails.png) | ![alt text](https://github.com/sofylopdev/Capstone/blob/master/SeriesDetails2.png) | ![alt text](https://github.com/sofylopdev/Capstone/blob/master/SeasonDetails.png) | ![alt text](https://github.com/sofylopdev/Capstone/blob/master/SeasonDetails2.png) | 

|Search| Settings | Widget |
| --- | --- | --- | 
| ![alt text](https://github.com/sofylopdev/Capstone/blob/master/Search.png) | ![alt text](https://github.com/sofylopdev/Capstone/blob/master/Settings.png) | ![alt text](https://github.com/sofylopdev/Capstone/blob/master/Widget.png) | 

|Tablet: Explore| Tablet: SeriesDetails top | Tablet: SeriesDetails bottom|
| --- | --- | --- | 
| ![alt text](https://github.com/sofylopdev/Capstone/blob/master/TabletExplore.png) | ![alt text](https://github.com/sofylopdev/Capstone/blob/master/TabletSeriesDetails.png) | ![alt text](https://github.com/sofylopdev/Capstone/blob/master/TabletDetails2.png) | 

|Tablet: SeasonDetails| Tablet: Search | 
| --- | --- | 
| ![alt text](https://github.com/sofylopdev/Capstone/blob/master/TabletSeasonDetails.png) | ![alt text](https://github.com/sofylopdev/Capstone/blob/master/TabletSearch.png) | 

