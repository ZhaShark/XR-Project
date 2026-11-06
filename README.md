# XR Project Proposal: Chinese Character to Element – An Interactive XR Experience
## 1. Project Overview
Our project is to make a small VR puzzle game using Godot 4.7.2 and Meta Quest 3S.
Players will use hand tracking to write Chinese characters in the air with their fingers. When a character is recognised, the game will spawn an ability effect according to the character.
Players must use these magical abilities to solve puzzles, interact with objects and find a way to complete each levels.
The game will be based on five Chinese characters related to the Five Elements: 金 (Metal), 木 (Wood), 水 (Water), 火 (Fire) and 土 (Earth).
#### project member：Qiu Xie, Jun Hao Chin, Ronan Canales
## 2. Project Objectives
We aim to:
- Add hand tracking using Meta Quest 3S.
- Allow players to draw simple Chinese characters in the air.
- Display the finger movements as visible 3D strokes.
- Recognise five selected Chinese characters using predefined templates.
- Spawn different magical effects based on the recognised characters.
- Create a small VR puzzle game with interactive level.
## 3. Game Design
The game will have five small puzzle levels. Each area will introduce a different magical ability.
金 (Metal): Write 金 to create a golden key. The player must find the correct lock and open the door.
木 (Wood): Write 木 to make a plant grow. The player can use the plant to reach a higher platform or reveal a hidden path.
水 (Water): Write 水 to create water. The player must direct the water towards a mechanism to activate it.
火 (Fire): Write 火 to create a fireball. The player must use it to light torches or remove an obstacle.
土 (Earth): Write 土 to raise a stone platform. Allows player to use it to reach an inaccessible area.
Each puzzle will require the player to understand the environment and choose the correct ability.
## 4. Technical Implementation
### 1. Hand Tracking and 3D Drawing
Use Meta Quest 3S hand tracking to detect the player's hand movements. Players will use their index finger to draw Chinese characters in the air. The game will show their finger movements as 3D strokes.
### 2. Character Recognition
Create a simple system to recognise the five Chinese characters. The game will compare the player's drawings with examples saved in the game to find the closest match.
### 3. Magic System
Each recognised character will create a different magical ability. We plan to use 3D objects, animations and particle effects to create the magic.
### 4. Puzzle Interaction
Create small puzzle areas where players can use their magical abilities to interact with objects and solve puzzles.
## 5. Project Challenges

Some challenges we might face include:
- Getting hand tracking to work properly in VR.
- Showing finger movements as 3D strokes.
- Recognising the five Chinese characters correctly.
- Connecting the recognised characters to correct abilities.
- Creating puzzles that work with each ability.
## 6. Development Plan
- Set up Godot, OpenXR and Meta Quest 3S hand tracking.
- Create the 3D drawing system.
- Make the character recognition system.
- Create the five magical abilities.
- Build the puzzle areas.
- Test the game on Meta Quest 3S.
## 7. Expected Outcome
We hope to create a small playable VR magic puzzle game. Players will be able to draw Chinese characters in the air using hand tracking and use the magic they create to solve puzzles.
The project will allow us to explore hand tracking, 3D drawing and character recognition in VR.
We hope that player will learn some Chinese words through their game experience. The player will learn from writing simple Chinese characters and understand what it means.
