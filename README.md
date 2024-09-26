
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
## Screenshots
<div align="center">
  <img  alt="Screenshot 1" 
       src="https://github.com/user-attachments/assets/d022f6cc-750a-4215-a775-eb616e8525f8">
</div>
<br><br>

<div align="center">
  <img  alt="Screenshot 2" 
       src="https://github.com/user-attachments/assets/75f199db-06f1-4dbd-83f1-e32cb6dafaef">
</div>
<br><br>

<div align="center">
  <img  alt="Screenshot 3" 
       src="https://github.com/user-attachments/assets/c8f915fd-48dd-494c-86aa-6bfa47fba24e">
</div>
<br><br>

<div align="center">
  <img alt="Screenshot 4" 
       src="https://github.com/user-attachments/assets/2088cd18-0ef-44aa-8bda-e1631905cdc3">
</div>
<br><br>

<div align="center">
  <img  alt="Screenshot 5" 
       src="https://github.com/user-attachments/assets/2b50dcb8-f1ef-4fcd-a087-cb735c384f8c">
</div>
<br><br>

<div align="center">
  <img  alt="Screenshot 6" 
       src="https://github.com/user-attachments/assets/81c0eedd-cc4f-4725-8844-22d4d7f4fb70">
</div>
<br><br>

<div align="center">
  <img alt="Screenshot 7" 
       src="https://github.com/user-attachments/assets/4340ed44-9319-4ec2-a4c3-3180fb69052c">
</div>
<br><br>

<div align="center">
  <img alt="Screenshot 8" 
       src="https://github.com/user-attachments/assets/72592617-74f1-46e2-951a-dda9ac7172d3">
</div>
