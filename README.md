# -Carbon---Android-
How to set up and run the mobile automation using Katalon Studio

Step 1 : Check if Node.js is already installed node -v node –version npm -v npm –version

Step 2: Download and install Node.js https://nodejs.org/en/download/ check node.js is installed by running the above commands node -v npm -v where node

Step 3: Install APPIUM check Java is installed on your system java -version npm install -g appium npm install -g appium@1.8.2 Check if appium is installed appium –version appium -v where appium

Step 4: Open Katalon Studio and connect to Appium

Step 5: Setup android mobile device for automation
--5(i). Settings – About Phone – tap 7 times on Build number
--5(ii). Settings – Developer Options – enable USB Debugging

Step 6: Connect android device to your system (usb cable)

Step 7: open the project by doing the following below:
----Select File > Open Project from the menu. 
----Browse to the folder where your project is located and select it

Step 8: Open the test case created called "Transaction Made" under the TEST CASES explorer folder "Airtime Recharge" and run each of the test cases

Step 9: Open the Test Suite titled "Home Challenge Regression" and Run to validate the added scripts

Please note: When the app automates to confirm airtime recharge transaction at step 17, kindly supply the PIN
Due to the nature of the response screens you might experience some steps not fully executed especially the confirmation dialog which led to disabling some steps but it can fixed with time.

Thank You
