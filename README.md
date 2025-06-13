# task-1-cpp-file-management-project
COMPANY : CODETECH IT SOLUTION PVT.LTD
NAME : SOUMITA SAHA 
INTERN ID : CTO4DN493
DOMAIN C++ PROGRAMMING 
DURATION 4 WEEKS
MENTOR :NEELA SANTOSH 

>>C++ File Management System – Internship Project

This project is a console-based File Management Tool developed in C++ as part of my internship task. It allows users to read from, write to (overwrite), and append to a text file through a simple menu-driven interface.

💻 Core Features:

1. Write to File (Overwrite):

Prompts the user to enter data.

Overwrites any existing content in the file.

Uses ofstream to write data securely.



2. Read from File:

Reads the entire file line-by-line using ifstream.

Displays the content on the console.

Includes error-handling in case the file doesn’t exist or cannot be accessed.



3. Append to File:

Takes user input and adds it to the end of the file without erasing existing content.

Uses the ios::app flag with ofstream for appending data.



4. User-Friendly Interface:

A while loop with a switch-case structure provides a clean and repetitive menu for user interaction.

The user can exit the program anytime by selecting option 4.




⚙️ Technical Highlights:

Utilizes standard file handling libraries like <fstream>.

Implements basic exception handling using if (!file) checks.

Handles newline input conflicts with cin.ignore() to ensure smooth input operations after numerical choices.


📁 Target File:

All operations are performed on a fixed file named sampleFile.txt. This file is automatically created if it does not exist, and reused for all read/write/append operations.


This project demonstrates my understanding of file I/O operations in C++, user input management, and basic program structuring using functions and control flow. It showcases the foundational skills necessary for building practical applications involving persistent data storage.

>>OUTPUT:
![Image](https://github.com/user-attachments/assets/10c63cb9-0c7e-4f33-9821-5718b6d0eb82)










