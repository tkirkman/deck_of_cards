# deck_of_cards

### Setup from command prompt
1. irb -I"./"
2. require 'cards'
3. require 'deck'

### Commands:
#### Create a new deck
deck = Deck.new

#### Shuffle deck
deck.shuffle

#### Draw(num)
deck.draw(3)

#### Count remaining cards
deck.card_count
