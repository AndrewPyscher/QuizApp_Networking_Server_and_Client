Description:

The client selects a quiz, and then sends the category to Server 1.
Server 1 accesses the database and returns the questions and answer choices to the client.
Server 1 also sends the correct answers to Server 2.
The client then takes the quiz. Once the quiz is finished, the client sends the users answers to Server 2.
Server 2 grades the quiz, and returns the score to the Client.
The client then checks if the score is the higher than the current high score, if it is then it updates the table and database.


Instructions:

Set up with IntelliJ
Depending on the version of IntelliJ, setup may be different. This is how to set up on the schools version of IntelliJ.
First download the project, then unzip the files where you store your projects.
Download the jdbc (provided).

****If you get a "jdbc not found" error****
In IntelliJ, go to File > Project Structure > libraries > + > then find and select your jdbc. (You may have to do this twice because the IntelliJ at SVSU is not the best)

If running on 1 computer:
Make sure that the hostname in the MainMenuController class on line 68 and 76 are "localhost"

If running on 2 computers:
Make sure that the hostname in the MainMenuController class on line 68 and 76 are the IP of the Servers computer

Start Server 1, Server 2, then Hello application.
Then begin the quiz.


Bugs:
The only "bug" is not with the code. Its just that you may have to select the jdbc twice sometimes.
There is also a warning saying that you are using an outdated version of JavaFX. This has no impact.

Contributions:

We worked together for all of it. So it was a team effort for the entire thing.
We took turns typing but the ideas came from us both.

Andrew:
Comments
Created Database, and DAO class.
Helped create Server 1 and 2
Set up the file structure.
Created half of the quizzes/ questions
Coded everything together

Madsion:
Comments
Helped create the database, but hasn't taken 411 yet.
Helped create Server 1 and 2
Designed the GUI
Created half of the quizzes/ questions
Coded everything together