# creating-your-own-cli-lab-rock-paper-scissor

In this lab, you will build a Command-Line Interface (CLI) game for Rock-Paper-Scissors using Node.js. This project will help you practice foundational CLI concepts—commands, syntax, project structure, and interactive menus—while building a simple application that runs in the terminal.

You will:

Create a CLI game with a user-friendly menu system.
Implement game logic for Rock-Paper-Scissors.
Track and display statistics for wins, losses, and ties.
Practice building a project with modular files and clear organization.
By the end of this lab, you should be able to organize a CLI project, use terminal-based npm packages, and build a small interactive application that runs from the command line.

Scenario
As a new developer, you’ve been tasked with creating an interactive Rock-Paper-Scissors game. The CLI tool should:

Provide a menu to:
Start a game.
View game statistics.
Reset statistics.
Quit the application.
Allow users to play against the computer, which will randomly choose its move.
Display the result of each round (win, loss, or tie) and update the statistics.
Provide a summary of wins, losses, and ties in the statistics menu.
This lab will help you understand how to design user-focused CLI tools, which is an essential skill for building interactive applications and automation scripts.

Tools and Resources
Code Editor: Visual Studio Code (or another code editor)
Node.js: For running JavaScript in the terminal
Terminal: For running commands and testing the CLI
Dependencies:
commander: A common CLI library for command parsing and structure.
@inquirer/prompts: For interactive menu choices and user input in the terminal.
chalk: For color-coded terminal output.