# Noteify
## Noteify is a currency detection app made for the visually impaired to check whether they have been handed the right amount of money and thereby, ensuring that they have not been cheated upon, giving the output as a computer-generated audio, having basic UI for better User-Experience. 

This is a project done by me and my partner <a href= "https://github.com/Ashniz24"> Ashna Nizam </a> and the app was developed using Flutter.

The main modules used are:

***camera*** <br>
***tflite*** <br>
***flutter_tts*** <br>
***path_provider***

The backend comprises of the tflite package using a tflite model along with the labels which specifies all the classes. The flutter_tts is a text-to-speech module in flutter used to convert text to speech, used here so that the output can be obtained as an audio.

<img src="screenshots/200.jpeg" width="300px" height=auto> <img src="screenshots/500claased.jpeg"  width="300px" height=auto>


**Advantages**
1. No authentication/login required.<br>
2. No internet connection required.<br>
3. Highly User-friendly <br>
4. Local storage will not be further consumed after installation.<br>
5. Good-high accuracy in predicting.<br>
6. A total calculating feature.<br>
7. Computer-generated audio output.<br>

**Disadvantages**
1. Heavy app.<br>
2. High battery consumption.<br>
3. Lesser accuracy if the image is blurry or dimly lit.<br>
4. Prone to crashes if phone has poor/low specifications.


## How to clone
1. Create a flutter app in your local system using android studio and name it Noteify <br>
2. Download the repo. <br>
3. Add the files in the **assets** folder into your local system assets folder. <br>
4. Copy paste *main.dart* and *pubspec.yaml* files from the repo. <br>
5. Change the **minsdkversion** in the /*android/app/build.gradle/* to 21. <br>
6. Run **packages.get** in *pubspec.yaml* <br>
7. Run the *main.dart*.

## Check out CONTRIBUTING.MD to learn how to contribute.
