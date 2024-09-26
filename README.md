
# 🚀 BaghChal AI
## What is the project about?
This project is an interactive implementation of BaghChal, a traditional Nepali board game, where players can compete against an AI opponent or play in multiplayer mode. The AI is powered by the Min-Max algorithm. The game was developed using C++ and the Simple and Fast Multimedia Library (SFML), and Audacity was used to enhance the sound effects for a more immersive experience.



## Features

- **Single-player mode:** Play against an AI opponent, which uses the Min-Max algorithm to strategize and make decisions.
- **Multiplayer mode:** Players can compete against each other, with one controlling the tigers and the other controlling the goats.
- **Interactive UI:** The game interface is visually interactive and built using SFML.
- **Game Mechanics:** Players control either the tigers or goats, with AI or the second player handling the opposing side.
- **Strategic AI:** The AI uses the Min-Max algorithm to evaluate moves and compete at a challenging level.
- **Sound Effects:** The sound effects were enhanced using Audacity, making the game experience more immersive.
- **Traditional Rules:** The game adheres to the classic rules of BaghChal, offering an authentic experience.




## Installation

#### **Method 1: Quick Start with Precompiled Version**
1. Go to the Releases section of this repository.
2. Download the latest version: Bagchal.
3. Open the downloaded file Bagchalv2.2.exe.
4. Enjoy the game instantly—no setup required!

#### **Method 2: Build from Source**

- **Install SFML 2.5.1**
  - ***Windows:*** Download the SFML 2.5.1 installer for Windows and follow the instructions.
  - ***MacOS:*** Install SFML using Homebrew:
    ```
    brew install sfml 
    ```

  - ***Linux:*** Install SFML using the terminal:
    ```
    sudo apt-get install libsfml-dev
    ```
- **Clone the Repository**
Download the source code by cloning this repository:
```
git clone https://github.com/Nischal-Karki-1/BaghChal-AI.git
```
- **Open the Project in VS Code**
    1. Navigate to the folder where you downloaded the repository.
    2. Open ```Bagchalv2.2``` in VS Code.
    3. Open the file ```Main.cpp```.

- **Build and Run the Game**
    1. Ensure your SFML paths are correctly set up in VS Code.
    2. Press ```Ctrl+Shift+B```, click ```Run and Debug``` to execute the project.
- **Enjoy the Game!**
## Min-Max Algorithm
- **Implementaion of Min-Max Algorithm**
<div align="center">
 <img width="529" alt="image" src="https://github.com/user-attachments/assets/64b0a16b-9d32-4869-a352-86a679b07529">
</div>

 #### **Working**
- Prepare the complete Game Tree.
- Evaluate the score of each branch, using the evaluation function.
- Back-up score from the nodes to the root by:
    - Selecting the child node with a maximum score for Max player.
    - Selecting the child node with the minimum score for Min player.
- It is based on these values/scores that the quality (good or bad) of the move is decided.
-  At the root node, the node with the max value is selected and the corresponding move is performed.
-  
## Screenshots
- #### Home Page
<div align="center">
 <img width="500" alt="Screenshot 2024-09-26 165030" src="https://github.com/user-attachments/assets/a06c1c1a-ed49-4f3e-8922-89d48d426394">

</div>
<br>

- #### Game Page
<div align="center">
<img width="500" alt="Screenshot 2024-09-26 165103" src="https://github.com/user-attachments/assets/1f4a2414-ee5a-4d0b-b7c9-438b41d0ea55">

</div>
<br>

- #### Goat Placement
<div align="center">
  <img width="500" alt="Screenshot 2024-09-26 165143" src="https://github.com/user-attachments/assets/6e922bc4-fc83-4839-8c19-6e4c38471fba">

</div>
<br>

- #### Tiger Selection
- <div align="center">
    <img width="500" alt="Screenshot 2024-09-26 165218" src="https://github.com/user-attachments/assets/a8bbf5c9-1c28-444e-88b3-4a12398fc2bf">
</div>
<br>

- #### Goat Defeating Move (Before)
<div align="center">
  <img width="500" alt="Screenshot 2024-09-26 165241" src="https://github.com/user-attachments/assets/e34f70bd-75b1-4fee-8aa9-1751290d5c0b">
</div>
<br>

- #### Goat Defeating Move (After)
<div align="center">
 <img width="500" alt="Screenshot 2024-09-26 165304" src="https://github.com/user-attachments/assets/37024d6e-aeed-4543-a4a4-e6f91440df7b">

</div>
<br>

- #### Tiger Victorious
<div align="center">
  <img width="500" alt="Screenshot 2024-09-26 165327" src="https://github.com/user-attachments/assets/2ee1393e-2872-4471-af08-e9bf34d56667">

</div>
<br>

- #### Goat Victorious
<div align="center">
  <img width="500" alt="Screenshot 2024-09-26 165351" src="https://github.com/user-attachments/assets/f1a06293-8b2c-4699-8c85-f168ac53c4a1">

</div>
