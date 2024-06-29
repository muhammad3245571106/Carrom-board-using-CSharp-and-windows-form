# Carrom board frontend using CSharp and Windows form
This is a carrom board frontend developed using C# and Windows form.
## Carrom Game
Carrom or Karom is a game that has long been played throughout India and South East Asia but the game has
become increasingly popular throughout much of the rest of the world during the last century. There are a huge
number of variations in the rules even though an international regulatory body and several major national bodies
exist - even these have rule variations depending upon the situation. Masters Games has based the following rules
on those from the UK Carrom Club, tailoring them for simplicity where possible.
I implement this game in Windows Form using C# in Visual Studio. The game has the following functionalities.
- A carrom board which will contain nine white/light pieces, nine black/dark pieces, and one red colored
“Queen”.
- A striker ball colored “white” which will be used to strike the balls by the player.
Objective
Players take turns to play. A turn consists of one or more strikes. A player wins by pocketing all the pieces of their
colored balls plus the queen. Queen must not be pocketed before having pocketed all your colored pieces (i.e.,
Player one must pocket all nine pieces of white balls first, before pocketing the queen ball)
Striking
* For each strike, the player must position the striker within the baseline OR on one of the two circles at either
end of the baseline.
* A striker within the baseline must touch both the front line and the rear line.
* The striker may not "cut the moon" - be placed partially within the baseline and partially within the circle.
* The player must flick the striker with one finger so that it crosses the front baseline - it is not permitted to
flick backward or horizontally.
* A piece that is on or behind the front baseline must not be struck by the striker until the striker has crossed
the front baseline.
Basic rules
* The first turn is given randomly to one of the two players.
* It doesn't matter which piece the striker hits first and it doesn't matter if the striker hits no pieces.
* The player retains the turn if it pockets his piece(s).
* If the player pockets no pieces or commits a foul, the turn finishes.
Fouls
When a player commits a foul, the turn comes to an end immediately.
A foul is recorded in the following situations:
* The striker is pocketed.
* A player pockets an opponent's piece(s). Additionally, the opponent's pocketed piece will not be returned to the
board and the turn ends immediately after this, even if the player had pocketed his ball in the same turn.
* A player pockets the Queen, without having pocketed all his pieces first (in this case, the Queen returns to its
starting position on board as well after the turn). Moreover, since the player had pocketed the queen, one
piece of the same player will be added to the board (if there already exists 9 pieces, then no piece will be
added)
