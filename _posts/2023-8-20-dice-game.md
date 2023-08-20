> Suppose we play a game in which I give you a die to roll and offer to pay you in dollars the number that you roll (if you roll a 3, I'll pay you $3). I also stipulate that if you're dissatisfied with the number that you roll on your first try, I'll let you roll the die again with the same offer. I will allow a maximum of 3 "do-overs", though you can elect to stop after any roll.

> How much would you pay me to play this game?

Any amount under $4.9444

X ~ Game\
E[X] = ?

E[Dice] = 3.5\
=> only optimal to reroll on rolls of 1, 2, or 3

Game w/o reroll: E[X_0] = 3.5\
Game w/ 1 reroll: E[X_1] = (1/6)4 + (1/6)5 + (1/6)6 + (3/6)3.5 = 4.25\
    => after 1 reroll its now optimal to reroll on rolls of 1, 2, 3, or 4, since the EV is now >4\
Game w/ 2 rerolls: E[X_2] = (1/6)5 + (1/6)6 + (4/6)4.25 = 4.666\
Game w/ 3 rerolls: E[X_3] = (1/6)5 + (1/6)6 + (4/6)4.666 = 4.9444

E[X] = 4.9444\
Since the EV of the game is $4.9444, you should pay any amount <$4.9444 to play.



> How does this generalize to any number of "do-overs"?
