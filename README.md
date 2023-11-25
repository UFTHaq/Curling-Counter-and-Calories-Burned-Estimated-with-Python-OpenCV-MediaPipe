![GitHub last commit](https://img.shields.io/github/last-commit/UFTHaq/Curling-Counter-and-Calories-Burned-Estimated?style=for-the-badge)
![GitHub top language](https://img.shields.io/github/languages/top/UFTHaq/Curling-Counter-and-Calories-Burned-Estimated?label=Python&logo=python&logoColor=white&style=for-the-badge)
![OpenCV](https://img.shields.io/badge/opencv-%23white.svg?style=for-the-badge&logo=opencv&logoColor=white&color=grey&labelColor=green)
![PyCharm](https://img.shields.io/badge/pycharm-143?style=for-the-badge&logo=pycharm&logoColor=black&color=grey&labelColor=green)
![GitHub code size in bytes](https://img.shields.io/github/languages/code-size/UFTHaq/Curling-Counter-and-Calories-Burned-Estimated?style=for-the-badge)
![GitHub Repo stars](https://img.shields.io/github/stars/UFTHaq/Curling-Counter-and-Calories-Burned-Estimated?color=red&style=for-the-badge)

# Curling-Counter-and-Calories-Burned-Estimated
<p align="justify">App for exercise curling biceps that can help you to estimate the calories burned and track your exercise history.
  Using Python, OpenCV, MediaPipe, Tkinter, and Google Sheets API.
</p>

<p align="center">
  <img src="https://github.com/UFTHaq/Curling-Counter-and-Calories-Burned-Estimated/assets/104829519/cd40c0e9-50fa-4c36-bb84-2edf7950e8b5" height=400 />
</p>

<p align="center"><b>If you consider this page is useful, please leave a star</b></p>

## I. Introduction
<p align="justify"> Sports are structured activities aimed at enhancing physical performance and appearance, ranging from maintaining work 
  capacity to emergency readiness. Goals include strengthening muscles, cardiovascular health, blood circulation, respiratory efficiency, 
  and physical recovery after injuries. Weight training is a popular form of exercise among fitness enthusiasts.
</p>

<p align="justify"> Weight training is a systematic activity using resistance to boost muscle strength, appealing to those with limited 
  energy or suboptimal physical conditions. It serves various purposes, including improving physical condition and preventing injuries. 
  Clear goals are crucial in weight lifting exercises, evident in fitness centers offering diverse programs, from physical fitness to 
  weight loss, gain, body shaping, and hypertrophy.
</p>

<p align="justify"> However, a common challenge in weight training is the difficulty in calculating the number of burned calories. 
  Currently, this calculation is still done manually, making progress tracking complex. Additionally, it's challenging to determine the 
  number of calories burned in a single weightlifting movement. By knowing how many calories are burned in each movement, we can predict 
  the number of movements needed to achieve specific goals and the time required.
</p>

<p align="justify"> Therefore, we face difficulties in recording information about our sports activities, such as the number of exercise 
  repetitions and the calories burned. To address this, we want to create a program that can calculate repetitions, calories, exercise 
  duration, and record the date and time of the workout. This recording will facilitate tracking the intensity of the exercises and 
  provide valuable information to evaluate the effectiveness of your exercises.
</p>

## II. Method
<p align="center">
  <b>Flowchart</b>
</p>
<p align="center">
  <img src="https://raw.githubusercontent.com/UFTHaq/Personal-WEB-Image/main/Images/Flowchart%20-%20Curling%20Counter%20Small%20Fix-min.png" width="200" />
</p>
<p>
  <b>Tools used : </b>Python, OpenCV, MediaPipe, Tkinter, Nutritionix API, and Google Sheets API.
</p>

## III. Result
<p><b>Home Page</b></p>
<p align="center">
  <img src="https://github.com/UFTHaq/Curling-Counter-and-Calories-Burned-Estimated/assets/104829519/a7ac7196-4def-472f-8f7c-29a8abedd5cb" height=400 />
</p>

<p><b>Filling in personal data and choosing which hand to train will initiate the app.</b></p>
<p align="center">
  <img src="https://github.com/UFTHaq/Curling-Counter-and-Calories-Burned-Estimated/assets/104829519/a772b554-6163-4ff6-b1ad-4c1525a4286d" height=400 />
</p>

<p><b>The next display when the program is running, all starting from <code>0</code>.</b></p>
<p align="center">
  <img src="https://github.com/UFTHaq/Curling-Counter-and-Calories-Burned-Estimated/assets/104829519/7bfeef90-ab23-4525-a5ce-77f43fd9e383" height=400 />
</p>

<p align="justify">
  <b>The program runs by calculating <code>repetitions</code>, hand movement <code>positions/stages</code>, a <code>timer</code> for exercise duration, 
    the trained <code>hand</code>, and an estimate of burned <code>calories</code>.
  </b>
</p>
<p align="center">
  <img src="https://github.com/UFTHaq/Curling-Counter-and-Calories-Burned-Estimated/assets/104829519/0e2ba4f2-5215-4ffd-b8a1-f5deb784caf1" height=400 />
</p>

<p align="justify">
  <b>The data can be reset, starting everything from <code>0</code> again, and the data can be saved to a Google Sheets database to view exercise tracking results and facilitate evaluation of the workouts. 
  </b>
</p>
<p align="center">
  <img src="https://github.com/UFTHaq/Curling-Counter-and-Calories-Burned-Estimated/assets/104829519/5088d0d1-6947-46f2-9f93-b576e38e3345" height=380 />
</p>

## IV. Conclusion
<p align="justify"> It can be concluded that the system can operate as expected, where the system records the sports activities we do, with recorded data 
  including exercise repetitions and the number of calories burned. This allows us to calculate repetitions, calories, exercise duration, and record the 
  date and time of the workout. The recording will facilitate tracking the exercise portions and evaluating the workouts conducted.
</p>

## V. Evaluation
<p align="justify">
  From the project "Curling Counter and Calories Burned Estimated," the necessary evaluation for further development is the app's ability to predict the 
  weight used. Currently, the app struggles to distinguish between movements without weight and those with weight. The addition of AI that can estimate the 
  load value may make this project more realistic. Additionally, creating a standalone app without dependencies on Python libraries such as OpenCV and 
  MediaPipe would enable a wider range of users to utilize the app
</p>


<p align="center"><b>If you consider this page is useful, please leave a star</b></p>






