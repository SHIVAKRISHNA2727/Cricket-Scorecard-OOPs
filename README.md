# Cricket-Scorecard-OOPs
**Project Documentation: Cricket Match Simulator**

**1. Introduction:**
The Cricket Match Simulator is a program that simulates a cricket match between two teams. It uses a combination of object-oriented programming concepts and randomization techniques to generate match scenarios. The program provides information about the teams, players, match details, and statistics.

**2. Features:**
- Simulates a cricket match between two teams.
- Generates random player details such as name, age, and number of matches played.
- Calculates the total score and wickets for each team.
- Determines the winning team based on the total score.
- Identifies players who scored a century (100 runs or more) in the match.
- Determines the player with the maximum number of wickets.
- Determines the Man of the Match based on performance.
- Provides match details such as date, trophy name, and venue.

**3. Technologies and Libraries Used:**
- C++ programming language.
- Standard C++ libraries: `iostream`, `stdlib.h`, `unistd.h`, `set`, `iterator`, `math.h`, `fstream`.

**4. Code Overview:**
The code consists of several classes, namely `player`, `team1`, `team2`, and `match`. These classes are used to represent players, teams, and the match itself. Each class has its own set of functions to perform specific tasks.

- The `player` class represents a player and contains information such as player name, age, and number of matches played.
- The `team1` and `team2` classes represent the two teams participating in the match. They inherit from the `player` class and include additional attributes and methods specific to a team.
- The `match` class represents the match and inherits from both `team1` and `team2`. It includes functions to calculate match statistics, display match details, and determine the Man of the Match.

**5. How the Code Works:**
- The `match` class is instantiated, which triggers the generation of player details for both teams, calculation of scores and wickets, and determination of the winning team.
- The `display` function is called to display match details, including team names, captains, toss result, and player details.
- The `isCentury` function checks if any player from either team has scored a century and displays their names.
- The `maxWickets` function identifies the player with the maximum number of wickets and displays their name.
- The `findManOfMatch` function determines the Man of the Match based on player performances and displays their name.
- The `display` function of the `match` class displays overall match details, such as date, trophy name, and venue.

**6. Future Enhancements:**
The Cricket Match Simulator can be enhanced with additional features and functionalities, such as:
- Implementing a more sophisticated scoring system, considering factors like run rate, boundaries, and extras.
- Introducing player-specific attributes such as batting style, bowling style, and role (batsman, bowler, all-rounder).
- Adding more realistic match scenarios, such as tracking partnerships and creating a match summary.
- Integrating graphical user interfaces (GUI) to provide a visual representation of the match and player statistics.
- Incorporating a database to store and retrieve match data for future reference and analysis.

**7. Conclusion:**
The Cricket Match Simulator is a simple yet engaging program that allows users to experience the thrill of a simulated cricket match. It demonstrates the use of object-oriented programming concepts and randomization techniques to create a realistic match scenario. With further enhancements, it has the potential to become a more comprehensive and interactive cricket simulation tool.
