# bigramsLayout
A bigram-considerate version of the default layout

# Motivation
- The default twiddler layout is easy to memorize but terrible for typing and does not contemplate character or bigram frequency.
- Fast, intuitive typing comes from one finger anticipating the next letter before the previous finger has left the current input. Hence, the ease of entering bigrams should be central in considering key layout.
- The default twiddler layout is "modal" or "layered". This means that chords can be conceived of as mode switching, that there are special modes for later characters in the alphabet, for numbers, movement, symbols, etc. and that these are not generally intermixed. Modality has advantages in ease of learning and conceptualization.
- Existing custom layouts are often directed to tuning special characters or functions that are use-case specific. Special use letters and functions (e.g., arrows, numbers, copy and paste) are single use functions that can be individually and arbitrarily asigned since they are generally independent of previous and subsequent letters. Hence, they should be separated modally from alphabetic letters.
- Thus, the need arises for a layout that considers character frequency and the ease of typing consecutive letters (bigrams) for a universal prose use case while retaining the modality of the default layout.

# Heuristics
- The most common letters should be unchorded
- The most common bigrams, unsurprisingly, involve the most common letters. These bigrams should alternate fingers, as it is slow to type two consecutive letters with the same finger. This means that, since "n" forms very common bigrams with the letters in the other rows, it is placed in the pinky finter to ensure alternating fingers. The only (unavoidable) exception to this is "EA", but "EA" is comparatively less common as both letters form more common bigrams with the remaining letters.
- Bigrams with chorded letters should be easy. For example, "of" is the most common bigram requiring a chorded letter, and since, "o" is a common letter and so unchorded, and "f" is mapped to "o+e" so that "of" is easy. Other considerations are "ly", "wh", "ng", etc.
- Chorded letters hould be easy. For example, ring finger chords (row 3) are reserved for rarer letters because of the difficulty of moving that finger without affecting other fingers.

   
Frequency data source:
https://norvig.com/mayzner.html

# Layout

```
|A E I|  |  *  |  |       *|  |       |  
|D T L|  |P C '|  |U  J Ret|  |      *|
|O H S|  |F M Z|  |K  Q Del|  |   +   |  *y
|N R _|  |G B V|  |X BS Cap|  |   +  *|  +w
```

The remaining symbols, letters, etc. remain unchanged from the default layout.
