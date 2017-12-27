# Face Detection security app project - desktop app

Face Detection security app consistі of 3 project: [Web project](https://github.com/borsch/facedetection-web), [Desktop app](https://github.com/borsch/facedetection-app), and this one

## Description
This part of project is a desktop app that use installer web camera to recognize person face and send it to the [web project](https://github.com/borsch/facedetection-web), where face will be recognized as friend or "enemy"

## Instalation
This project require OpenCV installed locally and linked as external library. OpenCV installation process described [here](http://opencv-java-tutorials.readthedocs.io/en/latest/01-installing-opencv-for-java.html). For current version was used OpenCV verion 3.3.1(or 331)

For generating GUI was used JavaFX. You can manually change GUI via xml editor or use [Scene Builder](http://www.oracle.com/technetwork/java/javase/downloads/sb2download-2177776.html) app. For current verion of project Scene Builder 2.0 was used

## Environment
Windows 7, OpenCV 3.3.1, JavaFX, Scene Builder 2.0, Eclipse Oxygen2, Java 8(1.8.0_144)

## Resource
Mostly this project duplicates [this](http://opencv-java-tutorials.readthedocs.io/en/latest/06-face-detection-and-tracking.html) OpenCV official tutorial
