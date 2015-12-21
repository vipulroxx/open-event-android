# Add-documentaion-Open-Event-Android-App

How to build #open-event-android
# open-event-android
[![Build Status](https://travis-ci.org/fossasia/open-event-android.svg)](https://travis-ci.org/fossasia/open-event-android)
The Open Event Android Client

The Android client is a generic app that has two parts:
a) A standard configuration file, that sets the details of the app (e.g. color scheme, logo of event, link to JSON app data)
b) The Android app itself
This app uses the json api provided by a server maintained [here](https://github.com/fossasia/open-event-orga-server). 

## Development Setup
Before you begin, you should already have the Android Studio SDK downloaded and set up correctly. You can find a guide on how to do this here: [Setting up Android Studio](http://developer.android.com/sdk/installing/index.html?pkg=studio)

##Steps:
1. Download the *open-event-android* project source. You can do this either by forking and cloning the repository (recommended if you plan on pushing changes) or by downloading it as a ZIP file and extracting it.
2. To clone it simply paste this command on terminal/bash:
			git clone https://github.com/fossasia/open-event-android.git
3. Open Android Studio, you will see a **Welcome to Android** window. Under Quick Start, select *Import Project (Eclipse ADT, Gradle, etc.)*
4. Navigate to the directory where you saved the open-event-android project, select the root folder of the project (the folder named "open-event-android"), and hit OK. Android Studio should now begin building the project with Gradle.
5. Check for errors in Message section.
  // Errors you can get :
   > Dependencies error
   > Resolve errors
   > Installing errors like JDK- 7 required, gradle needs to be installed or even android api 21 installation
   
  // How to fix errors
  > Installation of JDK - 7 can be done by visiting the url underneath the error.
  > Installation of Android api can also be done in the same way as above.
  > Infact, all downloading and installation errors can be fixed by visitng links underneath the url.
  > If there are any resolve errors, try visiting this link for help ( http://stackoverflow.com/questions/28493470/gradle-failed-to-resolve-library-in-android-studio ) or there is always our mailing list on IRC (#fossasia).
6. Once all build errors have been resolved, you should be all set to build the app and test it.
7. To Build the app, go to *Build>Make Project* (or alternatively press the Make Project icon in the toolbar).
8. If the app was built succesfully, you can test it by running it on either a real device or an emulated one by going to *Run>Run 'app'* or presing the Run icon in the toolbar.