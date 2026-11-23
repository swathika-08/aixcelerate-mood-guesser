# aixcelerate-mood-guesser
A python project that guesses whether a sentence a Happy or Sad mood.
The functions counts Happy and Sad sentences and initially it counts the mood and then guesses the mood and predicts the mood of the sentence.
It then calculates the accuracy using the practise data.

Result: The program achived ranges from 25% to 100% depending on the sentence in level 3.
Learning Questions : 
1.Total score of :
      =>"good party today" - 2
2.Total score of:
      =>"bad exam day" - -1
3.why did "exam" get a score of 0,and is that good or bad ?
=> as the word exam 0 id not included in the mood list.
4.why is "not good" labelled happy and how it could it be fixed ?
=>not good is labelled as happy as the negative words are not being checked in the program.

AI declaration:
I used chatgpt to clarify the errors in my code and to understand the Github submission process and for understanding some concepts like finding accuracy.

Reflection:
The hardest part was understanding how the scores for the words was claculated using the dictionaries.
