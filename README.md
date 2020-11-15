# antposter
UCI two truths one lie game
## Inspiration
At first, we wanted to make an app or website that functioned similarly to the UCI Confessions Page on Facebook. We also wanted to make it a type of game. We decided to pivot to our base idea which combined the two ideas into a game with a submission system, which would use those submissions in a sort of 2 Truths - 1 Lie game. The name drew inspiration from the recently popular game Among Us, where there is an "imposter"; thus we chose to name the game AntPoster(pronounced Ant-Pawster).
## What it does
AntPoster has 5 interfaces. The main interface allows the user to access three other ones: the submission page, the moderator login, and the actual game page. The submission page is where people can submit both truths and lies, which goes to a database that holds both lies/truths. The moderator login requires a password to access the database of lies and truths. After logging in, the moderator can accept or reject submissions, thereby sending the truths/lies to their respective databases. On the game page, 2 truths are randomly pulled from the truth database and one lie is randomly selected and placed on one of the buttons on the page. Clicking on a button should refresh the page, and increment a point if you got it correct, or increment a loss if you got it incorrect. The game page goes to the game over page if you have 3 losses.
## How I built it
The program is mainly HTML code, and a bit of JS. The backend portion is python, but it is not quite finished yet.
## Challenges I ran into
The most urgent challenge we ran into was finding a way to implement the database system using MongoDB to our program. 
## Accomplishments that I'm proud of
We're most proud of having a functional site, although some aspects are missing.
## What I learned
We expanded our knowledge of HTML and got some experience tinkering with new languages and libraries, such as JS and PyMongo.
## What's next for AntPoster
AntPoster aims to add a high score system and fix several of the present flaws.
