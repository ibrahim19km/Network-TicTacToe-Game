# Network-TicTacToe-Game

How to Run:
1. Open the Network Tic-Tac-Toe Game (file attached) as a project in any suitable Java IDE.
2. Run the TicTacToeServer.java file.
3. "Tic Tac Toe Server is Running..." prompt will be displayed at the server console in the Java IDE.
4. This means that the server has started running.



Now if You have a single pc to run, follow the steps given below:

	{Before running the TicTacToeClient.java file make sure that you change the hostname of the server to the hostname of the pc on which server is running on line number 32.}

	1. Now Run the TicTacToeClient.java file for the first time to play as player X.
		a. "Player X Connected." message will be displayed on the server terminal if the player connects successfully.
		b. And a new JFrame window will open displaying the game board labelled as "Tic Tac Toe: Player X" at the top of the window.
		c. The window will have a message at the bottom of the JFrame saying "Waiting for opponent to connect".
		d. At the client console in the Java IDE there will be a message displayed saying "Connected to: 'IP Address of the Server'".
	2. Now run the TicTacToeClient.java file another time to play as player O (only if you have a single pc).
		a. "Player O Connected." message will be displayed on the server terminal if the player connects successfully.
		b. And a new JFrame window will open displaying the game board labelled as "Tic Tac Toe: Player O" at the top of the window.
		c. Both the players once connected, the first turn is of Player X, so "Your Move" message will be displayed at the bottom of Player X JFrame window.
		d. While at the bottom of Player O JFrame window "..." will be displayed.
	3. Now as the game progresses, different messages will be displayed throughout the game for both the players.
	4. At the same time, the response of each player will be sent to the server and server will display the response on the server side console.
	5. After the game is over, respective messages will be displayed in case of any result.
	6. While at the same time, the result of the game will be displayed at the server console.
	7. And at the end, the respective result of each client will be displayed at their client console after the JFrame window is closed.



But if You have multiple pcs to run, follow the steps given below:
	
	{Before running the TicTacToeClient.java file make sure that you change the hostname of the server to the hostname of the pc on which server is running on line number 32.}
	
	1. The TicTacToeServer.java can be run on any of the two pcs or maybe on a third pc.
	2. Run the TicTacToeClient.java file on different pcs.
		a. Make sure if the TicTacToeServer.java is running on a third pc, then the third pc should not run TicTacToeClient.java.
		b. Also make sure that the pcs can ping each other as well as the server pc (try this by running "ping 'IP Address of PC'" command on the command promt).
		c. Step b is to make sure that the pcs are able to connect to each other and there is no connectivity problem.
	3.  Now as the game progresses, different messages will be displayed throughout the game for both the players.
	4. At the same time, the response of each player will be sent to the server and server will display the response on the server side console.
	5. After the game is over, respective messages will be displayed in case of any result.
	6. While at the same time, the result of the game will be displayed at the server console.
	7. And at the end, the respective result of each client will be displayed at their client console after the JFrame window is closed.



The Project is explained in detail and with screenshots of the output and consoles(Server, Client X and Client O) in the .ppt file.
