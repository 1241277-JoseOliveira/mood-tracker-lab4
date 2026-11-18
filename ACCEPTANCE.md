# Form validation: acceptance criteria

1. Given no score is selected, when I tap Save entry, then the message
   "Choose a score from 1 to 10" appears and nothing is added to the history.
2. Given a score is selected and a note of exactly 2000 characters,
   when I tap Save entry, then the entry is added to the history.
3. Given a score is selected and a note of 2001 characters, when I tap
   Save entry, then an error about the 2000-character limit appears and
   nothing is added to the history.
4. Given an error is showing, when I fix the problem and tap Save entry,
   then the entry is added and the error disappears.