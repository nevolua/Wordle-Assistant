# Wordle Assistant

Javascript code which, when ran on wordlegame.org during a game, will return ALL possible words that fit the criteria specified by whatever happened so far in the wordle game. Usually narrows the words down to 1-4 within 4 word prompts. 

## Requirements

- A browser
- Ability to run the javascript

## Running the script

1. Open main.js, then copy all of it. 
2. Run the script in the dev console, and it will read the words you've entered into the game, then with the data it's collected, print out a list of possible words to the console. 
3. Enter one of the possible words provided.
4. Repeat step 2 and 3 until success (almost 100% guaranteed to win unless you pick weirdly abstract words)

## Important Notes:

- Every time the script is ran, it will calculate the possible words using the previously entered words, which come out to green, yellow, or grey letters. It then prints the list of possible words, along with some other data to the console.
- If no words are entered yet, it will return undefined.
- The more criteria specified by the game, the more the script can narrow down the possible words.
- This project is open to contributions, specifically an automation of this script, which makes it easier to use, in the form of an extension/more complex script/program.
  
## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.
