# Scrum_Evaluation_Tool
This project creates a web application called Taigit which is used as a Scrum Evaluation Tool. It has an User Interface which uses the API endpoints provided by Taiga and GitHub to fetch relevant information regarding the user's Scrum process. Based on this information, it analyzes the process according to certain metrics and generates a comprehensive result which is portaryed in the form of charts, graphs etc. The front end uses React/Redux while the backend uses Typescript.

The tool has 3 parts:

 * Basic Scrum Data
   * Sprint dates
   * Team members
   * Creating their Taiga board and GitHub repo (automatically)
   * Visualization of data (GUI)
 * GitHub Evaluation
   * Frequency of commits
   * Good commit messages, good comments, correct handling of Pull Requests
   * Complexity of code/Code quality
 * Taiga Evaluation
   * How well did the team stick to scrum
   * Keep meeting minutes up to date, attend meetings
   * Create US, Tasks, move tasks, work on things, which commits belong to the task in progress
   * Who worked a lot, who did not
                 
# How to run the application
Dependencies:
- npm

To Run:
- Run ```npm install``` in the taigit/taigit folder
- Run ```npm start```
- Go to http://localhost:3000 to view the project
