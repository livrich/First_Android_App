# Overview

Before this, I had never used Android Studio. My original goal was to develop an app that calculated the N P K percentage values of a bag of fertilizer.
I wanted to do this using Flutter/Dart. Thus, my initial effort was spent figuring out how to get Flutter and Android Studio working. I got both working.
However, as I started playing with Android Studio, I realized it was more intricate and complex than I had assumed or anticipated. As a result, I decided
to hone in my focus to just learning how to operate Android Studio. In the future, I'd still like to learn Flutter/Dart.

Not sure where to start with Android Studio, I decided to follow a tutorial that would walk me through some of the basics. The tutorial I followed is linked
below. It is the first link under the "Useful Websites" section. I didn't realize until I was on one of the last steps of the tutorial that it hadn't been
updated since 2020. As such, I ran into a number of errors while trying to follow the tutorial. 

The first problem I ran into was independent from the tutorial. I originally set up my environment on my primary work computer. However, the specs on that
computer aren't that good. Normally, it can handle whatever I'm trying to do. Android Studio requires a lot of RAM to be able to run quickly and keep
up with the progressively more complicated emulator display. My computer was struggling to keep up. Therefore, once I realized that, I switched to my more powerful computer and reset up my
environment. That eliminated a number of problems I was having and allowed me to progress more quickly.

The other major problems I ran into were trying to change the background color of buttons and applying safe args.

Since the tutorial I was following was outdated, they were working from different base code than I was. As such, I spent a lot of time figuring out how to
change the background color of a button. What the tutorial said didn't work for me. I eventually found a solution. Granted, the solution isn't perfect. It
allowed me to change the background color of buttons but also got rid of the action bar. I had to change the theme of the app from the preset dark mode to a
light mode. For reasons I still don't fully understand, out of the numerous themes I tried, the only one that would let me change the default button background
color was a light mode that specifically specified not action bar. After spending some time trying to figure out how to get the action bar back, I decided to move
on without fixing it. My hope was I would learn more about Android Studio and maybe the extra knowledge would help me fix the action bar problem more easily.

Again, because the tutorial was outdated, it specified a way to implement safe args that is no longer used. I again turned to the internet to find a solution.
After a lot of searching, trying a solution to get another error, searching how to fix that new problem and trying some more code, I finally got safe args to work
without initially throwing an error. The next step after getting safe args working is to rebuild the code base so that the functionality of safe args will be fully
recognized. When I tried doing that, three more errors were thrown. The first of which had to do with a class not being abstract.

By this point, I had exhausted the time I allotted for this project. Thus, I decided to comment out the code related to safe args and call it there for now.

From this experience, I think app development could be really fun. Despite the problems I ran into, working with Android Studio was rewarding and I enjoyed seeing
the app come together. I still have a lot to learn about Android Studio and app development though. I came to understand many of the capabilities of Android
Studio, but admittedly, I don't understand all the code I was working with yet.

Currently, as the app stands, there is a "Toast" button that displays a temporary message at the bottom of the screen. There's a "Count" button that, upon clicking it,
increments the number in the middle of the screen by one. The "Random" button was supposed to interact with the second fragment to display a random number between zero
and the current value of count. If it had worked, when clicked, a message with the random number would have displayed at the top of the screen. However, part of the code
was dependent upon getting safe args working. Thus, as explained above, the "Random" button currently doesn't do anything.

For a demonstration of the working parts of the app watch the video below.

[App Demo Video](https://youtu.be/PJxGUJKAoxI)


# Development Environment

* Language: Kotlin
* IDE: Android Studio
* Control Manager: GitHub


# Useful Websites

* [Tutorial](https://developer.android.com/codelabs/build-your-first-android-app-kotlin#0)
* [Android Developer](https://developer.android.com/)
* [Gradle](https://discuss.gradle.org/)
* [DelftStack](https://www.delftstack.com/)
* [Geeks for Geeks](https://www.geeksforgeeks.org/)
* [Stack Overflow](https://stackoverflow.com/)


# Future Work

* How to change the background color of buttons without getting rid of action bar
* How to implement safe args without causing errors
* Fix abstract class/other errors that resulted from implementing safe args and trying to rebuild the project
* Start a new project from scratch where I create something original
* Learn how to use Flutter/Dart with Android Studio
