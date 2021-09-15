# CHANGELOG for h-slash-arabic-romanization html Javascript web application


## March 15, 2021
- Created this web application by modifying Code from my previous transliteration web application titled "one apostrophe ...".

## March 16, 2021: version 0.7.0
- Made the repository public on GitHub.
- Improve screen reader accessibility.
- Add the version number: v0.7.0


## August 20, 2021: version 0.8.1
- Fix more transliteration issues
 - specifically errors in transliterating "ssħ ddħ hh" and others
 - this was accomplished using a separator character and chunking
    as part of the transliteration process. The separator character is
	removed at the end of the process.

## September 4, 2021: version 0.8.3
- implement quick apostrophe mode (in cases where a Maltese keyboard layout is not available an apostrophe can be used instead.)
- change transliteration of qaaf to <q> instead of <qħ>.

## September 14, 2021: version 0.9.0
- handle sun and moon letters (Arabic definite article special cases)
 for example ax-xams becomes الشَّمس 
- check the most common checkboxes (by default set to
 romanize text as the user types)
- add style to the legend
- change GUI so that it is easier to see both textboxes at once.
- add placeholder text into textboxes so that it is more obvious what
to do.
- Explain using a few paragraphs what this page is about.

# September 15, 2021: version 1.0
- be able to write any letter with a hamza directly.
  - I needed to do this because I have not implemented the hamza spelling rules,
  - and because I want people to be able to write hamza on the carrier
    letter they choose
    even if they do not want to write the vowels for a word.
- Ensure that dash disappears in transliteration of definite article lacking
assimilation (i.e. with moon letters): i.e.  Arabization of "al-" should 
not include a dash character. 