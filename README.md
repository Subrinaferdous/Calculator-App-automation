# Project Title : Mobile App Automation (Calculator) 

## Project Summary : In this repository, I have automated the Google LLC Calculator Android App and generated an allure report for the test suite results.

## Work Scenerio
Automate two series for calculator app. Pass the series as a parameter to your test method. For an example:
100/10*5-10+60 and 
50+10-20*2+10/2
pseudocode for test function can be look like:

public void doSeries(){ calcuateSeries("100/10*5-10+60");}

## Prerequisites: 
1. install intellij
2. Dependencies implementation on Selenium, TestNg , Java

## Tools Used
1. Selenium
2. TestNG Framework
3. Appium
4. Allure Report
   1. ``` Project run (gradle clean test) For generating Allure Report  ```
   2. ``` allure generate allure-results --clean -o allure-report ```
   3. ``` allure serve allure-results ```

## output: For a better understanding of the project,Allure Report is given below.
![Screenshot 2024-09-15 010621](https://github.com/user-attachments/assets/452edc2a-19b5-4601-a4dc-1f0da3cbf05d)

 ## Allure Behaviour:
![Screenshot 2024-09-15 010703](https://github.com/user-attachments/assets/ae508fce-418f-4f84-8a97-c4bd30913dc8)

## output: For a better understanding of the project, video record is given below.
https://github.com/user-attachments/assets/bb58ea2d-9870-432f-937b-850e74463dfd


