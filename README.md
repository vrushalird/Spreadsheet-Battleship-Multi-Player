# Spreadsheet Battleship (Multi-Player Version)

## Project Description:

The Spreadsheet Battleship game developed in Excel using VBA programming offers an engaging multiplayer experience for more than two players. Inspired by the classic board game, this digital rendition allows players to strategically position their fleet of ships on a grid within the Excel spreadsheet. Through VBA automation, players take turns guessing the coordinates of their opponents' ships, aiming to sink them before their own fleet suffers the same fate.

## Key Features:

* <b>Multiplayer Gameplay</b>: Unlike traditional Battleship games limited to two players, this Excel version supports multiple players, enhancing the competitive dynamics and fostering collaboration and interaction among participants.

* <b>Dynamic Grid Interface</b>: The Excel spreadsheet serves as the battleground, with each cell representing a coordinate on the grid. Players input their guesses and track hits, misses, and sunk ships in real-time, creating an intuitive and visually appealing interface.

* <b>Customizable Fleet</b>: Players can customize their fleet of ships, choosing from various sizes and shapes to deploy strategically on the grid. This adds an element of planning and tactical decision-making to the gameplay.

* <b>VBA Automation</b>: The game leverages VBA programming to automate various game mechanics, including ship placement, turn management, and result calculations. This streamlines gameplay and ensures a smooth and seamless experience for all participants.

* <b>Scalability</b>: With support for multiple players, the game is scalable and adaptable to different group sizes, making it suitable for casual gaming sessions, team-building activities, or educational purposes.

Overall, the Spreadsheet Battleship game in Excel offers a modern twist on a timeless classic, combining the familiarity of the traditional board game with the versatility of digital technology. Whether played for leisure or as a collaborative challenge, it provides an entertaining and interactive experience for players of all ages.

## How to Play 
1. Download the files from [Host Template](Host%20Template%20File) and [Players Template](Players%20Template%20File).
2. Host will distribute Players Template file with the team by updating "Your Ship" tab with individual Players' name. This is just to track each player's sheet.
3. Players will take 10 minutes to place their ships on Battleship board. Please refer Players template file for more instructions.
3. Host will consolidate all Players sheets into Host file.
4. Host will Click on Create Players Table button. This will create a score table for each player in the Host sheet.
6. First player (Attacker) will tell his/her firing shot. Host will navigate to that cell location and enter X. It will determine whose ship was Hit/Sunk and total number of Hits/Sunks among all Players.
7. Other players (Defenders) will mark their Battleship board with X if their ship is Hit, and with O if it is a Miss.
8. Attacker will track his shots in the enemy ship with X if it hits any Players ship. There is no need to mark with O if it is a Miss.
9. Host will track players shot in the Shots tab by entering X. It will be automatically converted to O if none of the Players' ship was hit.
10. The last player with remaining ship becomes the winner and the one with highest score will become the runner up.

## Score Criteria
* <b>Hit</b> - Score 1 per player
* <b>Hit and Sunk</b> - Score 2 per player

## Note
* Grid size of 10x10 is fixed.


