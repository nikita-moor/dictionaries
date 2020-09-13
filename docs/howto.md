---
layout: default
title: Documentation
---

# Install GoldenDict

GoldenDict is a computer shell which could read and organize dictionaries of different formats.

* Windows: use [Early Access Builds](https://github.com/goldendict/goldendict/wiki/Early-Access-Builds-for-Windows) and choose Qt 5.12.3-based release (or higher).
* Linux: install the application from your software manager; choose Qt5-based version if there are different variant.
* macOS: use [Early Access Builds](https://github.com/goldendict/goldendict/wiki/Early-Access-Builds-for-Windows), no special requirements.


# Add dictionaries to GoldenDict

In order to use dictionaries from this website you should make few simple steps:

1. Take the most recent version of a dictionary from the [Release](https://github.com/nikita-moor/latin-dictionary/releases) section. Choose files with "zip" extension and ignore "Source code".
1. Downloaded file is an archive which should be extracted. For example, dictionary [Dumesnil1819 v1.1.3](https://github.com/nikita-moor/latin-dictionary/releases/download/release/Dumesnil1819-1.1.3.zip) contains folder "Dumesnil1819". Save the folder on your computer.
1. In GoldenDict, open menu Edit > Dictionaries. 
1. Switch to the tabs Sources > Files (it should be shown by default; see image below).
1. Press button "Add…" and open the folder of the dictionary. Press "OK" to confirm, and you will see how the dictionary is being indexed.
1. Everything is ready and you could start looking for a word, e.g. "amor".

{% include img-viewer.html img="img/goldendict-1.png" %}

**Note:** if you organized dictionaries into groups (menu Edit > Dictionaries, tab Groups), new dictionary will not be added automaticly. So, on the step 4 in place of "OK" press "Apply", then on the tab Groups add new dicitonary into the desired group.


# HTML dictionaries

This type of dictionaries works similar to websites:

1. Follow steps 1-2 from above.
1. In GoldenDict, open menu Edit > Dictionaries.
1. Switch to the tab "Websites".
1. Press button "Add…" and fill values of the new item:
  - enabled: ☑ (on);
  - as link: ☐ (off);
  - name: on your choice (does not matter);
  - address: `file:///c:/Schrevel1831-grc-lat-html/index.html` (adapt it to the real path to the "index.html"; it should start with 'file:///'; use "forward" slashs instead of backslash).


## Updating dictionary

If you are updating an old dictionary, simply replace it with files from new release. Then open menu File > Rescan Files.
