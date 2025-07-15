# Snake & Ladder Game Project

### NED 1st Semester Project  
A **Snake & Ladder Game** developed using **C language** and **Raylib** for graphical rendering. This project showcases a classic board game with interactive animations, player updates, and special events like encountering snakes or climbing ladders.

---

## Members / Contributors
- **Syed Muhammad Hunain**
- **Sarim Khan**
- **Muhammad Maaz Ali**
- **Muhammad Umer Pervez**

---

## Project Highlights
This project is structured into multiple files, each handling specific functionalities to ensure modularity and efficiency:

1. **MAIN.c**  
   - The main entry point for the Snake & Ladder game.
   - Manages the game loop, screen transitions, and resource loading/unloading using Raylib.

2. **Screens.h**  
   - Implements the game's various screens, including the title screen, player selection, name input, gameplay, and end screens.

3. **Snake_Ladder.h**  
   - Contains the logic for checking snakes or ladders on the board.
   - Updates the player's position and displays messages for landing on a snake or climbing a ladder.

4. **Resources.h**  
   - Handles resource management, including loading fonts, textures (dice faces, backgrounds, and logo), and ensuring proper cleanup to manage memory efficiently.

5. **Info.h**  
   - Defines global constants, enumerations, and variables for managing the game's state, including screen transitions, player information, game messages, and winner tracking.

6. **Dice.h**  
   - Implements dice rolling mechanics, including animations, player updates, and special events like encountering snakes or ladders.

---

## How to Run the Game
To run the Snake & Ladder game, follow these steps:

1. **Prepare the Folder Structure**  
   - Create a folder and paste all the required files into it.  
   - Ensure the folder contains the following files:
     - `Dice.h`
     - `Info.h`
     - `MAIN.c`
     - `Players.h`
     - `Resources.h`
     - `Screens.h`
     - `Snake_Ladder.h`
     - A `Resources` folder.

2. **Resources Folder**  
   - Inside the `Resources` folder, include the following:
     - **Images**:  
       - Six dice images (one for each face).  
       - A board image.  
       - A main background image.  
       - A logo image (in `.png` format).  
     - **Fonts**:  
       - A `Fonts` folder containing the `myfont.ttf` file.

3. **Run the Game**  
   - Open the terminal and navigate to the folder containing `MAIN.c`.  
   - Compile and run the game using the following command:  
     ```bash
     ./MAIN.exe
     ```
   - The game will launch automatically. Enjoy!

---

## Screenshots of the Game
Below are some screenshots showcasing different stages of the Snake & Ladder game:

### Title Screen
![Title Screen](Game%20Screenshots/Title.png)

### Choosing Players
![Choosing Players](Game%20Screenshots/Choosing%20Players.png)

### Enter Name Screen
![Enter Name Screen](Game%20Screenshots/Enter%20Name.png)

### Main Background
![Main Background](Game%20Screenshots/Main%20Background.png)

---

## Features
- Interactive gameplay with animations.
- Dynamic player updates based on dice rolls.
- Special events for encountering snakes or climbing ladders.
- User-friendly interface with graphical elements powered by Raylib.
- Modular code structure for easy maintenance and scalability.

---

## Acknowledgments
This project was developed as part of the **NED 1st Semester Project**. Special thanks to the contributors for their dedication and teamwork.

---
