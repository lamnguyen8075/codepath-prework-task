# codepath-prework-task
# Android Prework - *GREETING APPLICATION*

Submitted by: **LAM NGUYEN**

**Greeting Application** is an android app that shows an image and introductory message, and allows pressing a button to display a Toast. 
On the main screen, you will see 3 components including the welcome picture, introductory string and a button. All of these components seating on the 
top of a colorful background. When user click on the button, It will show the string to response to the user. 

Time spent: **5** hours spent in total

## Required Features

The following **required** functionality is completed:

* [x] Image and introductory message displayed on screen
* [x] Button displayed on screen
* [x] Toast with message appears when button is pressed 

The following **optional** features are implemented:

* [x] List anything else that you can get done to improve the app functionality!
- I used android:background="@drawable/bg" under ConstraintLayout to set the background of the picture to make it beatiful
- I implemented android-gif-drawable to make the program able to handle the gif file
## Video Walkthrough

Here's a walkthrough of implemented features:
<br/>
<img src='https://i.imgur.com/xkKkCgP.gif' title='Video Walkthrough' width='' alt='Video Walkthrough' />

<!-- Replace this with whatever GIF tool you used! -->
[GIPHY] https://giphy.com/

## Notes
This is the first time building the Kotlin App! 
It was so much fun when I debugged the code. In the 2nd part, I changed the photo, I used the tools:srcCompat() so the image only appear on the model in 
of the compiler. It didnt' show the photo in the app on the virtual device. After troubleshooting, I figured out the mistake that I need to use 
app:srcCompat()

## License

    Copyright 2022 LAM NGUYEN

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
