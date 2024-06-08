# SignLingo - Sign Language Recognition App 
The SignLingo is a powerful, innovative application designed to interpret sign language gestures in real-time. Utilizing a comprehensive dataset of 11,391 images across 25 classes, this app leverages advanced image processing techniques and machine learning algorithms to accurately recognize and translate sign language into text and speech, providing an inclusive communication tool for individuals with hearing impairments.


## Features
- **Real-time Sign Language Recognition:** Users can perform gestures, and the app will recognize and convert them to text in real-time.
- **Text-to-Speech Conversion:** Construct words by signing letters, and the app will read the complete word aloud.
- **User Authentication:** Secure user accounts managed through Firebase Authentication.

## Dataset
The dataset includes:
- **Total Images:** 11,391
- **Classes:** 25 (each representing a different sign language gesture)
- **Images per Class:** Between 397 to 500

## Technology Stack
- **OpenCV:** For image processing and edge detection to enhance gesture recognition.
- **Firebase:** For backend authentication and user management.
- **Android Studio:** Used for developing the Android application.

## Image Processing
Edge detection is a crucial step in our sign language recognition system. By focusing on the boundaries and distinct shapes of hand gestures, edge detection helps to transform images into a format that is easier for our model to analyze and recognize. This preprocessing step significantly improves the accuracy of gesture recognition.

## Installation and Setup

### Prerequisites
- Android Studio
- Firebase account

### Steps
1. **Clone the Repository**
    ```bash
    git clone https://github.com/your-username/SignLingo.git
    cd SignLingo
    ```

2. **Open in Android Studio**
   - Open Android Studio and select "Open an existing Android Studio project."
   - Navigate to the cloned repository and open it.

3. **Set Up Firebase**
   - Go to the [Firebase Console](https://console.firebase.google.com/).
   - Create a new project or use an existing one.
   - Add your Android app to the Firebase project and follow the instructions to download the `google-services.json` file.
   - Place the `google-services.json` file in the `app/` directory of your project.
   - Enable Firebase Authentication in the Firebase Console.

4. **Build and Run the App**
   - Sync the project with Gradle files.
   - Build and run the app on an Android device or emulator.

## Usage
1. **Sign Up / Sign In**
   - Open the app and sign up for a new account or sign in with an existing account.
   
2. **Recognize Sign Language**
   - Navigate to the sign recognition section.
   - Perform the sign language gesture in front of the camera. The app will display the recognized text.

3. **Text to Speech**
   - Use the recognized letters to form words.
   - The app will read the complete word aloud once it's formed.
   
## Demo Video 

https://github.com/Roohishaik/SignLingo/assets/94975857/0a3c29e2-2681-4c3a-8c32-7abd02b1c627
                                 
---

Thank you for using the Sign Language Recognition App. Together, we can bridge the communication gap and make interactions more inclusive for everyone.
