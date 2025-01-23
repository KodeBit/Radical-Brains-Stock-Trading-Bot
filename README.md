Radical Brains Inc. Stock Trading Platform


Description
This application is an easy to use stock trading software that automates the buying and selling of stocks - Amazon, Apple, Google, META, Microsoft, Tesla.  

## **Table of Contents**
1)  Tools
    Software used to create, install, and use application
    
2)  How To Install And Run
    Instructions for how to load the application on your device
    
3)  How It Works
    A description of what happens behind the UI
    
4) Credits
    Computer Science Analysts


## **Tools**
- Visual Studio Code
- Alpaca
-Py Installer(Current Version)
-Python

## **How To Install And Run**
- Download Visual Studio Code(if do not have it)
Create a standalone executable using py installer
-Make sure your physton script (RadicalBrainsv3.py) is working properly
-Go to command prompt to install python and Py installer with current version 
  -Navigate to the folder where your python script is located
    -cd C:\Users\screw\...\...
-Create an Executable
  - pyinstaller --onefile --windowed --icon=RB_Logo.icoRadicalBrainsv3.py
- Download the exc file that includes the installation script
- Double Click on RadicalBrainsv3.exe to launch the application 
-Run the program (Make sure not to move any files inside the folder as everything needs to stay in the same directory for the application to work. 
- Follow the links to the config folder 

- Go to https://app.alpaca.markets/account/login
  - Log in
  - click 'Home'
  - click 'Generate' or 'Regenerate' under API keys
  - copy Endpoint and Key
- Put your API key credentials from Alpaca into the config.py file


## **How It Works**
- Enter ‘user’ for username and ‘password’ for password 
-After signing into the welcome screen, you will be directed to the home page 
- Choose the appropriate option to match your decision.(choosing from trend, range, buy or sell).  
- The next screen called Results shows the user all of their stocks they may have purchased in the last or currently still have, total balance, and the price of stocks that were purchased.  
- The next screen called Stocks shows the option for users to purchase another stock or not
    - If the user chooses to purchase another stock, clicking 'Yes', they will be prompted to the  Welcome Screen, allowing them to restart the process
    - If the user chooses **NOT** to purchase another stock, clicking 'No', the program will automatically  quit
-If the user selects Trend or Range a table will pop up with a confirmation code that your stocks were  successfully purchased.

## **Credits**
Kristian Beckley,
Jamaine Barnes,
Amir Crutchfield,
Sydney Johnson, 
Lauren Mathis, and  
Jadon Sadler  
