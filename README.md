# Soccer-Team-Roster
This program will store roster and rating information for a soccer team. Coaches rate players during tryouts to ensure a balanced team.
From Milestone 1:

Step 1: Prompt the user to enter four numbers, each corresponding to a person's weight in pounds. Store all weights in a list. Output the list.

Example:

Enter weight 1:

236.0

Enter weight 2:

89.5

Enter weight 3:

176.0

Enter weight 4:

166.3

Weights: [236.0, 89.5, 176.0, 166.3]

Step 2: Output the average of the list's elements with two digits after the decimal point. Hint: Use a conversion specifier to output with a certain number of digits after the decimal point. Output the max list element with two digits after the decimal point.

Example:

Enter weight 1:

236.0

Enter weight 2:

89.5

Enter weight 3:

176.0

Enter weight 4:

166.3

Weights: [236.0, 89.5, 176.0, 166.3]

Average weight: 166.95

Max weight: 236.00

Fix any issues with milestone 1 submission prior to submitting the Portfolio Project.

From milestone 2:

Step 3: Prompt the user to input five pairs of numbers: A player's jersey number (0 - 99) and the player's rating (1 - 9). Store the jersey numbers and the ratings in a dictionary. Output the dictionary's elements with the jersey numbers in ascending order (i.e., output the roster from smallest to largest jersey number). Hint: Dictionary keys can be stored in a sorted list.

Example:

Enter player 1's jersey number:

84

Enter player 1's rating:

7

Enter player 2's jersey number:

23

Enter player 2's rating:

4

Enter player 3's jersey number:

4

Enter player 3's rating:

5

Enter player 4's jersey number:

30

Enter player 4's rating:

2

Enter player 5's jersey number:

66

Enter player 5's rating:

9

ROSTER

Jersey number: 4, Rating: 5

Jersey number: 23, Rating: 4

Jersey number: 30, Rating: 2

...

Step 4: Implement a menu of options for a user to modify the roster. Each option is represented by a single character. The program initially outputs the menu after a user chooses an option. The program ends when the user chooses the option to Quit. For this step, the other options do nothing.

Example:

MENU

a - Add player

d - Remove player

u - Update player rating

r - Output players above a rating

o - Output roster

q - Quit

Choose an option:

Fix any issues from milestone 2 submission prior to submitting the Portfolio Project.

Additional tasks to add before submitting the final project:

Step 5: Implement the "Add player" menu option. Prompt the user for a new player's jersey number and rating. Append the values to the two vectors.

Example:

Enter a new player's jersey number:

49

Enter the player's rating:

8

Step 6: Implement the "Delete player" menu option. Prompt the user for a player's jersey number. Remove the player from the roster (delete the jersey number and rating).

Example:

Enter a jersey number:

4

Step 7: Implement the "Output players above a rating" menu option. Prompt the user for a rating. Print the jersey number and rating for all players with ratings above the entered value.

Example:

Enter a rating:

5

ABOVE 5

Jersey number: 66, Rating: 9

Jersey number: 84, Rating: 7

Your final program submission materials must include your source code and screenshots of the application executing the code and the results.
