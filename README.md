# Wordle Assistant

JavaScript code that, when run on wordlegame.org during a game, returns all possible words fitting the criteria specified by the current state of the Wordle game. This usually narrows the words down to 1-4 within four word prompts.

## Requirements

- A web browser
- Ability to run JavaScript in the browser's developer console

## Running the Script

1. Open `main.js` and copy its entire content.
2. Open the developer console in your browser (usually by pressing F12 or right-clicking on the page and selecting "Inspect").
3. Paste the copied script into the console and press Enter.
4. The script will read the words you've entered into the game and, using the collected data, print out a list of possible words to the console.
5. Enter one of the possible words provided.
6. Repeat steps 3-5 until you succeed (almost 100% guaranteed to win unless you pick unusually abstract words).

## Important Notes

- Each time the script is run, it calculates the possible words using the previously entered words, considering green, yellow, and grey letters. It then prints the list of possible words, along with additional data, to the console.
- If no words are entered yet, the script will return `undefined`.
- The more criteria specified by the game, the more accurately the script can narrow down the possible words.
- This project is open to contributions, particularly in automating this script to make it easier to use, possibly in the form of a browser extension or a more complex script/program.

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.
