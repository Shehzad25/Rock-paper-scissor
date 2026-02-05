🪨📄✂️ Rock Paper Scissors Game (Python GUI)

A Rock–Paper–Scissors game built using Python and Tkinter, where a user plays against the computer. The game features a graphical interface, random computer moves, and visual feedback using images stored in organized folders.

🎮 Features

GUI built with Tkinter

Random computer selection

Real-time image updates

Win / Lose / Draw logic

Clean and beginner-friendly project structure

🛠️ Tech Stack

Python

Tkinter

Random module

📁 Project Structure
Rock-Paper-Scissors/
│
├── main.py / test.py
│
├── images/
│   ├── rock.png
│   ├── paper.png
│   ├── scissors.png
│   ├── default.png
│   ├── vs.png
│   └── you_win.png
│
└── README.md

▶️ How to Run the Project

Clone the repository

git clone https://github.com/Shehzad25/rock-paper-scissors.git


Go to the project folder

cd rock-paper-scissors


Run the game

python main.py


⚠️ Make sure the images/ folder is in the same directory as main.py.

🧠 Game Rules
Computer	Player	Result
Rock	Rock	Draw
Paper	Paper	Draw
Scissors	Scissors	Draw
Rock	Paper	Player Wins
Paper	Scissors	Player Wins
Scissors	Rock	Player Wins
Paper	Rock	Computer Wins
Rock	Scissors	Computer Wins
Scissors	Paper	Computer Wins
🖼️ Image Handling

All game images are loaded from the images/ folder:

PhotoImage(file="images/rock.png")
PhotoImage(file="images/paper.png")
PhotoImage(file="images/scissors.png")


This keeps assets organized and makes the project easier to maintain.

🚀 Future Enhancements

Scoreboard system

Reset / replay button

Sound effects

Dark mode UI

Executable version using PyInstaller

👨‍💻 Author

Shehzad Khan
Python Developer | Data Science Enthusiast

🔎 Small but important tip (code improvement)

Instead of hardcoding paths everywhere, you can do this:

IMG_PATH = "images/"

PhotoImage(file=f"{IMG_PATH}rock.png")


Cleaner and safer ✔️
