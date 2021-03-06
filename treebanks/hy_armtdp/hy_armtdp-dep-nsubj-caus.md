---
layout: base
title:  'Statistics of nsubj:caus in UD_Armenian-ArmTDP'
udver: '2'
---

## Treebank Statistics: UD_Armenian-ArmTDP: Relations: `nsubj:caus`

This relation is a language-specific subtype of <tt><a href="hy_armtdp-dep-nsubj.html">nsubj</a></tt>.
There are also 1 other language-specific subtypes of `nsubj`: <tt><a href="hy_armtdp-dep-nsubj-pass.html">nsubj:pass</a></tt>.

2 nodes (0%) are attached to their parents as `nsubj:caus`.

1 instances of `nsubj:caus` (50%) are left-to-right (parent precedes child).
Average distance between parent and child is 5.5.

The following 2 pairs of parts of speech are connected with `nsubj:caus`: <tt><a href="hy_armtdp-pos-VERB.html">VERB</a></tt>-<tt><a href="hy_armtdp-pos-NOUN.html">NOUN</a></tt> (1; 50% instances), <tt><a href="hy_armtdp-pos-VERB.html">VERB</a></tt>-<tt><a href="hy_armtdp-pos-PROPN.html">PROPN</a></tt> (1; 50% instances).


~~~ conllu
# visual-style 4	bgColor:blue
# visual-style 4	fgColor:white
# visual-style 3	bgColor:blue
# visual-style 3	fgColor:white
# visual-style 3 4 nsubj:caus	color:blue
1	Այդպես	այդպես	ADV	_	Distance=Med|PronType=Dem	3	advmod	_	_
2	է	եմ	AUX	_	Aspect=Imp|Mood=Ind|Number=Sing|Person=3|Polarity=Pos|Tense=Pres|VerbForm=Fin	3	aux	_	_
3	սովորեցրել	սովորել	VERB	_	Aspect=Perf|Subcat=Tran|VerbForm=Part|Voice=Cau	0	root	_	_
4	պապս	պապ	NOUN	_	Animacy=Hum|Case=Nom|Number=Sing|Number[psor]=Sing|Person[psor]=1	3	nsubj:caus	_	SpaceAfter=No
5	։	։	PUNCT	_	_	3	punct	_	_

~~~


~~~ conllu
# visual-style 13	bgColor:blue
# visual-style 13	fgColor:white
# visual-style 23	bgColor:blue
# visual-style 23	fgColor:white
# visual-style 23 13 nsubj:caus	color:blue
1	Կանանցից	կին	NOUN	_	Animacy=Hum|Case=Abl|Definite=Ind|Number=Plur	2	nmod	_	_
2	երկուսը	երկուս	NOUN	_	Animacy=Hum|Case=Nom|Definite=Def|Number=Sing	7	nsubj	_	_
3	նրա	նա	DET	_	Case=Gen|Number=Sing|Person=3|Poss=Yes|PronType=Prs	4	det:poss	_	_
4	թևերն	թև	NOUN	_	Animacy=Inan|Case=Nom|Definite=Def|Number=Plur	5	obl	_	_
5	ընկած	ընկնել	VERB	_	Aspect=Perf|Polarity=Pos|Subcat=Intr|VerbForm=Part|Voice=Mid	7	advcl	_	_
6	քռքաշ	քռքաշ	ADV	_	Style=Vrnc	7	advmod	_	_
7	տարան	տանել	VERB	_	Aspect=Perf|Mood=Ind|Number=Plur|Person=3|Polarity=Pos|Subcat=Tran|Tense=Past|VerbForm=Fin|Voice=Act	0	root	_	_
8	տուն	տուն	NOUN	_	Animacy=Inan|Case=Nom|Definite=Ind|Number=Sing	7	obl	_	SpaceAfter=No
9	,	,	PUNCT	_	_	13	punct	_	_
10	իսկ	իսկ	CCONJ	_	_	13	advmod:emph	_	_
11	պատշարի	պատշար	NOUN	_	Animacy=Hum|Case=Dat|Definite=Ind|Number=Sing	12	nmod:poss	_	_
12	կնիկ	կնիկ	NOUN	_	Animacy=Hum|Case=Nom|Definite=Ind|Number=Sing	13	nmod	_	_
13	Բավականը	Բավական	PROPN	_	Animacy=Hum|Case=Nom|Definite=Def|NameType=Giv|Number=Sing	23	nsubj:caus	_	_
14	մի	մի	DET	_	PronType=Art	15	det	_	_
15	քանիսին	քանիսը	PRON	_	Case=Dat|Definite=Def|Number=Sing|PronType=Ind	23	iobj:agent	_	SpaceAfter=No
16	,	,	PUNCT	_	_	20	punct	_	_
17	այդ	այդ	DET	_	Distance=Med|PronType=Dem	18	det	_	_
18	թվում	թիվ	NOUN	_	Animacy=Inan|Case=Loc|Definite=Ind|Number=Sing	20	nmod:npmod	_	_
19	և	և	CCONJ	_	_	20	advmod:emph	_	_
20	Սաթոյին	Սաթո	PROPN	_	Animacy=Hum|Case=Dat|Definite=Def|NameType=Giv|Number=Sing	15	appos	_	SpaceAfter=No
21	,	,	PUNCT	_	_	23	punct	_	_
22	աչքունքով	աչքունք	NOUN	_	Animacy=Inan|Case=Ins|Definite=Ind|Number=Sing	23	obl	_	_
23	հասկացրեց	հասկանալ	VERB	_	Aspect=Perf|Mood=Ind|Number=Sing|Person=3|Polarity=Pos|Subcat=Tran|Tense=Past|VerbForm=Fin|Voice=Cau	7	conj	_	SpaceAfter=No
24	,	,	PUNCT	_	_	28	punct	_	_
25	որ	որ	SCONJ	_	_	28	mark	_	_
26	իր	ինքը	DET	_	Case=Gen|Number=Sing|Person=3|Poss=Yes|PronType=Emp|Reflex=Yes	27	det:poss	_	_
27	հետևից	հետև	NOUN	_	Animacy=Inan|Case=Abl|Definite=Ind|Number=Sing	28	obl	_	_
28	գնան	գնալ	VERB	_	Aspect=Prosp|Mood=Sub|Number=Plur|Person=3|Polarity=Pos|Subcat=Intr|Tense=Pres|VerbForm=Fin|Voice=Mid	23	ccomp	_	SpaceAfter=No
29	։	։	PUNCT	_	_	7	punct	_	_

~~~


