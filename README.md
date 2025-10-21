Java Swing GUI Calculator

This project is a fully functional, standalone desktop calculator application built with Java Swing. It provides a clean, modern user interface for performing basic arithmetic operations like addition, subtraction, multiplication, and division. The project is managed and built using Apache Maven, which handles the entire build process to create a single, executable JAR file.

✨ Features

Standard Calculator Layout: A familiar and intuitive interface with a digital display and a grid of number and operator buttons.

Core Arithmetic Operations: Supports Addition (+), Subtraction (-), Multiplication (*), and Division (/).

Decimal Point Support: Allows for calculations with floating-point numbers.

Clear Functionality: A 'C' button to reset the current calculation and clear the display.

Error Handling: Prevents division by zero and shows a user-friendly error message.

Chain Operations: Supports continuous calculations (e.g., 5 * 5 + 2 = 27).

🛠️ Tech Stack

Language: Java

UI Framework: Java Swing

Build Tool: Apache Maven

📋 Prerequisites

To build and run this application from the source, you must have the following software installed on your system.

1. Java Development Kit (JDK)

Requirement: JDK, version 8 or higher.

How to check: Open a terminal and type java -version.

Download: Oracle Java website.

2. Apache Maven

Requirement: Maven is used to build the project and create the executable JAR.

How to check: Open a terminal and type mvn -version.

Download: Follow the installation guide on the official Maven website.

🏗️ How to Build and Run from Source

With Maven, building and running the project is a simple, two-step process.

Clone the repository:

git clone [https://github.com/your-username/your-repo.git](https://github.com/your-username/your-repo.git)
cd your-repo


Build the Project with Maven:
Open a terminal in the project's root directory (where the pom.xml file is located) and run the following command:

mvn clean package


Maven will compile the source code and package it into a single, executable JAR file in a new target directory. This JAR file includes all necessary components to run.

Run the Application:
Navigate to the target directory and run the application using the java -jar command. The filename may vary slightly depending on the version in your pom.xml.

cd target
java -jar SwingCalculator-1.0-jar-with-dependencies.jar
"# GUICalculator" 
