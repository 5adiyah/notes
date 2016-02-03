### Project 2 Algorithm
By: Sadio Ali
01/27/2016

Welcome Users
	Print out: "Hello, welcome to the game. This game will require there to be two players, 
	Please go and find a friend to play with you.
	
	Print out: The game instructions are: The first player will type in a question of their choice. Their opponent, player 2, will have 5 tries to rewrite the same question back into the terminal. The trick is, the question will only be displayed for a short amount of time before the screen is cleared. Each time the player views the question, they loose points. For every correct word they type in they will gain points. We will continue until one of you has 0 points. That player is the looser. 

Display Points
	Print out: Each player will start off with 10 points. Each time you are shown the question you will loose a point. For each word that you correctly type in, you will regain points
	When you are regaining these points, you will not exceed your original 10 points. 
	We will continue to play until one of you has 0 points. That player will have lost the game.
	
	Variables:
		int p1points
		int p2points

Coin Toss
	- Print out "To start the game, the computer will do a coin toss to determine who will start the gme.
	- Prompt user one "Player 1, would you like to be Heads (Enter 1) or tails (Enter 2)? (Please type in 1 or 2
	- Read in the users response (1/2)
	- If response is not equal to 1 or 2, display error message, have user reenter
	- Generate a coin toss
	- Print out the results of the coin toss (heads/tails)
	- If the results of the coin toss == users choice, print out "Player 1 starts us off!"
	- If the results of the coin toss != useres choice, print otu "Player 2 starts us off!"
	
	Variables:
		int userschoice
		int tossresults

Enter in Question
	Prompt the user to enter in a question "Please type in a question"	
	array question

Print question
	prompt user "It is now the next players turn, are you read? Please enter Y or N"
	Read in response (y/n)
	Upper case the response
	If response != y/n print out error message, have user reenter
	print out the question
	clear the screen (function)

Answer the question
	Ask user if they are ready to type in the question "Are you ready to type in the question you just saw? Please enter Y or N"
	Read in the users response (y/n)
	Upper case the response
	If response != y/N print out error message, have user reenter
	
    As long as number of tries is less than 5 (maybe 10?) 
	Check if response == y
	If yes
		prompt user to type in the question "Please type in the question you just saw. You will get points for every correct word"
		read in the response
		Count the number of words that are the same between the original question and the one the user just retyped in.
		For every word that is the same in both questions, add a point to the users total points. If the points add up to 10, do not exceed 10
			compare the two questions
				if they got the whole question right (all the words are the same between the two sentences)
					 then have the user enter in the answer to the question they were asked
					Exit loop to switch users, continue until p1points == 1 or p2points == 0
						print out: ___points is equal to 0, ___ has lost the game, ___ has won!
				if they only got a couple words correct
					tell the user "you got x number of words correct"
					your points are now __
					go back to the beginning of answer the question
	If no
		print out the question
		clear the screen
		go back to beginning of answer the question


