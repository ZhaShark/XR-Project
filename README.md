# XR Project Proposal: Chinese Character to Element – An Interactive XR Experience
## 1. Project Overview
The aim of this project is to develop a small VR magic puzzle game using Godot 4.7.2 and Meta Quest 3S.
Players will use hand tracking to write Chinese characters in the air with their fingers. When a character is recognised, the game will generate a corresponding magical ability.
Players must use these magical abilities to solve puzzles, interact with objects and find a way to complete each room.
The game will be based on five Chinese characters related to the Five Elements: 金 (Metal), 木 (Wood), 水 (Water), 火 (Fire) and 土 (Earth).
##### project member：Qiu Xie, Junhao Chen, 
## 2. Project Objectives
The main objectives are:
Implement hand tracking using Meta Quest 3S.
Allow players to draw simple Chinese characters in the air.
Display the finger movements as visible 3D strokes.
Recognise five selected Chinese characters using predefined templates.
Generate different magical effects based on the recognised characters.
Create a small VR puzzle game with interactive rooms.
## 3. Game Design
The game will contain five small puzzle areas. Each area will introduce a different magical ability.
金 (Metal): Write 金 to create a golden key. The player must find the correct lock and open the door.
木 (Wood): Write 木 to make a plant grow. The player can use the plant to reach a higher platform or reveal a hidden path.
水 (Water): Write 水 to create water. The player must direct the water towards a mechanism to activate it.
火 (Fire): Write 火 to create a fireball. The player must use it to light torches or remove an obstacle.
土 (Earth): Write 土 to raise a stone platform. The player must use it to reach an otherwise inaccessible area.
Each puzzle will require the player to understand the environment and choose the correct magical ability.
## 4. Technical Implementation
### 4.1 Hand Tracking and 3D Drawing
Use Meta Quest 3S hand tracking to detect the player's hand movements.
The player will use their index finger to draw characters in the air. The system will record the finger positions and display them as 3D strokes.
### 4.2 Character Recognition
Implement a simple recognition system using predefined templates for the five selected characters.
The system will compare the player's drawing with the templates and identify the closest matching character.
### 4.3 Magic System
Each recognised character will activate a corresponding magical effect.
The effects will be created using Godot's 3D objects, animations and particle effects.
### 4.4 Puzzle Interaction
Create small interactive environments where players must use magic to solve puzzles.
The game will include basic object interactions, triggers, collision detection and puzzle completion conditions.
## 5. Project Challenges
The main challenges of this project include:
Implementing hand tracking in a VR environment.
Recording and displaying 3D finger movements.
Recognising the five selected Chinese characters.
Connecting character recognition with magical effects.
Designing puzzles that require players to use the correct magic.
## 6. Development Plan
Set up Godot, OpenXR and Meta Quest 3S hand tracking.
Implement 3D drawing using finger movements.
Implement basic recognition for the five Chinese characters.
Create the five magical effects.
Build the puzzle areas and connect them to the magic system.
Test the complete game on Meta Quest 3S.
## 7. Expected Outcome
The final outcome will be a small playable VR magic puzzle game.
Players will be able to write Chinese characters in the air using hand tracking, generate different magical abilities and use them to solve puzzles.
The project will demonstrate the use of hand tracking, 3D drawing and basic character recognition in an interactive VR game.
