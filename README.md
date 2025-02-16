<<<<<<< HEAD
﻿# Typing Speed Calculator

This project is a simple command-line Typing Speed Calculator built using Python. The application measures typing speed (Words Per Minute - WPM) as users type a sample text. It uses the `curses` library for text-based UI.

## Features
- Measures typing speed in WPM.
- Highlights incorrect characters in red.
- Displays typing progress in real-time.
- Allows users to exit the test by pressing the `Esc` key.

## Requirements
- Python 3.6+
- `windows-curses` (for Windows users)

## Installation
1. Clone or download this repository.
2. Ensure Python 3.6 or later is installed.
3. Install the required library (for Windows users):
   ```bash
   pip install windows-curses
   ```

## How to Run
1. Open the terminal (or command prompt) and navigate to the project directory.
2. Run the following command:
   ```bash
   python main.py
   ```
3. Enter your name when prompted and press Enter.
4. Follow the on-screen instructions to complete the typing test.

## Sample Text
The default sample text for the typing test is:
```
This is a sample text for this typing test.
```

## Keybindings
- `Backspace`: Removes the last character typed.
- `Esc`: Exits the typing test.

## Code Explanation
### Main Functions:
- `start_screens(stdscr)`: Displays the welcome screen.
- `display(stdscr, target, current, wpm)`: Shows the target text, the user’s input, and the current WPM.
- `wpm_test(stdscr)`: Runs the typing test, measuring WPM and handling user input.
- `main(stdscr)`: Initializes color pairs and manages the main application flow.

### Colors:
- Green: Correct characters.
- Red: Incorrect characters.
- Magenta: Informational text and messages.

## Future Improvements
- Add more sample texts or randomize the text.
- Improve accuracy tracking.
- Add support for multiple languages.

## License
This project is open-source and free to use for educational and personal purposes.

## Acknowledgments
- Python's `curses` library for text-based UI.

Feel free to contribute by submitting issues or pull requests!

=======
# Typing-Speed-Calculater
>>>>>>> 604f5b08637fec2aaedb16acea68814267e3894b
