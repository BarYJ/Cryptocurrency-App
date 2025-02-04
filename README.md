# Let's Code React-Native

## [Watch it on YouTube](http://bit.ly/ByProgrammersYT)

In this episode of "Let’s Code React Native" series, we are going to build a clean looking Cryptocurrency app based on the design created by David Morgan on Dribbble.

Be sure to subscribe to our YouTube channel for more videos like this!

## Table of Contents

| Code | Project | Preview | Inspiration | No. of Screens |
| ------ | ------ | ------ | ------ | ------ |
| LCRN09 | [Cryptocurrency App](https://youtu.be/xBmx2eaozck) | <img src="https://cdn.dribbble.com/users/3712718/screenshots/14896748/media/46be264ccd9a8a2c05691e657be48167.png?compress=1&resize=1200x900" width="120" /> | [View](https://dribbble.com/shots/14896748-Cryptocoin-App-concept) | 4 |

## Contributors

<a href="https://github.com/byprogrammers/lets-code-react-native/graphs/contributors">
  <img src="https://contributors-img.web.app/image?repo=byprogrammers/lets-code-react-native" />
</a>

## Splah screen (for ios)
npm i react-native-splash-screen --save
react-native link
cd ios , pod install , cd ..

// insert these into AppDelegate:
#import "RNSplashScreen.h"  // here

[RNSplashScreen show];  // here (under didFinishLaunching... right before return YES)


## React Native Gradient
npm install react-native-linear-gradient --save
react-native link
cd ios , pod install , cd.. (Everytime installed a new library, re-install pod)


## Install Victory Native (For graph chart)

npm install victory-native --save

npm install react-native-svg --save

## running the app
react-native run-ios

