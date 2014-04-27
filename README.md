Cosmotheoros
============

*"The Celestial Worlds discover'd: Or, Conjectures concerning the inhabitants, plants and productions of the worlds in the planets"*


This repository holds the finished PDF and source files for my typeset version of Christiaan Huygens' scientific and philosophical work, which he finished shortly before his death and was published posthumously.

I have found the text and images at the web page of [R.H. van Gent], cleaned the figures a bit in [Gimp], and typeset the text with XeLaTeX and the great `fontspec` package. 

I have used the image of the Latin version of the book found on R.H. van Gents site as the cover, and typeset a version based on pictures of the original English version as the title page. 

![Front of the original Latin version, from R.H. van Gents page](Images/ct_title_sm_la.jpg)

*Front of the original Latin version, from R.H. van Gents page.*

If you don't care about all the background stuff, here is a direct [download] link.


## About the book

Christiaan Huygens, who is perhaps most well known for his work in optics and wave theory of lights, was also an avid astronomer and thinker. In this book, he speculates about the possibility of finding life on other planets in our Solar System and even around other stars. But he goes further than that: He imagines what that life could and could not look like, how astronomical circumstances like e.g. the rings of Saturn or the dimness of the sun in the outer Solar System, would affect life on such world and make their inhabitants adapt. While stressing that Life on such alien worlds would probably not look like any beings on Earth, he also speculates that the differences cannot be *too* deep, as our anatomy helps us with functions that seem necessary to develop and exercise intelligence.

It is generally a very visionary and surprisingly clear/sighted book, although it also carries some quite heavy signs of its time. A time for which it was also a very bold book to publish, which probably was one of the reasons he didn't write down these thoughts until very old age, and yet found it necessary to forego the expected criticism from religious dogmatics on the first pages. More on the [Wikipedia entry] and van Gents page.




![Title page from original English version](Images/title_page.jpg)


## Fonts and typesetting

I have spent some time looking around for good fonts to emulate the old-style Latin letters of the late 17th century, when I stumbled onto the fantastic [Fell Type] fonts designed by Igino Marini, which do just that: Emulate typical typefaces and print quality of that era. They are high-quality fonts with great support for OpenType features like historical style, different ligature sets etc. - I think it looks pretty good with these fonts. The fonts do not have a **bold** version, but this was not generally used at the time. This book uses the 'IM Fell English PRO' font. Best of all: They are free and open source!

The use of the 'Long s'  (ſ) character follows the rules listed at the [Babelstone] blog for 17th century books. XeLaTeX has some support for simple rules, but as is described in the Babelstone blog post, these rules (basically: Short 's' at the end of words, long 'ſ' at the beginning and inside of words) are somewhat over/simplified and inaccurate.


[Download]: ./cosmotheoros.pdf
[R.H. van Gent]: http://www.staff.science.uu.nl/~gent0113/huygens/huygens_ct_en.htm
[Gimp]: http://www.gimp.org
[Fell Type]: http://iginomarini.com/fell/the-revival-fonts/
[Babelstone]: http://babelstone.blogspot.se/2006/06/rules-for-long-s.html
[Wikipedia entry]: http://en.wikipedia.org/wiki/Christiaan_Huygens#Cosmotheoros
