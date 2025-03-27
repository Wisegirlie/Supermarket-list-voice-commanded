# Voice-Enabled To-Do List App  
Effortlessly manage tasks using voice commands or manual input. Perfect for staying organized on the go!  

## Features  
- Add tasks via voice commands  
- Easy-to-use interface  

## Installation  
1. Clone the repository  
2. Install dependencies:
   - Navigate to the project folder and run ***"npm install"***
   - Navigate to the client folder and run ***"npm install"***
3. Set up environment variables:
   - Create a ***.env*** file in the root folder.
   - You have to get a GOOGLE API KAPI KEY for using Google Speech-to-text (https://cloud.google.com/speech-to-text#turn-speech-into-text-using-google-ai)
   - Add the following variables to connect with GOOGLE API:
     - ***GOOGLE_API_KEY=your-google-speech-to-text-api-key***     
   -Add the following variable to connect to mongoDB:
     - ***MONGO_URI=your-mongo-uri***
4. Update the API URLs in the client
   - Go to client/service/taskService.js and set the API_URL to ***"http://{Your Local IP Address}:3000"***
   - Go to client/functions/transcribeSpeech.js and set the rootOrigin to ***"http://{Your Local IP Address}"***
5. Run the app:
   - go to the client folder and run ***"npm start"***
   - on the project folder run ***"npx run dev***  
5. View and use with Android Emulator and/or Expo GO in your mobile.
  

## Demo
https://drive.google.com/file/d/1M2EWYSqiZJYV3xog30P0I3CLrIEBKAPS/view?usp=sharing


## Contributors  
- Rebecca Liu 
- Gabriela Waisman
- Mauro Zegarra 
- Ming-Hsun Hsu
- Jordan Coque  

