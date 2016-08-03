1. Created using Android Studio, just open the app using Android Studio
2. The app looks like the Guess2.png file added, and this app wasn't done with beauty in mind, but it works
3. The code is easy to follow and modify. 
4. Play the guessVid.mp4 for a screencast of the app, I did not use the emulator keyboard while doing the demo, but you can
5. Unzip the GuessTheNumber2 folder to get the project for Android studio. 
6. Run the app
- Click on one of the 2 ranges
- Enter a guess number. The Trick is to divide by half to home into the answer,
so for a 100 range, first number can be 50, and the output will tell Lower or Upper,
if Upper, then choose 75, it is lower, then you know your answer in between 50 and 75,
so keep dividing.
- When you run out of guesses, the computer has won the game, and a score recorded for the computer,
and saved, even when you close the app, and reload it, the score is still available
- Click on the start New Game to start a new game, this can be clicked at anytime
- The Reset button resets the game, and the saved scores set to 0.
- When you win, then a score is recorded for the player, and the Start New Game should be
clicked to continue playing.
- There is an ImageView that displays the state of the game.
- If a wrong number or charactered is entered, the user will be notified.
- A Toast massage, displays what range was selected, and the other range's button is disabled.
 
Tested with:
- android api 19 kitkat
- android api 22 lollipop
- android api 23 marshmallow 
 
Not test with:
- android api 21 lollipop

Written by U.T. Otite
