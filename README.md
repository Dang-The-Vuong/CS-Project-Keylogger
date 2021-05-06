# CS-Project-1(Key-logger)

## Description
    A program that monitor victim keystroke in the computer and store it in a file. The program then sent the file it to the attacker.
## Authors

    By Vuong Dang

## Getting Started

   ### Dependencies
       - Require Python3.
            - Require two libaries: pynput and smtplib
       - Work one Window, Mac and Linux.
            - You have to run it as root in Mac because of security reason.
       - In order to work, the attacker must have an gmail account and enable lesssecureapps login https://www.google.com/settings/security/lesssecureapps
       - The attacker need to give the application Gmail login credential in order for the program to work!
       - The program can sent message to any email(Yahoo, Yandex, Gmail, etc...)
   ### Installing
       - Git(Git application need to be install):
            - Command: git clone https://github.com/dangvuonglcps/CS-Project-1.git
       - Download the file from source.
   ### Executing program
       - Make sure to have the dependencies ready.
       - Make sure to be in the same folders or directory to the program.
       - To run the program, enter the command "python3 main.py"

## Output
       - The program should print out the log keys and also sent a text file of the log key to an attacker.

## Note
       - The progam demo was initually design to work with ProtonMail but it require dependencies like the ProtonMail Bridge application which is not convenient and not realistic.
