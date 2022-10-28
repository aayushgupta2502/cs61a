# cs61a
Contains projects developed in UC Berkeley's Structure and Interpretation of Computer Programs course.
Project #1: Hog
In Hog, two players alternate turns trying to be the first to end a turn with at least 100 total points.
On each turn, the current player chooses some number of dice to roll, up to 10. That player's score for the turn is the sum of the dice outcomes.
However, a player who rolls too many dice risks:
--Sow Sad. If any of the dice outcomes is a 1, the current player's score for the turn is 1.
--Picky Piggy. A player who chooses to roll zero dice scores the nth digit of the decimal expansion of 1/7 (0.14285714...),
where n is the opponent's score. As a special case, if n is 0, the player scores 7 points.
--Hog Pile. After points for the turn are added to the current player's score, if the players' scores are the same, the current player's score doubles.

Project #2: Cats
In this project, I wrote a program that measures typing speed.
Additionally, it also implements typing autocorrect, which is a feature that attempts to correct the spelling of a word after a user types it.
This project is inspired by typeracer.

Project #3: Ants
In this project, I created a tower defense game called Ants Vs. SomeBees.
Basic Idea: As the ant queen, you populate your colony with the bravest ants you can muster. Your ants must protect their queen from the evil bees that invade your territory.
Irritate the bees enough by throwing leaves at them, and they will be vanquished. Fail to pester the airborne intruders adequately,
and your queen will succumb to the bees' wrath. This game is inspired by PopCap Games' Plants Vs. Zombies.

This project uses an object-oriented programming paradigm, focusing on material from Chapter 2.5 of Composing Programs.
The project also involves understanding, extending, and testing a large program.

Project #4: Scheme
In this project, I developed an interpreter for a subset of the Scheme language.
Designed an evaluator which can do: 1) symbol evaluation, call built-in procedures, and definitions.
