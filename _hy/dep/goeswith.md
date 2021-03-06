---
layout: relation
title: 'goeswith'
shortdef: 'goes with'
udver: '2'
---

This relation links two or more parts of a word that are separated in text that is not well edited.
These parts should be written together as one word according to the ortographic rules of Armenian.
The head is the first or in some sense the _main_ part, the other parts are attached to it with the `goeswith` relation (for consistency, similarly as in [flat](), [fixed]() and [conj]()).
Note that only the last part may be annotated with `SpaceAfter=No`.

~~~ sdparse
նա ի զուր էր այդքան անհանգստանում
goeswith(ի, զուր)
~~~

~~~ sdparse
կարգ ու կանոն հաստատել
goeswith(կարգ, ու)
goeswith(կարգ, կանոն)
~~~

Note that we also use this relation to link the inflectional bound morphemes that are separated due to tokenization to the _main_ part of the word (usually the last word of phrases or sentences used as names or after abbreviations).

~~~ sdparse
«/PUNCT Երկիր/NOUN[Animacy=Inan|Case=Nom|Definite=Ind|Number=Sing] Նաիրի/PROPN[Animacy=Inan|Case=Nom|Definite=Ind|NameType=Geo|Number=Sing] »/PUNCT -/PUNCT ից/NOUN[Animacy=Inan|Case=Abl|Definite=Ind|Number=Sing] \n “ Yerkir Nairi ” - from
punct(Նաիրի, «)
punct(Նաիրի, »)
nmod(Նաիրի, Երկիր)
punct(ից, -)
goeswith(Նաիրի, ից)
~~~

~~~ sdparse
1937/NUM[NumForm=Digit|NumType=Card] թ/NOUN[Abbr=Yes|Animacy=Inan|Case=Nom|Definite=Ind|Number=Sing] ./PUNCT -/PUNCT ին/NOUN[Animacy=Inan|Case=Dat|Definite=Ind|Number=Sing] \n in year 1937
nummod(թ, 1937)
punct(թ, .)
punct(ին, -)
goeswith(թ, ին)
~~~

For more details see the [tokenization page](http://universaldependencies.org/hy/tokenization.html).
