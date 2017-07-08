# HelloApolloAndroid
This is modified version of apollo-android sample app with all the bug fixes. https://github.com/apollographql/apollo-android

## Why use this ?
Current appolo android sample app is does't work properly, first it refers all the dependecies locally by referencing the project. Second it has issues in running the app with current server returning null for 1 query. 

## What is added
* I removed all the local dependcies and updated it to point to actual apollo android dependcies from mvn central. 
* Fixed the compilation issue with other RX dependecny.

This is just an attempt to provide a working android app with very simple hello world intergation of apollo android client. For more info on apollo android please check https://github.com/apollographql/apollo-android
