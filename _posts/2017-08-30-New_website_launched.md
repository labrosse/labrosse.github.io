---
layout: single
title: "Just started a new website..."
date: 2017-08-30
---

I got a bit fed up with my old website using a CMS, which is a bit
annoying to maintain. I thought I would give a try to
[Jekyll](http://jekyllrb.com), use Markdown for all pages and
posts. I used the
[Minimal mistakes](https://mmistakes.github.io/minimal-mistakes/),
which seems like a good way to go ;-). 
The bibliography is converted automatically to html from bib
using [bibtex2html](https://www.lri.fr/~filliatr/bibtex2html/) with:
```
bibtex2html -d -r --revkeys --both --html-entities --nobibsource --nodoc  -s myplain mybib.bib
```

This uses ```myplain.bst``` as style file for bibtex, a slight
modification of the standard ```plain.bst``` to have all names as
```Lastname, F.```. You can get the file [here](/assets/files/myplain.bst).

In order for the abstracts link to work, I modify the html file as
```
sed -i -e "s/mybib_abstracts.html/\/publications_abstracts\//g" mybib.html
```

I am not sure I will keep up with the blogging thing but at least to
make static pages, this is simple enough! Nothing too fancy here but
you should find the minimum info.

