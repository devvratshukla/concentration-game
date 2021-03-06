# concentration-game
A browser-based card matching game (also known as Concentration Game)

## How The Game Works
The game board consists of sixteen "cards" arranged in a grid. The deck is made up of eight different pairs of cards, each with different symbols on one side. The cards are arranged randomly on the grid with the symbol face down. 

### Gameplay rules:
The gameplay rules are very simple: flip over two hidden cards at a time to locate the ones that match!

### Gameplay details:

1. The player flips one card over to reveal its underlying symbol.
2. The player then turns over a second card, trying to find the corresponding card with the same symbol.
3. If the cards match, both cards stay flipped over.
4. If the cards do not match, both cards are flipped face down.
5. The game ends once all cards have been correctly matched.

## Dev setup
1. git clone this repo
2. From the project's root directory run:
```$ npm install``` and then ```$ gulp```

## Dependencies
1. [jquery](http://jquery.com/)
2. [jquery-confirm](http://craftpip.github.io/jquery-confirm/)
3. [EasyTimer.js](https://albert-gonzalez.github.io/easytimer.js/)