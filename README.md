# PythonSolutions_4019534

This project is a combination of 3 parts, all with the goal of generating a strong password using a weak password inputted by the user.

In the PythonSolutions_4019534 folder, we have:
  • Part1 folder
  • Part2 folder
  • Part3 folder

# Part1 folder (Part 1)
This section of the project required a command line script to be developed that will generate a strong password using random.seed(input_password), where input_password is a input variable that will contain the user defined password. appendixA.py contains the script given in our assignment instructions (COS738 Cybersecurity Assignment - Blackledge 2023 V2.pdf) to provide the original code that was modified for this section. part1.py is the modified version of appendixA.py, replacing the length variable with an input variable (input_password) and initializing this variable into the function random.seed(input_variable). The user is prompted to enter a password. This password is then assigned to the generate_password(input_password) function and seeded into the random.seed() function to initialize a random number generator. After which, a for loop iterates over the length of input_password and adds a character to the strongpassword variable using the random.choice() function which will select a random character from characters (a string holding all possible characters to make the strong password). This solution to this part is provided as a part1.py file and as a command line script (included in the dist folder) using the PyInstasller package as was required. After executing the script on the command line, the script asks the user to enter a password (weak) and then returns an accompanying strong password and informs user the password is saved in the strongpasswordPart1.txt file and also displays the file's path. 

# Part2 folder (Part 2)
We are required to convert our command line script for Part 1 into a Python app. As such we have modified our part1.py file to take in a string from another file and named this script part2generator.py. Another script was developed that will display a simple GUI of our strong password generator as a Python app (part2app.py). This app will have an entry field where the user can type their password (weak), and a button ("Generate Password"). After the button is clicked, a section will appear below the button containing the new password (strong) and it will inform the user that the password is saved in the strongpasswordPart2.txt file and where the file is stored (path). An exit button ("Exit") is also present that will close the app when clicked. Included in this folder is a dist folder containing a command line script for the Python app. 

# Part3 folder (Part 3)
This section required the use of the TuringBot approach. After downloading the software, we produced a stream of numbers in [0,1] on random.org, and seeded the data into the TuringBot system to develop a unique nonlinear formula (turingBot(x)) that we will use to create a function to randomly generate a strong password using the input_password value given by the user. This TuringBot approach replaces the random.seed(input_password) function used in Part 1 and Part 2. This script will send the newly generated strong password to part3app.py script which will display the password, and display the .txt file name it is saved in (strongpasswordPart3.txt) as well as where the file is stored (its path). part3app.py creates a simple GUI as was the case with part2pp.py in Part 2 that includes an entry field for the user to type their password (weak) and a button ("Generate Password"). As was the case in Part 2, after the button is clicked, a section appears below it that displays information about the new password (strong). An exit button ("Exit") is also present that will close the app when clicked. Included in this folder is a dist folder containing a command line script for the Python app.

All these scripts are included in the folders specific to sections of thev project that require them and all 3 folders are contained in the PythonSolution_4019534 folder that is uploaded to iKamva as PythonSolution_4019534 .zip 

# Student name: Fatima Gamieldien
# Student number: 4019534
  
