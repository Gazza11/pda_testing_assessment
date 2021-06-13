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


  def check_for_ace(self, card): # Line 23, else statement missing a colon. Line 21, needs an extra '='.
    if card.value = 1:
      return True
    else
      return False

  dif highest_card(self, card1 card2): # Spelled def wrong, swap dif for def. Missing comma after card 1 in parameters of function. Missing indentation on line 28. Line 29, card needs to be card1.
  if card1.value > card2.value:
    return card
  else:
    return card2
  

def cards_total(self, cards):  # Define total as 0. Line 39, return should be indented to the same line as the start of for loop on line 37. Line 39 has been changed to allow the total to be added to a string.
  total                      
  for card in cards:
    total += card.value
  return f"You have a total of {total}"
```
