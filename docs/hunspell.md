---
layout: default
title: Documentation
---

# Hunspell: words normalization

Latin is an inflected language, so a word could have several forms but dictionaries usually contain only its normal form, such as nominative singular for nouns. For this reason, one cannot simply copy an unknown word into GoldenDict, but need to manually type its correct form.

Hunspell is a spell checking system, also able to produce lemmas, i.e. normal forms of the words, so, for example, word "puellam" will be transformed to "puella", which significantly simplifies work with dictionaries.

Other examples of normalization are ligatures, "pæne" > "paene", and diacritics, "curâ" or "malè". Hunspell produces several permutations of the original word to handle variate spelling, so suggestion for the word "coelum" will include "caelum".

Hunspell by itself needs a dictionary. To the date we could choose between two variants:

1. Dictionary by [Karl Zeiler and Jean-Pierre Sutto][1]
1. Dictionary by [Konrad Kokoszkiewicz][2] (at the very bottom of the page)

The first dicitonary is the most universal, the second contains strictly classical lexicon (to the end of 2nd century AD). Both dictionaries are indifferent to the spelling:

> such spellings as "uua", "uva", "vua" and "vva" are all accepted.

Each dictionary would work fine with GoldenDict. Additionally, they could be used for spellchecking in Libre Office, Chrome, Firefox, &c.


# Installing Hunspell dictionaries

**Note:** Users of Linux could install Hunspell dictionaries as ordinal applications (see Software Center of something alike). For example Arch Linux provides a package with dictionary created by Karl Zeiler and Jean-Pierre Sutto. Then follow the step 3 in the list below, or start from beginning if your distributive has no Hunspell dictionary for Latin language.

Procedure is simple:

1. Download one of the dictionaries. File with extension "oxt" in fact is a zip-archive, rename it to "dict.zip" and extract. Required files "la.aff" and "la.dic" are located in the folder "la/universal".
1. Save these two files to the documents on your computer.
1. Start GoldenDict and open menu Edit > Dictionaries, tab Sources > Morphology.
1. Change "Path to a directory with Hunspell/Myspell dictionaries" to the folder where you saved the dictionary. (**Linux:** if you installed dictionary as package, then the correct path will be "/usr/share/hunspell".)
1. Enable (check on) "Latin Morphology" in the list.
1. Press OK. Try typing an incorrect word, you should see the list of spelling suggestions (see image).
1. If not, open settings (Edit > Dictionaries), and on the tab Groups add "Latin Morphology" to the group.

{% include img-preview.html img="img/hunspell-1.png" %}


[1]: https://extensions.libreoffice.org/extensions/latin-spelling-and-hyphenation-dictionaries
[2]: http://www.obta.uw.edu.pl/~draco/

