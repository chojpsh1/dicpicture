# dicpicture
Android application project for translating objects in picture to language which user wants.

This project is considered user wants to say some object in foreign language. When user takes a picture including that object with this application, this application translates the object's name to the foreign language.

## Local Env

##### Install Android Studio

##### Create Google Cloud Translation API key

> Follow the Google Cloud Translation API documentations. (https://cloud.google.com/translate/?authuser=2&hl=ko)

## code
* app/src/main/java/com/example/seoyukyung/dicpicture/MainActivity.java
>It's the main program. It calls functions which are connect to goole API, open camera or gallery and translate the object's name in picture through API to launage user selected.

* app/src/main/res/layout/activity_main.xml
>It's the main UI setting code.
