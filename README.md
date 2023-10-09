# Android-Tesseract-OCR


<h3>Add the JitPack repository to project root `build.gradle` file at the end of repositories:</h3>

       allprojects {
           repositories {
               ...
               maven { url 'https://jitpack.io' }
           }
       }

<h3>Add dependency to app `build.gradle`</h3>

       dependencies {
           implementation 'cz.adaptech:tesseract4android:4.0.0'
       }