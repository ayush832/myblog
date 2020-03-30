---
layout: post
title:  "Android Studio for beginners,Part 1: Installation and setup"
excerpt: " Part 1: Installation and setup"
date:   2020-03-30 02:00:00
categories: [ANDROID_DEVLOPMENT,PART1]
tags: [intallation and setup]    
---
![Intro]({{site.baseurl}}/assets/images/into.jpg){: style="max-width: 99%; max-height: 99%;"}<br>
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
I launched ```android-studio-ide-181.5056338-windows.exe``` to start the installation process. The installer responded by presenting the <b>Android Studio Setup</b> dialog box shown in Figure.<br>
<br>
Clicking Next took me to the following panel, which provides the option to decline installing an Android Virtual Device (AVD).<br>
<br>
I chose to keep the default settings. After clicking Next, I was taken to the Configuration Settings panel, where I was asked to choose where to install Android Studio.<br>
<br>
I kept the default installation location and clicked Next, and was greeted with the Choose Start Menu Folder panel.<br>
<br>
I kept the default setting and clicked Install. The following Installing panel appeared.This panel shows the progress of the installation:<br>
<br>
Clicking Show details causes the names of files being installed and other activities to be displayed. When installation finished, the Installation Complete panel appeared.<br>
<br>
After clicking Next, the installer presented the Completing Android Studio Setup panel.<br>
<br>
To complete the installation, I left the Start Android Studio box checked and clicked Finish.<br>
<br>


## Running Android Studio
The first time Android Studio runs, it presents a Complete Installation dialog box that offers the option of importing settings from a previous installation.<br>
<br>
I chose not to import settings (the default selection) and clicked OK, and was rewarded with the following splash screen:<br>
<br>
I also observed the following Finding Available SDK Components message box.<br>
<br>
At this point, Android Studio presented the following Android Studio Setup Wizard dialog box:<br>
<br>
I clicked Next, and the wizard invited me to select an installation type. I kept the default standard setting.<br>
<br>
I was then given the opportunity to choose a user interface theme.<br>
<br>
I kept the default IntelliJ setting and clicked Next. Android Studio next provided the opportunity to verify settings.<br>
<br>
I clicked Finish and Android Studio began the process of downloading SDK components.<br>
<br>
It can take several minutes for this part of the setup to finish. Clicking Show Details might relieve some boredom by revealing the various files being downloaded and unzipped.<br>
<br>
For my AMD-based computer, an unpleasant surprise awaited after the components had completely downloaded and unzipped:<br>
<br>
My options are to either put up with the slow emulator or use an Android device to speed up development. In later blog, I'll show you how I resolved this issue and how to use android device with you as a emulator.<br>
<br>
Finally, I clicked Finish to complete the wizard. The Welcome to Android Studio dialog box appeared.<br>
<br>
This dialog box is used to start up a new Android Studio project, work with an existing project, and more. It can be accessed by selecting Android Studio from the Windows Start menu, or the equivalent on another platform.<br>
## Your first Android Studio Project
From our setup so far, you should still have Android Studio running with the Welcome to Android Studio dialog box. From here, click Start a new Android Studio project. Android Studio will respond with the Create New Project dialog box.<br>
<br>
Enter HelloWorld as the application name and the company domain name will be processed automatically. On my desktop, I observed C:\Users\Rishi\AndroidStudioProjects\HelloWorld as the project location. Click Next to select your target devices.<br>
<br>
Android Studio lets you select form factors, or categories of target devices, for every app you create. I kept the default setting.<br>

Click Next, and you will be given the opportunity to choose a template for your app's main activity. For now we'll stick with Empty Activity. Select this template (if necessary) and click Next.<br>
<br>
Next you'll customize the activity:<br>
<br>
Leave that to defaults and move forward<br>
<br>
The first time you use Android Studio, you'll discover that it has to download some files related to its constraint layout, which is used to build responsive user interfaces:<br>
<br>
Android Studio enables Finish after downloading the constraint layout files. Click this button and Android Studio takes you to the main window.<br>
<br>
The main window is divided into a menu bar and several other areas, which are identified in nex two Figures. (Note that both Figures are courtesy of [Google](https://www.google.com/).)<br>
<br>
## The Project and editor windows
When you enter the main window, you observe the Project window showing only app and Gradle Scripts. You'll have to expand the app branch of the project tree to observe more details.<br>
The Project window is organized into a tree whose main branches are app and Gradle Scripts. The app branch is further organized into manifests, java, generatedJava, and res subbranches:
<ul>
<li>manifests stores ```AndroidManifest.xml```, which is an XML file that describes the structure of an Android app. This file also records permission settings (where applicable) and other details about the app.</li>
<li>java stores an app's Java source files according to a package hierarchy, which is ```mainactivity.java``` in this example. It also organizes files for testing purposes.</li>
<li>res stores an app's resource files, which are organized into drawable, layout, mipmap, and values subbranches:</li>
<ul>
<li>drawable is a mostly empty location in which to store an app's artwork; initially, the XML files for the launcher foreground and background adaptive icons are stored here.</li>
<li>layout is a location containing an app's layout files; main.xml (the main activity's layout file) is initially stored here.</li>
<li>mipmap is a location containing various ic_launcher.png files, which store launcher screen icons of different resolutions.</li>
  <li>values is a location containing colors.xml, strings.xml, and styles.xml.</li>
</ul>
</ul>


The Gradle Scripts branch identifies various .gradle (such as build.gradle) and .properties (such as local.properties) files that are used by Android Studio's Gradle-based build system.

## Conclusion
You've installed and configured Android Studio and created a project for your first Android Studio mobile app; now you're ready to build your Android application. In Android Studio, this means populating your new project with Java source code and resource files.

<br><br>
### EDIT: [Rishi Agrawal](https://rishiagrawal2609.github.io/). 



