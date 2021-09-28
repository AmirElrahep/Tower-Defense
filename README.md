# Tower Defense

Westfield State University themed tower defense game for Android.

## Table of Contents

* [General Information](#general-information)
    * [Built With](#built-with)
* [Screenshots and Gameplay](#screenshots-and-gameplay)
* [Features](#features)
* [Setup](#setup)
    * [Prerequisites & Useful Links](#prerequisites--useful-links)
    * [How to Build](#how-to-build)
* [Contact](#contact)

## General Information

This is a tower defense game developed for Android with a Westfield State University theme. Developed utilizing Scrum
methodology and Git source control for team collaboration over the span of a semester.

A user can choose from various distinct maps and three different levels of difficulty. During the game, the player
places towers throughout the map to defeat waves of spawning enemies. After a game is over, the user can enter a name to
display next to their score in the high scores list corresponding to the difficulty they played.

### Built With

* Java - Android Studio
* MySQL
* Gradle

## Screenshots and Gameplay

<table>
    <tr>
        <td><img width="1010" alt="start" src="https://user-images.githubusercontent.com/72151692/135110097-f1397074-ff83-4783-ab16-5897d1e9164a.png"></td>
        <td><img width="1010" alt="settings" src="https://user-images.githubusercontent.com/72151692/135110125-722f8f92-8a1d-44d7-9bfe-2268ef142a39.png"></td>
    </tr>
    <tr>
        <td><img width="1010" alt="gameSelection_1" src="https://user-images.githubusercontent.com/72151692/135110153-4c62a509-d562-4726-b646-2856fa4dae91.png"></td>
        <td><img width="1010" alt="gameSelection_2" src="https://user-images.githubusercontent.com/72151692/135110165-6cc43c02-029a-48e5-aa14-6c62970df0d4.png"></td>
    </tr>
    <tr>
        <td><img width="1010" alt="mapSelection" src="https://user-images.githubusercontent.com/72151692/135110197-6874d36b-a3d0-491c-a565-ee3a556027b1.png"></td>
        <td><img width="1010" alt="pauseMenu" src="https://user-images.githubusercontent.com/72151692/135110231-5a9cae99-268e-4508-b9aa-b76fd0b0ce97.png"></td>
    </tr>
    <tr>
        <td><img width="1010" alt="upgradesInfoMenu" src="https://user-images.githubusercontent.com/72151692/135110254-974c49bb-fdad-4f37-bf47-9be44520162b.png"></td>
        <td><img width="1010" alt="gameplay" src="https://user-images.githubusercontent.com/72151692/135110277-c0cd8d38-0634-429b-9314-762d0651126e.png"></td>
    </tr>
</table>

Demo Video
[![Demo Video Link](https://user-images.githubusercontent.com/72151692/135111606-9438b60e-664e-4dc0-874c-a834d8ead7da.png)](https://www.youtube.com/watch?v=IHWJn54g9U0&t=2s&ab_channel=Mero3379)

## Features

* Stores and retrieves high scores from a remote AWS database using MySQL.
* Makes use of multi-threading to keep logical processes isolated from the user interface.
* Saves game progress and settings in persistent storage using serialization.

## Setup

The following is the installation process for this project on Android Studio using Gradle.

### Prerequisites & Useful Links

Android Studio

- [Android Studio Download](https://developer.android.com/studio/?gclid=CjwKCAjwy7CKBhBMEiwA0Eb7aia9fn_8StaS8V_yYfje8WM6y-E4iIiXjLIRnxsbb3hTGlLEliPhdhoCn0AQAvD_BwE&gclsrc=aw.ds)

### How to Build

1. Follow the download instructions for Android Studio.
2. Clone the project - https://github.com/AmirElrahep/Tower-Defense.git
3. Open the AVD Manager and create a new virtual device: Nexus 6P running Android 8.1 Oreo (API 27)
4. Navigate to the MainActivity class

   ```sh
   com/wsu/towerdefense/view/activity/MainActivity.java
   ```

Run and enjoy!

## Contact

Amir Elrahep - [LinkedIn](https://www.linkedin.com/in/amir-elrahep-4141a1154/)
