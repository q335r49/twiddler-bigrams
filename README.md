# bigramsLayout
A bigram-friendly version of the default layout

# Motivation
The default twiddler layout is easy to memorize but terrible for typing. This layout rearranges the letters, while keeping the remaining keys (symbols, numbers, etc.) unchanged, with the following heuristics:
1. Most common letters should be unchorded
2. Most common bigrams should alternate fingers, as it is slow to type two consecutive letters with the same finger. This means that, although "n" is very common, it is placed on the pinky since it forms very common bigrams with the letters in the other rows.
3. Common bigrams should be "easy". For example, "of" is the most common bigram requiring a chorded letter, and since, "o" is a common letter so unchorded, and "f" is mapped to "o+e" so "of" is easy.
4. Chorded letters hould be easy. For example, ring finger chords (row 3) are reserved for rarer letters because of the difficulty of moving that finger.
   
Frequency data is found here:
https://norvig.com/mayzner.html
