Steps to run:

1- Unzip the file Mars-Rover.zip
2- Run the file Mars-Rover\bin\Debug\Mars-Rover.exe
3- Enter Plateu Length (Y)
4- Enter Plateu Width (X)
5- Enter Number Of Rovers 
6- For Each Rover Enter Following:
	i  - Enter the Landing Location in format X,Y,Dir  e.g. 0,1,N. 
	ii - Enter Instructions e.g. RLMLMRLLRRM


Note:

Following scenarios are handled:

-If there is already a rover located at landing location, You will be asked to enter landing location again.
-If the landing location of a rover is out of plateu boundries, You will be asked to enter landing location again.
-If a move insntruction will place rover to a location where there is already a rover placed, that instruction will be skipped and next instruction will be executed.
-If a move instruction will place rover outside the boundries of plateu, that instruction will be skipped and next instruction will be executed.