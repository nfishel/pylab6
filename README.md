# pylab6
PyLab6 Dice Game

#Step 1: Have the User Select the Number of Dice 🎲
Create a new file called `dicegame.py` and add a comment at the top. Ask the user for the number of dice to be used in this game and store it in a variable called `number_of_dice`. Before starting the game, ask the user to hit a key when ready for the game.

{% spoiler "Hint" %}
Don't forget to cast the `number_of_dice` to an `int`
{% endspoiler %}

Run your program by typing:
```python
python dicegame.py
```
in the terminal window.

{% spoiler "Soluttion" %}
```python
# dice game

#step 1 in main program area - start game
number_of_dice = int(input('Enter the number of dice: '))
ready = input('Ready to start? Hit any key to continue.')
```
{% endspoiler %}

{% next "Step 2" %}

