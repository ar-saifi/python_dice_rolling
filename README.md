# python_dice_rolling
🎲 Dice Roller with ASCII Art
This Python script simulates rolling multiple dice and displays the results using visually appealing ASCII art. It also calculates and prints the total of all dice rolled.
📋 Features
- Prompts the user to enter the number of dice to roll.
- Randomly generates values between 1 and 6 for each die.
- Displays each die using stylized ASCII art side by side.
- Calculates and prints the total sum of all dice.
🧠 How It Works
- User Input:
The script asks: How many dice? and stores the number.
- Dice Generation:
It uses random.randint(1, 6) to simulate each die roll.
- ASCII Art Display:
Each die face is mapped to a 5-line ASCII representation stored in the dice_art dictionary.
- Side-by-Side Rendering:
The dice are printed line-by-line to appear horizontally aligned.
- Total Calculation:
The sum of all dice values is printed at the end.
