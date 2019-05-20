---
layout: default
title: Documentation
---

# Adding dictionaries to Goldendict

GoldenDict is a computer shell which could read and organize dictionaries of different formats. In order to use dictionaries from this website you should make few simple steps:

1. Take the most recent version of a dictionary from the [Release](https://github.com/nikita-moor/latin-dictionary/releases) section. Choose files with "zip" extension and ignore "Source code" files.
1. Downloaded file is an archive which should be extracted. For example, dictionary [Dumesnil1819 v1.1.3](https://github.com/nikita-moor/latin-dictionary/releases/download/release/Dumesnil1819-1.1.3.zip) contains folder "Dumesnil1819". Save it to the documents or personal collection on your computer.
1. In GoldenDict, open menu Edit > Dictionaries. Required tabs Sources > Files should be shown by default (see image below).
1. Press button "Add…" and open the folder of the dictionary. Press "OK" to confirm, and you will see how the dictionary is being indexed.
1. Everything is ready and you could start looking for a word, e.g. "amor".

{% assign randomId = "now" | date: "%N" | modulo: 1000 %}

<div class="img-viewer">
  <input type="checkbox" id="img-viewer-{{ randomId }}"/>
  <label for="img-viewer-{{ randomId }}">
    <img src="img/goldendict-1.png" width="947" height="557" class="img-viewer-full"/>
    <img src="img/goldendict-1.png" height="200px" alt="preview"/>
  </label>
</div>

**Note:** if you organized dicitonaries into groups (menu Edit > Dictionaries, tab Groups), new dictionary will not be added automaticly. So, on the step 4 in place of "OK" press "Apply", then on the tab Groups add new dicitonary into the desired group.

## Updating dictionary

If you are updating an old dictionary, simply replace it with files from new release. Then open menu Edit > Dictionaries and press button "Rescan now".
