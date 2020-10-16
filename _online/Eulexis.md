---
title: Eulexis
description: morphological analyzer, dictionary
website: https://outils.biblissima.fr/en/eulexis/index.php
categories: [greek]
---
# {{ page.title }}

[{{ page.title }}]({{ page.website }}) is a lemmatiser for **Ancient Greek** texts. Our adaptaion contains lemmatization, morphological analyzing, and short English definitions (one-two words). 


## Download

Current version is [v1.0 (October 16, 2020)][2].


## Exemplum

{% include img-viewer.html img="img/Eulexis-1.png" id="1" %}
{% include img-viewer.html img="img/Eulexis-2.png" id="2" %}


## States and limitations

Comparing to [Alpheios][3], this dictionary is more compliant, it will suggest several forms differing only in tones or breathing marks, but may not be able to recognize some declensions or conjugations. Also, Greek words can be typed in transliteration:


```
αβγδεζηθικλμνξοπρςστυφχψωϝϟ
abgdezhqiklmncoprsstufxywfk
```


## How to setup

1. Download the most recent version of the dictionary (file "Eulexis-html.zip") and extract archive.
1. In GoldenDict, open menu Edit > Dictionaries.
1. Switch to the tab Websites.
1. Press button "Add…" and fill values of the new item:
  - enabled: ☑ (on);
  - as link: ☑ (on);
  - name: on your choice (does not matter);
  - address: `file:///C:/Users/user/Documents/Eulexis-html/index.html` (adapt it to the real path to "index.html"; it should start with 'file:///'; use "forward" slashs instead of backslash).


## License

<a rel="license" href="http://creativecommons.org/publicdomain/mark/1.0/">
<img src="https://licensebuttons.net/p/mark/1.0/88x31.png"
     style="border-style: none;" alt="Public Domain Mark" />
</a>


[1]: https://github.com/nikita-moor/latin-dictionary/tree/master/{{ page.nickname }}
[2]: https://github.com/nikita-moor/latin-dictionary/releases/tag/2020-10-16
[3]: {{ site.baseurl }}{% link _online/Alpheios.md %}
