# iOS Dependency Cards

# Game Rules

Rules 
To begin with, the orignal deck is shuffled. 
Each player starts a game with:
- a “Repo” deck of 10 random “Repo” cards, with all the values facing down.
- three random “Tool & Bug“ cards, whose value can be read by the player but kept hidden from the others.

Each round has a “caller”. The caller for the first round is chosen randomly. 

At the beginning of the round, each player pops the topmost card from his personal “Repo” card deck, without showing it to the others.

After reading all the properties, the caller picks a property and reads it. 

The properties that can be picked are as follows:
- Stars (the higher, the better)
- Commits (the higher, the better)
- Contributors (the higher, the better)
- Forks (the higher, the better)
- First commit (the more recent, the better)

In turns, all the players read the value for the given property. 

The “caller” can then use one of the “Tool or Bug” card and use it against another player or for his/her own good to affect the value of the called property.

The player having the best value for the called property gets all the cards of the round, puts them on bottom of the personal deck and becomes the “caller”.

Each “Tool & bug” card can be used only once throughout the game and lasts for the number of rounds defined by the card itself. 
A “Tool” card can be used to increase the value of caller’s card. A “Bug” card can be given by the caller to another player at discretion, in order to negatively affect the opponent.

The game ends when one player wins all the cards of the other players’ “Repo” decks.

## Example

Craig, Eddy and Tim are given a deck of 10 “Repo” cards and 3 “Tools & Bugs” card each.

Craig is randomly selected to be the “caller” for the first round.

The three players pop the topmost repo card from their own personal “Repo” deck. 
 
Craig picks the property “Stars”. All the players publicly declare the “Stars” value of their cards: Craig’s repo card has 1226 stars, Eddy 201 and Tim 2000. 

Craig can then decide whether to use of of his “Tool & Bug” cards for the round. Craig owns a bug card that halves the number of stars of an opponent at his discretion, so he gives it to Tim, whose “Stars” points will now have a value of 1000.

Craig wins the round and puts all the “Repo” cards of the round on bottom of his “Repo” deck. Since he is the winner of the round, Craig remains the “caller”.

In the next round, all the players pop a new “Repo” card. Craig picks the property “Commits”: his own value is 350, Eddy has 382 and Tim 488. Craig decides not to use any of his two remaining “Tool or bug” card. Tim wins the round, collect all the “Repo” cards, including his own, and put them on bottom of his deck.

The game continues until one player has all the “Repo” cards, and the others have none. 
