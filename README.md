Download Link: https://assignmentchef.com/product/solved-python-program-to-manage-information-about-baseball-players
<br>
Assignment Specifications

1. You will develop a Python program to manage information about baseball players. The program will maintain the following information for each player in the data set:player’s name (string)team identifier (string)games played (integer)at bats (integer)runs scored (integer)hits (integer)doubles (integer)triples (integer)homeruns (integer)

2. The program will recognize the following commands: QUIT HELP INPUT filename TEAM identifier REPORT n PLAYERS The program will be operated interactively: it will prompt the user and accept commands from the keyboard.If the user enters an invalid command, the program will display an appropriate message and prompt the user to enter another command.

3. The “QUIT” command will halt execution.

4. The “HELP” command will display information to the user about the commands recognized by the program.

5. The “INPUT” command will be followed by a string representing the name of an input file. The program will discard the current data set stored in memory, and then process the input file as the source for a new data set (open the file, read the file once and store the records, then close the file).An input file contains zero or more player records, where each record consists of the nine fields listed above. The records are separated by newlines, and the fields are separated by semicolons.If the user enters an invalid file name, the program will display an appropriate message and prompt the user to enter another file name. The program will halt after the user enters an invalid file name three consecutive times.

6. The “TEAM” command will be followed by a string representing a team identifier. The program will display all information about all players on that team.If the user enters an invalid team identifier, the program will display an appropriate message and prompt the user to enter another command; the program will not display an empty table.

7. The “REPORT” command will be followed by an integer number and a string (one of “HITS”, “BATTING” or “SLUGGING”).If the user enters an invalid command, the program will display an appropriate message and prompt the user to enter another command; the program will not display an empty report.For each report, the program will display all information about the top “n” players in a given category:HITS — number of hitsBATTING — batting averageSLUGGING — slugging percentage

8. The program will display appropriate messages to inform the user about any unusual circumstances.

Assignment Note

1. The file named “mlb.2013.txt” contains information about players on the teams in Major League Baseball in 2013.

2. The file named “mlb.part.txt” contains information about 20 players on teams in Major League Baseball in 2013; that file will be useful for your initial development. The first few lines of that file are shown below:De Aza, Alejandro; CWS; 153; 607; 84; 160; 27; 4; 17Hunter, Torii; DET; 144; 606; 90; 184; 37; 5; 17Hamilton, Josh; LAA; 151; 576; 73; 144; 32; 5; 21Choo, Shin-Soo; CIN; 154; 569; 107; 162; 34; 2; 21Upton, Justin; ATL; 149; 558; 94; 147; 27; 2; 27Cabrera, Miguel; DET; 148; 555; 103; 193; 26; 1; 44Posey, Buster; SF; 148; 520; 61; 153; 34; 1; 15Suzuki, Ichiro; NYY; 150; 520; 57; 136; 15; 3; 7Holliday, Matt; STL; 141; 520; 103; 156; 31; 1; 22Headley, Chase; SD; 141; 520; 59; 130; 35; 2; 13