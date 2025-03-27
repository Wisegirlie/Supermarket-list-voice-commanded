# Voice-Enabled Supermarket List App  
Effortlessly manage you supermarket list using voice commands or manual input. Perfect for staying organized on the go!  
The Supermarket List App allows users to easily create and manage their shopping lists using voice commands.

## Features  
- Add and deleete products via voice commands  
- Check and uncheck items with voice commands
- Easy-to-use interface  

## Extra features:
- You can use voice command or manual input
- Check and delete products by one-touch buttons
- Duplicates check
- Add one or more products in the same command.
- Works in IOS and Android

## Languages, Databases, APIs and Frameworks used:
React Native
Expo
Node.js
Express
MongoDB
Google Speech-to-Text API

## Installation  
This app runs in an Android Emulator in your desktop amd/or Expo Go in your mobile phone.
It won't run in a regular browser.

1. Clone the repository  
2. Install dependencies:
   - Navigate to the project folder and run ***"npm install"***
   - Navigate to the client folder and run ***"npm install"***
3. Set up environment variables:
   - Create a ***.env*** file in the project root folder.
   - You have to get a GOOGLE API KEY to use Google Speech-to-text (https://cloud.google.com/speech-to-text#turn-speech-into-text-using-google-ai)
   - Add the following variables to connect with GOOGLE API in the .env file:
     - ***GOOGLE_API_KEY=your-google-speech-to-text-api-key***     
   -Add the following variable to connect to the mongoDB on your desired location:
     - ***MONGO_URI=your-mongo-uri***
4. Update the API URLs in the client to work locally:
   - Go to client/service/taskService.js and set the API_URL to ***"http://{Your Local IP Address}:3000"***
   - Go to client/functions/transcribeSpeech.js and set the rootOrigin to ***"http://{Your Local IP Address}"***
5. Run the app:
   - go to the client folder and run ***"npm start"***
   - on the project folder run ***"npm run dev***  
5. View and use with Android Emulator and/or Expo GO in your mobile.
  
## Demo
You can watch a video demo of the running app:
https://drive.google.com/file/d/1M2EWYSqiZJYV3xog30P0I3CLrIEBKAPS/view?usp=sharing

## Screenshots

![Image] (./screenshots/Screenshot-01.jpg)
![Image] (./screenshots/Screenshot-02.jpg)

## How to use it

- Open the app
- Tap the microphone icon to activate the voice recognition feature.
- Say the command and product. For example:
   “Add milk“ 
   “Add milk, bread and eggs“ 
   “Complete milk“
   “Delete grapes“
- Tap the microphone icon to stop the voice recognition feature.
- The list will update automatically.

## Contributors  
- Rebecca Liu 
- Gabriela Waisman
- Mauro Zegarra 
- Ming-Hsun Hsu
- Jordan Coque  
