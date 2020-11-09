# conviva-android-nexstreaming
## Conviva nexstreaming module can be included in two ways in any Android app projects.

* Gradle dependency
* Offline library

## Gradle dependency
    Add the following line to app's build.gradle file.
    
    implementation 'com.conviva.sdk:conviva-nexplayer-sdk:4.0.2'
    
## Offline library
    Place the Conviva library in app's 'lib' folder and add the following line to app's build.gradle file.
    
    implementation fileTree(dir: 'libs',include:['*.aar'])

## Supported Android OS Version    
    Android 11

## Supported NexPlayer SDK Version    
    NexPlayer 6.71
    
## Note:  

* Refer https://community.conviva.com/ for integration guidelines.
