# Homework Advanced Cursors: Legends of the Hidden Temple

## Introduction
You have decided to create an app celebrating the 20th anniversary of Legends of the Hidden Temple. Unfortunately, your friends quit halfway through working on the database and you have to pick up where he left off.

## Requirements:
All you need to do is add the following functionality to the app so we can ship it:

- Make sure that game scores aren't added to a game already in the database (in table games, column game).
- Add a button to reset the database so we can add new things if we want.
- Populate the mostGamesWon textview in StatsActivity.
- Populate the longestLosingStreak textview in StatsActivity (This is the hardest. Save for last).

The places where the changes need to be made are marked as "TODO" in the code.

#### Bonus

- Fix the bug when the submit button is clicked.
- Add a checkbox if a team found the idol or not. Populate the idol column in the game table with this information. Remember that only one team can win the idol per game, so the idol can be found either 0 or 1 times per game. A team who finds the idol will automatically win the game (no matter how many points they have).
- Add a listview so that a user can see the StatsActivity statistics for each team when the team is clicked.
- Add material design graphics to make the design of the app "pop".
