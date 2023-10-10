# Wordle Assistant

Javascript code which, when ran on wordlegame.org during a game, will return ALL possible words that fit the criteria specified by whatever happened so far in the wordle game. Usually narrows the words down to 1-4 within 4 word prompts. 

## Requirements

- A browser
- Ability to run the javascript

## Running the script

1. Open main.js, then copy all of it. 
2. Paste the script into the developer console of a tab opened to wordlegame.org and press enter. (which runs the script)
3. Run the script, and it will give you the most likely words, which you can use for the next step of the game.
4. Repeat step 3 until success.

## Important Notes:

- Every time the script is ran, it will calculate the possible words using the criteria specified (green, yellow, or grey letters) by the game, and print them to the console.
- So, if you run the script without entering any words into the game, it will give a list of thousands of words, because there is no criteria to be met.
- The more criteria specified by the game, the more the script can narrow down the possible words.
- Once you've ran the script once, instead of pasting it again, you can make it easier by pressing up-arrow while having the command line selected, and it will automatically fill in with the script.

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.
