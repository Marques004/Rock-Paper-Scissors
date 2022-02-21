### Development

Do not modify `RPS_game.py`. Write all your code in `RPS.py`. For development, you can use `main.py` to test your code. 

`main.py` imports the game function and bots from `RPS_game.py`.

To test your code, play a game with the `play` function. The `play` function takes four arguments:
- two players to play against each other (the players are actually functions)
- the number of games to play in the match
- an optional argument to see a log of each game. Set it to `True` to see these messages.

```py
play(player1, player2, num_games[, verbose])
```
For example, here is how you would call the function if you want `player` and `quincy` to play 1000 games against each other and you want to see the results of each game:
```py
play(player, quincy, 1000, verbose=True)
```

Click the "run" button and `main.py` will run.

### Challenge Accepted.


