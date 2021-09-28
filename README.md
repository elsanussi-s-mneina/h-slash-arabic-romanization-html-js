# h-slash-arabic-romanization
A web application for tranliterating Arabic to Latin characters according to a transliteration system made in 2021.


# Current Status
- works for demo purposes, but not widely tested and likely contains some errors.
- needs unit tests

# Plans
- This is going to continue being experimental.
- My current intention is to start this project over in a different programming language using what I have learned so far.

# Details of the Transliteration System
The system has the following properties:
- only uses letter characters from Maltese
- only uses punctuation characters from Maltese, and one punctuation character from Catalan.

The system has the following differences from Maltese orthography:
- slashed h can no longer occur alone, ħ -> hħ. It must always occur as one letter of a digraph or trigraph. This is a solution to prevent ambiguous situations with digraphs.
- the addition of digraphs and trigraphs for sounds that exist in Arabic but not in Maltese.
- The use of an apostrophe for digraphs representing certain sounds that exist in Arabic but not in Maltese
