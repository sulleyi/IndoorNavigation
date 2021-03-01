# IndoorNavigation

## Overview

This is a app designed to find the fastest routes through the ISEC building on the Union College Campus. First, a virtual map of the envirnoment was made using ARCore Anchor points to mark potential points of interest. These anchor points and their location data is stored on a Firebase instance. Through the Futter UI, users initialize their position using a scannable QR code. Then they are able to select a destination node. The shortest path is calculated using Dijkstra's Algorithm (potentially A* later) and directions are displayed in the AR Environment.

## Stack

- Flutter

Flutter is used for a simple UI. Well integrated wth Firebase and ARCore.

- ARCore

Works with both Android and IOS. Used for mapping physical environment and displaying navigation directions.


- Firebase

Simple cloud storage for ARCore Anchors and saved user routes.



Resources:

- https://youtu.be/qYet1ka1J3I
- https://blog.raccoons.be/arcore-powered-indoor-navigation-unity
