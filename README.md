
League of Legends Lane Assistant
Overview
The League of Legends Lane Assistant is a desktop application built using Python's Tkinter library. It assists players in selecting their roles and champions in the game "League of Legends." The application features a user-friendly interface that allows users to navigate through roles and champion selections easily.

Features
Role Selection: Users can choose from five roles: Support, ADC (Attack Damage Carry), Mid, Jungle, and Top.

Champion Selection: Based on the selected role, users can pick from a list of champions categorized into Tanks, Mages, Enchanters, Assassins, and Ranged.

User-Friendly Interface: The application features a visually appealing layout with icons and background images to enhance user experience.

Exit Functionality: Users can exit the application easily with a dedicated button.

Installation
To run this application, ensure you have Python installed on your machine. You will also need the Pillow library for image handling.

Clone the repository:
bash

git clone https://github.com/yourusername/league-lane-assistant.git
cd league-lane-assistant

Install required packages:
bash
pip install Pillow

Run the application:
bash
python main.py

Functionality
The application consists of several functions, each serving a specific purpose. Below is a breakdown of the main functions included in the code:

1. Role()
Purpose: Opens a new window for role selection.
Functionality: Displays buttons for each role (Support, ADC, Mid, Jungle, Top). When a user clicks on a role button, it calls the supp_Champ(role) function with the selected role as an argument.

2. supp_Champ(role)
Purpose: Opens a new window for champion selection based on the selected role.
Parameters: role - A string representing the selected role.
Functionality: Displays a list of champions categorized by their types (Tanks, Mages, Enchanters, Assassins, Ranged). It also allows users to select a champion from the respective dropdown menu.

3. show_champion()
Purpose: Displays the selected champion in the champion selection window.
Functionality: When the "Choose" button is clicked, this function retrieves the currently selected champion from the dropdown and displays it on the screen.

Code Structure
The main code structure consists of the following key components:

Imports: Necessary libraries are imported at the beginning, including tkinter for GUI and PIL for image handling.
Main Window: The main application window is initialized, including title, icon, and dimensions.
Role Icons and Background: Icons for each role are loaded, and a background image is set for the main window.
Buttons and Labels: Buttons for settings, exit, and starting the role selection process are created and placed in the main window.
Main Loop: The application enters the main event loop with root.mainloop().
Usage
Launch the application.
Click the "Start" button to open the role selection window.
Select a role by clicking on the corresponding icon.
Choose a champion from the dropdown menus in the champion selection window.
Click the "Choose" button to display the selected champion.
License
None

Acknowledgments
Thank you to the League of Legends community for inspiration and guidance.
Special thanks to the developers of Tkinter and Pillow for their contributions to Python GUI development.
