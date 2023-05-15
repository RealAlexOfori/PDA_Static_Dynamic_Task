### Testing task 1:

# Carry out static testing on the code below.
# Comment on any errors that you see below.

Note that we are only looking for errors here.

**Not** any issues with, i.e.: 
Thinking that methods should be renamed or should be class level, or using string interpolation etc. 

These aren't errors but rather standards that vary from developer to developer. 

Only comment on errors that would stop the tests running.

```python

class CardGame:

# It should be if card.value == 1: on line 22 
#  there should be a colon after the else...else:, on line 24
  def check_for_ace(self, card):
    if card.value = 1:
      return True
    else
      return False
   
# On line 30, it should be def instead of dif and a comma after card1...(self, card1, card2)
# Also it should be return card1 instead of return card
# Also the whole code from if on line 31 to 34 should be indented
  dif highest_card(self, card1 card2):
  if card1.value > card2.value:
    return card
  else:
    return card2
  

# The first total on line 38 should be equal to 0 i.e total = 0.
def cards_total(self, cards):
  total
  for card in cards:
    total += card.value
    return "You have a total of" + total
  
```
