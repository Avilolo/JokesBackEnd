# JokesBackEnd

JokesBackEnd
The JokesBackEnd repository contains the backend code for the Jokes App project. It provides the API endpoints to fetch random jokes and perform other related operations.

This repository contains the Android application for the Jokes App project. The Jokes App is a mobile application that displays random jokes to users.

Features:
-Fetches random jokes from the JokesBackEnd API.

-Displays jokes in a user-friendly interface.

-Provides a search functionality to find specific jokes.


Installation
To install and run the Jokes App Android application, follow these steps:


Build and run the application on an Android emulator or a physical device.

Dependencies:
The Jokes App Android application relies on the following dependencies:

****TO USE API*****

Since the API ip constantly changes you need to update by hand the new ip.

In file mylibrary/src/main/java/com/example/mylibrary/MyJokes.java:
change the local ipv4 to your ipv4 ("API_URL").

add this to your build.gradle:

allprojects {
		repositories {
			...
			maven { url 'https://jitpack.io' }
		}
	}
  
  Add dependency:
  
  dependencies {
	        implementation 'com.github.Avilolo:mylibrary:Tag'
	}
  
  *******image to show implementing the Library works in new project******
  ![image](https://github.com/Avilolo/JokesAppAndroid/assets/117349493/2ed84b4d-91e0-47f8-9b83-e7b9e6a60cf9)
