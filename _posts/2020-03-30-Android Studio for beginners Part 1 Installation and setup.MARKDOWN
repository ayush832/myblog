---
layout: post
title:  "Android Studio for beginners,Part 1: Installation and setup"
excerpt: " Part 1: Installation and setup"
date:   2020-03-30 02:00:00
categories: [ANDROID_DEVLOPMENT,PART1]
tags: [intallation and setup]    
---
# Android Studio for beginners, Part 1: Installation and setup
For some years now it's been clear that Android is a force to be reckoned with in the mobile OS landscape. This Java-based technology has sparked a new gold rush, with programmers competing to make money from their mobile apps.<br>
To be successful, Android developers need a good grasp of the Java language (or Kotlin), Android APIs, and Android application architecture. It's also important to use an appropriate and effective development environment. For many years, Eclipse IDE with the ADT plugin was the preferred platform for Android development. Today, it's Android Studio.<br>
In this blog, I'll briefly introduce the Android development platform, then show you how to download, install, and run the software. <br>


## Get started with Android Studio
Android Studio is Google's officially supported IDE for developing Android apps. This IDE is based on IntelliJ IDEA, which offers a powerful code editor and developer tools. Android Studio 3.2.1 includes the following features:<br>
<ul>
  <li>A flexible Gradle-based build system</li>
  <li>A fast and feature-rich emulator</li>
  <li>A unified environment where you can develop for all Android devices</li>
  <li>Instant Run to push changes to your running app without building a new APK</li>
  <li>Code templates and GitHub integration to help you build common app features and import sample code</li>
  <li>Extensive testing tools and frameworks</li>
  <li>Lint tools to help you catch performance, usability, version compatibility, and other problems</li>
  <li>C++ and NDK support</li>
  <li>Built-in support for Google Cloud Platform, making it easy to integrate Google Cloud Messaging and Google App Engine</li>
  <li>Plugin architecture for extending Android Studio via plugins</li>
</ul> 


## Download Android Studio
Google provides Android Studio for the Windows, Mac OS X, and Linux platforms. You can download Android Studio from the Android Studio homepage, where you'll also find the traditional SDKs with Android Studio's command-line tools. Before downloading Android Studio, make sure your platform meets the following requirements:


### Windows requirements
<ul>
  <li>Microsoft Windows 7/8/10 (32-bit or 64-bit)</li>
  <li>3 GB RAM minimum, 8 GB RAM recommended (plus 1 GB for the Android Emulator)</li>
  <li>2 GB of available disk space minimum, 4 GB recommended (500 MB for IDE plus 1.5 GB for Android SDK and emulator system image)</li>
  <li>1280 x 800 minimum screen resolution</li>
</ul>


### Mac OS requirements
<ul>
  <li>Mac OS X 10.10 (Yosemite) or higher, up to 10.13 (High Sierra)</li>
  <li>3 GB RAM minimum, 8 GB RAM recommended (plus 1 GB for the Android Emulator)</li>
  <li>2 GB of available disk space minimum, 4 GB recommended (500 MB for IDE plus 1.5 GB for Android SDK and emulator system image)</li>
  <li>1280 x 800 minimum screen resolution</li>
</ul>


### Linux OS requirements
<ul>
  <li>GNOME or KDE desktop. Tested on Ubuntu 14.04 LTS, Trusty Tahr (64-bit distribution capable of running 32-bit applications)</li>
  <li>64-bit distribution capable of running 32-bit applications</li>
  <li>GNU C Library (glibc) 2.19 or later</li>
  <li>3 GB RAM minimum, 8 GB RAM recommended (plus 1 GB for the Android Emulator)</li>
  <li>2 GB of available disk space minimum, 4 GB recommended (500 MB for IDE plus 1.5 GB for Android SDK and emulator system image)</li>
  <li>1280 x 800 minimum screen resolution</li>
</ul>


Once you've ensured that your operating system is compatible with Android Studio 3.2.1 or higher, download the appropriate Android Studio distribution file. The Android Studio download page auto-detected that I'm running a 64-bit Windows operating system and selected android-studio-ide-181.5056338-windows.exe (927 MB) for me to download.

#### [Link to download android studio](https://developer.android.com/studio)

## Installing Android Studio on 64-bit Windows 10
I am going to show how to install Android Studio on windows 10 only as I don't have access to MacOS or Linux.<br>
I launched '''android-studio-ide-181.5056338-windows.exe''' to start the installation process. The installer responded by presenting the <b>Android Studio Setup</b> dialog box shown in Figure 1.
