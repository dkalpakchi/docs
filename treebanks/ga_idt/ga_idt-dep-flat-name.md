---
layout: base
title:  'Statistics of flat:name in UD_Irish-IDT'
udver: '2'
---

## Treebank Statistics: UD_Irish-IDT: Relations: `flat:name`

This relation is a language-specific subtype of <tt><a href="ga_idt-dep-flat.html">flat</a></tt>.
There are also 1 other language-specific subtypes of `flat`: <tt><a href="ga_idt-dep-flat-foreign.html">flat:foreign</a></tt>.

771 nodes (1%) are attached to their parents as `flat:name`.

771 instances of `flat:name` (100%) are left-to-right (parent precedes child).
Average distance between parent and child is 1.38261997405966.

The following 16 pairs of parts of speech are connected with `flat:name`: <tt><a href="ga_idt-pos-PROPN.html">PROPN</a></tt>-<tt><a href="ga_idt-pos-PROPN.html">PROPN</a></tt> (479; 62% instances), <tt><a href="ga_idt-pos-PROPN.html">PROPN</a></tt>-<tt><a href="ga_idt-pos-PART.html">PART</a></tt> (164; 21% instances), <tt><a href="ga_idt-pos-NOUN.html">NOUN</a></tt>-<tt><a href="ga_idt-pos-PROPN.html">PROPN</a></tt> (44; 6% instances), <tt><a href="ga_idt-pos-PART.html">PART</a></tt>-<tt><a href="ga_idt-pos-PROPN.html">PROPN</a></tt> (35; 5% instances), <tt><a href="ga_idt-pos-NOUN.html">NOUN</a></tt>-<tt><a href="ga_idt-pos-PART.html">PART</a></tt> (21; 3% instances), <tt><a href="ga_idt-pos-PROPN.html">PROPN</a></tt>-<tt><a href="ga_idt-pos-ADJ.html">ADJ</a></tt> (7; 1% instances), <tt><a href="ga_idt-pos-NOUN.html">NOUN</a></tt>-<tt><a href="ga_idt-pos-NOUN.html">NOUN</a></tt> (6; 1% instances), <tt><a href="ga_idt-pos-PROPN.html">PROPN</a></tt>-<tt><a href="ga_idt-pos-DET.html">DET</a></tt> (3; 0% instances), <tt><a href="ga_idt-pos-PROPN.html">PROPN</a></tt>-<tt><a href="ga_idt-pos-NOUN.html">NOUN</a></tt> (3; 0% instances), <tt><a href="ga_idt-pos-ADP.html">ADP</a></tt>-<tt><a href="ga_idt-pos-NOUN.html">NOUN</a></tt> (2; 0% instances), <tt><a href="ga_idt-pos-PROPN.html">PROPN</a></tt>-<tt><a href="ga_idt-pos-NUM.html">NUM</a></tt> (2; 0% instances), <tt><a href="ga_idt-pos-ADP.html">ADP</a></tt>-<tt><a href="ga_idt-pos-CCONJ.html">CCONJ</a></tt> (1; 0% instances), <tt><a href="ga_idt-pos-PROPN.html">PROPN</a></tt>-<tt><a href="ga_idt-pos-ADP.html">ADP</a></tt> (1; 0% instances), <tt><a href="ga_idt-pos-PROPN.html">PROPN</a></tt>-<tt><a href="ga_idt-pos-PRON.html">PRON</a></tt> (1; 0% instances), <tt><a href="ga_idt-pos-VERB.html">VERB</a></tt>-<tt><a href="ga_idt-pos-PART.html">PART</a></tt> (1; 0% instances), <tt><a href="ga_idt-pos-X.html">X</a></tt>-<tt><a href="ga_idt-pos-X.html">X</a></tt> (1; 0% instances).


~~~ conllu
# visual-style 3	bgColor:blue
# visual-style 3	fgColor:white
# visual-style 2	bgColor:blue
# visual-style 2	fgColor:white
# visual-style 2 3 flat:name	color:blue
1	Thuig	tuig	VERB	VTI	Form=Len|Mood=Ind|Tense=Past	0	root	_	_
2	Mary	Mary	PROPN	Noun	Gender=Fem|Number=Sing	1	nsubj	_	_
3	Harney	Harney	PROPN	Noun	Gender=Masc|Number=Sing	2	flat:name	_	_
4	é	é	PRON	Pers	Gender=Masc|Number=Sing|Person=3	1	obj	_	_
5	seo	seo	PRON	Dem	PronType=Dem	2	det	_	_
6	go	go	PART	Ad	PartType=Ad	7	mark:prt	_	_
7	breá	breá	ADJ	Adj	Degree=Pos	1	advmod	_	SpaceAfter=No
8	,	,	PUNCT	Punct	_	9	punct	_	_
9	agus	agus	CCONJ	Coord	_	10	cc	_	_
10	Charlie	Charlie	PROPN	Noun	Gender=Masc|Number=Sing	2	conj	_	_
11	McCreevy	McCreevy	PROPN	Noun	Gender=Masc|Number=Sing	10	flat:name	_	SpaceAfter=No
12	.	.	PUNCT	.	_	1	punct	_	_

~~~


~~~ conllu
# visual-style 4	bgColor:blue
# visual-style 4	fgColor:white
# visual-style 3	bgColor:blue
# visual-style 3	fgColor:white
# visual-style 3 4 flat:name	color:blue
1	Grianghraif	grianghraf	NOUN	Noun	Case=NomAcc|Gender=Masc|Number=Plur	0	root	_	_
2	le	le	ADP	Simp	_	3	case	_	_
3	Maidhc	Maidhc	PROPN	Noun	Case=NomAcc|Gender=Masc|Number=Sing	1	nmod	_	_
4	Ó	ó	PART	Pat	PartType=Pat	3	flat:name	_	_
5	Seachnasaí	seachnasaí	PROPN	Noun	Case=NomAcc|Gender=Masc|Number=Sing	3	flat:name	_	SpaceAfter=No
6	.	.	PUNCT	.	_	1	punct	_	_

~~~


~~~ conllu
# visual-style 5	bgColor:blue
# visual-style 5	fgColor:white
# visual-style 4	bgColor:blue
# visual-style 4	fgColor:white
# visual-style 4 5 flat:name	color:blue
1	Tháinig	tar	VERB	VI	Form=Len|Mood=Ind|Tense=Past	0	root	_	_
2	sé	sé	PRON	Pers	Gender=Masc|Number=Sing|Person=3	1	nsubj	_	_
3	ar	ar	ADP	Simp	_	4	case	_	_
4	Rí	rí	NOUN	Noun	Case=NomAcc|Gender=Masc|Number=Sing	1	obl	_	_
5	Laighin	Laighin	PROPN	Noun	Case=Gen|Gender=Fem|Number=Sing	4	flat:name	_	_
6	ar	ar	ADP	Simp	_	7	case	_	_
7	Tountinna	Tountinna	PROPN	Noun	Case=NomAcc|Gender=Masc|Number=Sing	1	obl	_	SpaceAfter=No
8	.	.	PUNCT	.	_	1	punct	_	_

~~~


