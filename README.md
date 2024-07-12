# Snake-Game-OOPs 🐍
Welcome to the classic Snake game, brought back to life in the Windows console! This project not only lets you relive the nostalgia but also serves as a great learning experience for Object-Oriented Programming (OOP) concepts in C++.

<img src="https://github.com/user-attachments/assets/e88f96f1-0f0c-437b-9c9f-97568ee8e06b" width="500px" height="275px">
<img src="https://github.com/user-attachments/assets/beb4865e-3f17-40e1-bbae-32f1b286c5c8" width="500px" height="275px">

## 🚀 Getting Started

### Prerequisites

Before you dive into the snake world, make sure you have:
- **Windows OS** (Sorry, Linux and macOS friends, this one’s Windows-specific!)
- A **C++ compiler** (MinGW is a great choice for Windows)
- A command line or terminal

### Installation
Clone the repository or simply download the source code.<br>
--> git clone https://github.com/JuhiPathak23/Snake-Game-OOPs.git<br>
Navigate to the project directory.<br>
--> cd snake-game-oops<br>
Compile the code with your C++ compiler.<br>
--> g++ -o snakegamemain.cpp -lwinmm<br>
Run the game and enjoy!<br>
## 🎮 How to Play
Use the W, A, S, D keys to slither around.
W: Move Up
A: Move Left
S: Move Down
D: Move Right
Gobble up the food (o) to grow your snake and increase your score.
Avoid bumping into your own body—self-biting is a game over!

## 📚 Learning OOP Concepts
This project was a slithery fun way to dive into the core principles of Object-Oriented Programming:

### Encapsulation
Classes and Data Members: The Snake and Board classes neatly bundle data and methods. The snake's body and direction are kept snugly within the Snake class, and the game board's state is managed by the Board class.
Access Control: Data is protected inside classes, exposing only what’s necessary through methods. This prevents any unintended meddling with the snake’s innards!
Abstraction
Simplified Interfaces: Interacting with the snake and the board is a breeze thanks to methods like changeDirection(), move(), spawnFood(), and update(). These methods hide the gritty details of snake movement and food spawning.
### Inheritance and Polymorphism
Next Steps: While this implementation doesn’t yet include inheritance or polymorphism, it lays a strong foundation. Imagine a future where you might have a GameObject class with Snake and Food as subclasses—polymorphism would let us handle different game objects seamlessly!

### 🛠️ Code Structure
main.cpp: This is where all the magic happens. It contains the game logic and showcases how encapsulation and abstraction come together to create a fun game.
Key Classes and Functions
Point: Represents coordinates on the screen.
Snake: Manages the snake's position, length, and movement.
Board: Manages the game board, including the snake, food, and score.

### 📈 Scoring and Fun
Keep an eye on your score displayed at the top of the console.
Challenge your friends and see who can grow the longest snake!

## 📝 License
This project is licensed under the MIT License - see the LICENSE file for details.

## 🙏 Acknowledgments
Inspired by the timeless Snake game enjoyed across various platforms.
Thanks to all the open-source contributors who make game development accessible and fun.
## ✉️ Contact
Got questions or feedback? I’d love to hear from you!

Email: pathakkakul@gmail.com<br>
GitHub: JuhiPathak23<br>
Happy slithering!
