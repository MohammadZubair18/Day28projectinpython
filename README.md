# Day28projectinpython
Tic Tac Toe in Python

Tic-Tac-Toe using Python Project
Hey folks, as we all are now aware that Python supports thousands of modules and packages to crack any logic behind the idea! And here also Python will help you play and create a very renowned and interesting game which we have all gotten our hands on since our childhood. Yes, you read it correctly game using Python and that’s Tic-Tac-Toe!, so let’s start our journey for Tic Tac Toe in Python Project with source code.


What is the Tic Tac Toe game?
Tic Tac Toe is a 2 player game where each player has a symbol (either X or O) and plays alternately to mark their symbol on a 3×3 grid.

![image](https://user-images.githubusercontent.com/116421874/203126875-faae8e10-081e-4ab7-9343-d4c78fa35bb2.png)



what is Tic Tac Toe
If any player gets their(X or 0) symbol consecutively 3 times in a row, column or diagonal then that player is the winner. So, in total, we have 8 winning conditions: 3 for the rows, 3 for the columns, and 2 for the diagonals. Isn’t it interesting!

So, we will be coding it in Python using Tkinter for the interface.

‘Tkinter‘ is one of the known in-built libraries of Python. It is a standard Python interface to the Tk GUI toolkit shipped with Python. Python with tkinter is the fastest and easiest way to create GUI applications. All you need to do is perform the following steps:

We first need to import the tkinter module.

Since we also have to display the results, we should use messagebox widget. As MessageBox Widget is used to display the message boxes in the python applications. Hence to use this, we have to import messagebox:

from tkinter import *
import tkinter.messagebox 
Using * after import means we have imported all the methods and variables of the tkinter library.

Now, let’s create the GUI application’s main window i.e. game window.

Here, we will create a Tk widget and assign it to a variable root. And title() is used to set the title of the window.

Let’s assign two variables: click and count as well. Initialize ‘click’ to ‘True’ and ‘count’ to ‘0’. According to our logic, if click=True that means ‘X’ is clicking and if it is False that means it’s time for ‘0’ to click, while the count variable will check how many turns have been played, and after every turn, the count variable will be incremented by 1.
