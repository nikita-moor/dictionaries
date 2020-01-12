---
title: Victionarium Latinum
author: Wikimedia Foundation
year: 2020
tags: [Latin, Latin]
nickname: Victionarium
categories: [latin]
---
# {{ page.title }}, {{ page.author }} ({{ page.year }})

Snapshot of Latin Wiktionary (Victionarium) project for date 2020-01-01 transformed into a Latin-Latin dictionary, so other sections of the articles, such as Etymology or Translations, were omitted.


## Download

Current version is [v1.0 (January 12, 2020)][1]. Format Slob is recommended for GoldenDict, read [documentation][2] about other dictionary shells.


## Exemplum

{% include img-viewer.html img="img/Victionarium-1.png" id="1" %}
{% include img-viewer.html img="img/Victionarium-2.png" id="2" %}


# Sources

1. _Latin-language Wiktionary (Victionarium)._ Retrieved January 1, 2020, from <https://dumps.wikimedia.org/lawiktionary/20200101/>.


# States and limitations

Dictionary contains only definitions of the words, links to Latin-language Wikipedia, and images. Etymology (Notatio) sections were parsed (see [github repository][3]), but we found them not useful and did not include into the final edition. Sections _Formae alia_, _Synonyma_, _Dictiones collatae_, and similar seem interesting and may be included into the following releases.

Images were reduced to 512 px to make the file of reasonable size.

Sign "√" marks main definitions of the words, see [Victionarium][4] for other symbols and abbreviations.


## License

<a rel="license" href="https://creativecommons.org/licenses/by-sa/3.0/">
<img alt="Creative Commons License"
     style="border-width:0"
     src="https://i.creativecommons.org/l/by-sa/3.0/88x31.png" />
</a>

<!-- <a rel="license" href="https://www.gnu.org/licenses/fdl-1.3.html">
<img alt="GNU Free Documentation License"
     style="border-width:0"
     src="http://www.gnu.org/graphics/gfdl-logo-tiny.png" />
</a> -->

This work is licensed under a <a rel="license" href="https://creativecommons.org/licenses/by-sa/3.0/">Creative Commons Attribution-ShareAlike 3.0 Unported License</a> and <a rel="license" href="https://www.gnu.org/licenses/fdl-1.3.html">GNU Free Documentation License (GFDL)</a>. License terms of each article, its text and included media files, could differ from general license.


[1]: https://github.com/nikita-moor/latin-dictionary/releases/tag/2020-01-06
[2]: {{ site.baseurl }}{% link docs/docs.md %}
[3]: https://github.com/nikita-moor/latin-dictionary/tree/master/{{ page.nickname }}
[4]: https://la.wiktionary.org/wiki/Auxilium:Abbreviationes

