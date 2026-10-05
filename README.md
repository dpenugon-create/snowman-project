# Snowman Game
A python hangman game with 2 difficulty levels, a hint system, and 2 different languages.
##  Features
My bonus features are different languages, difficulty levels, and a bonus round.
How does the game pick a word?
The game picks a word using .random to pull from a list of words
How does it check a letter guess against the word?
It runs a for loop for the length of a list comprised of all the letters in the word. Then, it checks if each of those letters match, if it does, it replaces that index with the matching letter. 
How does it decide when the player has won or lost?
When the guesses = 0, they try to guess the whole word unsuccessfully, or they get the word within the guesses.
## Challenges I Ran Into
replacing the letters in the word when they get it right was the biggest challenge because I initially used .replace, but since that looks for the first instance of that letter, it was breaking when there were repeated letters. I eventually used str slicing instead to successfully replace the matching letters.
## What I'd Improve With More Time
My code has some clunkiness and inefficiency, especially with how the for loop and nested for loop run, also, I have some "bugs", like in difficulty you can select 3, (Most of this is just try/except stuff that I didnt code in). Also, I would like to make the chatbot interface cleaner, with the order of the information you get presented more digestable and presentable. 
Made by Dexter Penugonda — [Your GitHub profile link]
