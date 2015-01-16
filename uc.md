# Informal Use Case

## UC1: User login
Description: Both teacher and student need to identify themselves for using the system by enter their username and password
  
## UC2: Student Join a game
Description: Once student login into the game. They can find an opened lobby for them to join a game.
  
## UC3: Teacher/Student create a game  
Description: Once they login, they can create a lobby for other student to join.
If the creator is student, they will grant a moderator permission for that lobby only.  The moderator can limit the amount of team can join per lobby.  Once the lobby is full or moderator forces it, the game will start immediately.  Only online mode lobby can be created by moderator that is a student.  
If the creator is teacher, they will grant any permission that student moderator have, also can create in both online and live mode lobby
  
## UC4: Student answer the question
Description: The team who have the right, pick a question on the board.  
Then the question is appeared. Each team can press a button to answer the question.  
The first team that press the button first must answer that question. If correct, they will get a score  
equal to that question's score, otherwise their score will be deducted in the same amount, and the team which answer  
correctly will got a chance to pick another question. There also has a time limit for each question after press the button,  
if the team cannot answer within the time, their score will be deducted as well.

## UC5: Teacher adding/editing a question
Description: Only teacher who can add more question into the question bank. Adding question can be done only while teacher didn't act as moderator of any lobby.  Teacher can editing a question that incorrect, also delete it as well.
