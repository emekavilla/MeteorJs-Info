# MeteorJs-Info

Meteor JS

Meteor JS is a full-stack JavaScript platform for developing modern web and mobile applications. Meteor includes a key set of technologies for building connected-client reactive applications, a build tool, and a curated set of packages from the Node.js and general JavaScript community.

Meteor allows you to develop in one language, JavaScript, in all environments: application server, web browser, and mobile device.

Meteor uses data on the wire, meaning the server sends data, not HTML, and the client renders it. Meteor embraces the ecosystem, bringing the best parts of the extremely active JavaScript community to you in a careful and considered way.

Meteor provides full stack reactivity, allowing your UI to seamlessly reflect the true state of the world with minimal development effort.

TO CREATE AN APP USING METEOR

First make sure you have meteor installed on your mac by running "which meteor" in terminal. If not install by running this command:

curl https://install.meteor.com/ | sh

To start,

Run "meteor create my-app"

All necessary files will be created inside the my-app folder.

Next:

cd my-app meteor npm install meteor

Then go to http://localhost:3000 to view running app

CAN MY APP BE IOS AND ANDROID READY? HECK YES MI AMIGIS!!!!

Running on an iOS simulator (Mac Only)

If you have a Mac, you can run your app inside the iOS simulator. Go to your app folder and type: meteor install-sdk ios

This will run you through the setup necessary to build an iOS app from your project. When you're done, type:

meteor add-platform ios meteor run ios

You will see the iOS simulator pop up with your app running inside.

Running on an Android emulator

In the terminal, go to your app folder and type: meteor install-sdk android

This will help you install all of the necessary tools to build an Android app from your project. When you are done installing everything, type:

meteor add-platform android

After you agree to the license terms, type: meteor run android

After some initialization, you will see an Android emulator pop up, running your app inside a native Android wrapper. The emulator can be somewhat slow, so if you want to see what it's really like using your app, you should run it on an actual device.

Running on an Android device

First, complete all of the steps above to set up the Android tools on your system. Then, make sure you have USB Debugging enabled on your phone and the phone is plugged into your computer with a USB cable. Also, you must quit the Android emulator before running on a device. Then, run the following command:

meteor run android-device

The app will be built and installed on your device.

Running on an iPhone or iPad (Mac Only; requires Apple developer account)

If you have an Apple developer account, you can also run your app on an iOS device. Run the following command:

meteor run ios-device

This will open Xcode with a project for your iOS app. You can use Xcode to then launch the app on any device or simulator that Xcode supports. Now that we have seen how easy it is to run our app on mobile, let's get to adding some more features.

By Emeka and Darc
