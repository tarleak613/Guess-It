This is a react-native application using EXPO

Lets break it into two sections:

1. UI was created using figma
   <img width="554" alt="image" src="https://github.com/tarleak613/Guess-It/assets/134609299/cc7b1f9b-b74f-41cf-9b55-2f2ad88a7f2c">

2. The actual implmentation was done via React-native Expo
   
 <img width="196" alt="image" src="https://github.com/tarleak613/Guess-It/assets/134609299/273a6885-ec64-49db-bb53-a79ba0564a35">
 
 <img width="197" alt="image" src="https://github.com/tarleak613/Guess-It/assets/134609299/ac4606fc-a800-4ae4-a020-5dd3a5af904f">
 
 <img width="200" alt="image" src="https://github.com/tarleak613/Guess-It/assets/134609299/dbbb85f5-2c5a-4472-8335-dd51e4deb11e">
 
 <img width="194" alt="image" src="https://github.com/tarleak613/Guess-It/assets/134609299/3971f114-3de5-4cf5-af3f-449cad801191">
 
 <img width="195" alt="image" src="https://github.com/tarleak613/Guess-It/assets/134609299/a6384066-9746-4fee-b83f-564dbef46aa5">
 
HOME SCREEN
--it shows categories to choose 
--all the categories consists of their particular words 

RULES SCREEN
--here the rules of the game is shown
--there is drop-down menu to select the duration of the game
--a play button to start the game

COUNTDOWN SCREEN
--5 second countdown 
--rotate screen gifs

GAMEPLAY SCREEN
--shows a random word according to the category
--tilt down to answer (word turns green with two partypopper gifs)
--tilt up to pass ( word turns red indicating it's a pass)

SCORECARD SCREEN
--list of correct and indirect answers
--restart button to play again

COMMNANDS TO BUILD AN EXPO FILE

npm install -g eas-cli
eas login
eas build:configure
eas build --platform android

for more information visit
https://docs.expo.dev/build/setup/

COMMANDS TO DOWNLAOD THE APK ON YOUR LOCAL EMULATOR

  "build": {
    "preview": {
      "android": {
        "buildType": "apk"
      }
    },
    "preview2": {
      "android": {
        "gradleCommand": ":app:assembleRelease"
      }
    },
    "preview3": {
      "developmentClient": true
    },
    "preview4": {
      "distribution": "internal"
    },

  Replace these lines of code in eas.json file
  and run on the terminal:
  eas build -p android --profile preview

For more information visit
https://docs.expo.dev/build-reference/apk/

To track the build process login in your expo account
<img width="955" alt="image" src="https://github.com/tarleak613/Guess-It/assets/134609299/aa998497-6c7a-484d-803b-0ec2bc8ad3b2">

