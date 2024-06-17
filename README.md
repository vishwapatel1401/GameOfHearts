Hearts Card Game
A multiplayer Hearts card game developed in C# with a MySQL backend for score tracking and storage. The game supports 4 players and includes features such as scoreboards, heart-breaking notifications, and persistent score storage in a database.

Table of Contents
•	Introduction
•	Features
•	Installation
•	Usage

Introduction
The Hearts Card Game is a digital version of the popular card game Hearts. It allows 4 players to play the game simultaneously, keeping track of scores automatically and storing them in a MySQL database. The game provides visual indications for important events, such as when hearts are broken.

Features
•	Multiplayer Support: Play with up to 4 players.
•	Scoreboard: Automatically displays scores at the end of each round.
•	Hearts Broken Notification: Visual indicator when hearts are broken.
•	Persistent Storage: Scores are stored in a MySQL database for future access.
•	User-friendly Interface: Intuitive and easy-to-use interface.

Installation
Prerequisites
•	.NET Framework or .NET Core
•	MySQL Server
•	MySQL Connector for .NET

Steps
1.	Clone the repository:
bash
Copy code
git clone https://github.com/yourusername/hearts-card-game.git
2.	Navigate to the project directory:
bash
Copy code
cd hearts-card-game
3.	Set up the database:
o	Create a MySQL database named hearts_game.
o	Run the SQL scripts in the database folder to create necessary tables.
4.	Update connection strings:
o	Update the MySQL connection strings in the project configuration file with your database credentials.
5.	Build and run the project:
o	Open the project in your preferred IDE (e.g., Visual Studio).
o	Build the solution and run the application.

Usage
1.	Launch the application.
2.	Start a new game and invite 3 other players to join.
3.	Play the game following the standard rules of Hearts.
4.	Scores will be automatically updated and displayed on the scoreboard at the end of each round.
5.	Access historical scores from the database as needed.





