# Week1-T1-windows-RNA
# React Native App 
This app demonstrates use of react-native to create project which use react-navigation and run on win10 development system.

## To test this out

1. Clone repository   
```
git clone https://github.com/rajnishc8/Week1-T1-windows-RNA
cd Week1-T1-windows-RNA
npm install
react-native run-windows
```

## Get Started

### Creating this app 
1.  react-native init Week1-T1-windows-RNA
2.  cd Week1-T1-windows-RNA
```
    2a.) npm install --save react-navigation
    2b.) npm install --save react-native-vector-icons  <- run this from admin command prompt.
    2c.) npm install
    2d.) react-native link        <- do this after installing all npm packages.
```
3.) npm install --save-dev rnpm-plugin-windows
4.) npm install react-native@0.50  <-- rnpm-plugin-windows(react-native-windows@0.50.0-rc.2) only works with react-native@0.50 at the moment. It may not be required later.
5.) react-native windows
6.) react-native run-windows
7.) Your app should be running now on windows!
     if you get "red screen" . wait for Metro Bundler to start. just keep on pressing 'Reload Javascript" button until Metro builder start's.

8.) Update app.windows.js to change code.
9.) react-native run-windows
