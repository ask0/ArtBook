# ArtBook App
This Android application is a small educational project to showcase fundamental concepts of Android development. It serves as a local gallery for users to store their favorite art pieces. The app allows users to add art entries with an image, artist name, art name and year. Images are fetched from the local storage of the device and added to the gallery.

# Educational Purpose
This project is suitable for those learning:

* How to create and manage a local database in Android.
* How to handle permissions to access device storage.
* How to use RecyclerViews to display a list of custom data objects.
* How to navigate between different activities and pass data between them.
* How to handle image data in Android, including selecting images from device storage.

# Features
* The main activity shows a list of saved art pieces. 
* Clicking an art piece shows detailed information about it. 
* From the main activity, users can navigate to a form to add new art pieces. 
* Users can select images from their phone storage.

# Usage
# Prerequisites
* Android Studio
* Emulator or physical Android device for testing

# Getting Started
1. Clone the repository
~~~
git clone https://github.com/ask0/artbook.git
~~~

2. Open the project
Open the project in your favorite IDE (e.g., Android Studio)

3. Run the project
Build and run the project on an emulator or real device.

# Classes
* Art : This is the data class used to define the art objects stored in the local database.
* MainActivity : This is the main activity class of the application. It shows the list of art pieces stored in the local database.
* ArtActivity : This activity is responsible for adding new art pieces to the gallery. It also handles permission requests to access the local storage of the device.
* ArtAdapter : This is the RecyclerView Adapter for the art list shown in the MainActivity.

# Permissions
The application requires permission to access the local storage of the device to fetch the images of the art pieces.

# Screenshots 


# Contributing
As this is an educational project for demonstrating basic Android development concepts, contributions are not necessary. However, feel free to fork it and use it as a basis for any other project that might benefit from these features.

# Acknowledgements
This project uses the Android Jetpack library for managing activity results and permissions.
Bitmap manipulation techniques were learned from Android documentation.




