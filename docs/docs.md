---
layout: default
title: Documentation
---

# Dictionary shells

[GoldenDict](http://goldendict.org/) is a free desktop computer dictionary shell. It works on Windows, Linux, and MacOS, and supports great variety of file formats. To the date it is the most functional application for work with dictionaries.

Users of mobile devices could try [Aard2](http://aarddict.org/). Its import tool [xdxf2slob](https://github.com/itkach/xdxf2slob/) correctly recognizes XDXF format. Additional formats for other applications could be produced, but it completely depends on the users requests. Please, [join the discussion](https://github.com/nikita-moor/latin-dictionary/issues/2) or [contact me]({{ site.baseurl }}{% link about.md %}) directly.


# GoldenDict setting up

For adding dictionary to GoldenDict see article ["Quick Start"]({{ site.baseurl }}{% link docs/howto.md %}). It gives enough information for starting using dictionary, but looking for a word you will need to type in its normal form, such as "amo" for "amavistis".

To manage this problem GoldenDict offers automatic words normalization based on Hunspell library. It is not a real lemmatizer, but in most cases suggestions are correct and it greatly simplifies use of the dictionary. See article ["Hunspell"]({{ site.baseurl }}{% link docs/hunspell.md %}) explaining how to setup morphology normalization.

Every application chooses independently how it will render articles of XDXF dictionaries. Users of GoldenDict could customize this process, and we propose our variant improving appearance but also adding new features critical to some dictionaries. Please, read documentation to every dictionary to find the answer do you need to apply this setting or could skip it. Article ["Custom styles"]({{ site.baseurl }}{% link docs/styles.md %}) tells about benefits of this castomization.
