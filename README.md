# IndoorNavigation

## Overview

This is a app designed to find the fastest routes through the ISEC building on the Union College Campus. First, a virtual map of the envirnoment was made using ARCore Anchor points to mark potential points of interest. These anchor points and their location data is stored on a Firebase instance. Through the Futter UI, users initialize their position using a scannable QR code. Then they are able to select a destination node. The shortest path is calculated using Dijkstra's Algorithm (potentially A* later) and directions are displayed in the AR Environment.

## Stack

- Flutter [Docs](https://flutter.dev/docs)

Flutter is used for a simple UI. Well integrated wth Firebase and ARCore.

- ARCore [Docs](https://developers.google.com/ar/reference/java/com/google/ar/core/package-summary)

Works with both Android and IOS. Used for mapping physical environment and displaying navigation directions.


- Firebase [Docs](https://firebase.google.com/docs/firestore/quickstart?authuser=1#java)
_Cloud Firestore_


Simple cloud storage for ARCore Anchors and saved user routes.



## Resources/Inspiration:

- https://youtu.be/qYet1ka1J3I
- https://blog.raccoons.be/arcore-powered-indoor-navigation-unity
- Incorporating Java code: https://www.calloftechies.com/2019/06/how-to-use-java-or-kotlin-with-flutter.html
