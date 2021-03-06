## BlackboxNLP 2019

The second edition of the BlackboxNLP workshop will be collocated with [ACL 2019](http://www.acl2019.org/) in Florence. 

There will be a live stream of the workshop [here](https://www.youtube.com/embed/JEH2fiyjrJU).

Archived information about the 2018 edition: [blackboxnlp.github.io/2018](https://blackboxnlp.github.io/2018/).

## Important dates

- ~~April 19~~. Submission deadline (11:59pm Pacific Daylight Savings Time, UTC-7h).
- ~~May 17~~ **~~May 20~~**. Notification of acceptance.
- ~~June 3~~. Camera ready (11:59pm Pacific Daylight Savings Time, UTC-7h).
- August 1. Workshop.

## Proceedings
The proceedings of the workshop can be found in the [ACL Anthology](https://www.aclweb.org/anthology/volumes/W19-48/).

## Workshop program 

A detailed version of the program is available [here](program.md).

| Time         | Program item                                  |
|--------------|-----------------------------------------------|
| 09:00-09:10  | Opening remarks                               |
| 09:10-10:00  | Invited talk 1: [Arianna Bisazza](#arianna-bisazza)|
| 10:00-11:15  | Poster session 1 (10:30-11 tea break)         |
| 11:15-12:30  | Oral presentation session 1 (5 x 15 minutes)  |
| 12:30-14:00  | Lunch                                         |
| 14:00-14:50  | Invited talk 2: [Michael F. Bonner](#michael-f-bonner)|
| 14:50-16:00  | Poster session 2 (15:30-16 tea break)         |
| 16:00-16:45  | Oral presentation session 2 (3 x 15 minutes)  |
| 16:45-17:30  | Panel discussion                              |
| 17:20-17:30  | Best paper announcement and closing remarks   |

**Poster information**: Provided poster boards are 100x250cm (portrait format). 

**Oral presentations** should be 12 minutes long + 3 minutes for questions.

## Travel awards

We will have a limited number of travel awards for students whose papers were accepted for publication in the workshop, thanks to generous support from Microsoft, Google and Facebook. We will prioritize students with limited financial resources (e.g., who work in low-income countries or in graduate programs that are not well-funded). A link to the application website will be made available after acceptance notifications have been sent out. The deadline for applications ~~is May 27~~ has passed. 

## Invited speakers

### [Arianna Bisazza](http://liacs.leidenuniv.nl/~bisazzaa/)
<img src="http://liacs.leidenuniv.nl/~bisazzaa/fig/arianna-utrecht.jpeg" width="100px">

Bio: Arianna Bisazza is an Assistant Professor in natural language processing at Leiden University, Netherlands. 
Her research aims at identifying intrinsic limitations of current language modeling paradigms as well as improving the quality of machine translation for challenging language pairs.
She previously worked as a postdoc at the University of Amsterdam and as a research assistant at Fondazione Bruno Kessler. 
She obtained her PhD from the University of Trento, Italy, in 2013 and was awarded an NWO VENI grant in 2016.

**Understanding syntactic transfer in multilingual NLP models**

Recent work has shown that state-of-the-art models of language and translation can be successfully trained on multiple languages simultaneously without changes to the underlying neural network architectures. Besides the practical advantage of having fewer models to maintain, this approach has the potential to dramatically improve the quality of many NLP applications in low-resource languages by exploiting cross-linguistic commonalities.
As a result the adoption of multilingual models is quickly catching on, however the mechanisms explaining knowledge sharing in these models remain largely unknown:
What kind of knowledge is really shared among languages? Does multilingual training mostly lead to better semantic modeling of the lexicon or does it also enable the sharing of more abstract grammatical categories? And furthermore, what are the conditions for cross-lingual syntactic transfer to happen at various levels?
This talk will present some answers to these questions based on various models and probing tasks, and discuss the future of multilinguality in NLP.



### [Michael F. Bonner](http://michaelfbonner.com/)
<img src="https://static1.squarespace.com/static/511abe2be4b0343281bc20c2/t/51b80116e4b0168c35d8527e/1526055235721/IMGP1331.JPG?format=300w" width="100px">

Bio: Michael F. Bonner is an Assistant Professor in the Department of Cognitive Science at Johns Hopkins University. His lab investigates the cognitive and computational neuroscience of natural vision and memory using methods from neuroimaging, computer vision, and natural language processing.

**Cortical mechanisms of natural scene perception**
 
 Our everyday behaviors rely on visual information in many ways: we must identify people, places, and objects, determine the actions afforded by our surroundings, and relate our perceptual environment to memories and plans. Understanding how the human brain processes the behaviorally relevant properties of the visual environment requires an integrative approach for combining biological investigations with theories of visual computation and statistical models of visual information. We used this approach to understand the mechanisms by which visual cortex processes two central aspects of natural scenes: navigational affordances—that is, where we can navigate in a scene, and where our movement is blocked—and object context—that is, the statistical regularities of object co-occurrence in the visual world. Using fMRI and computational modeling, we discovered a mechanism in visual cortex that automatically represents the navigational affordances of scenes, even in the absence of explicit navigational planning, and we determined that these representations could be extracted through a small set of purely feedforward computations in a biologically inspired convolutional neural network. By probing this computational model, we identified classes of visual inputs and a set of mid-level visual features that appear to be critical for the coding of navigational affordances. In a separate line of work, we combined fMRI with models of distributional semantics to find that the sensory coding of visual objects reflects the statistical structure of object co-occurrence in the natural environment, providing probabilistic information about the contexts in which objects are typically encountered. Together, this work demonstrates an approach for merging neurobiological and computational theories to yield insights at multiple levels of explanation and to move us toward a more comprehensive functional description of the human visual system.

## Description

Neural networks have rapidly become a central component in NLP systems in
the last few years. The improvement in accuracy and performance brought by
the introduction of neural networks has typically come at the cost of our
understanding of the system: How do we assess what the representations and
computations are that the network learns? The goal of this workshop is to
bring together people who are attempting to peek inside the neural network
black box, taking inspiration from machine learning, psychology,
linguistics, and neuroscience. The topics of the workshop will include, but
are not limited to:

- Applying analysis techniques from neuroscience to analyze
high-dimensional vector representations (such as Haxby et al., 2001;
Kriegeskorte, 2008) in artificial neural networks;
- Analyzing the network's response to strategically chosen inputs in order
to infer the linguistic generalizations that the network has acquired
(e.g., Linzen et al., 2016; Loula et al., 2018);
- Examining the performance of the network on simplified or formal
languages (e.g., Hupkes et al., 2018; Lake et al., 2018);
- Proposing modifications to neural network architectures that can make
them more interpretable (e.g., Palanki et al., 2017);
- Scaling up neural network analysis techniques developed in the
connectionist literature in the 1990s (Elman, 1991);
- Testing whether interpretable information can be decoded from
intermediate representations (e.g., Adi et al.,  2017; Chrupala et al.,
2017; Hupkes et al., 2017);
- Translating insights on neural networks interpretation from the vision
domain (e.g., Zeiler & Fergus, 2014) to language;
- Explaining model predictions (e.g., Lei et al., 2016; Alvarez-Melis &
Jaakkola, 2017): What are ways to explain specific decisions made by neural
networks?
- Adversarial examples in NLP (e.g., Ebrahimi et al., 2018; Belinkov &
Bisk, 2018): How to generate them and how to evaluate their quality?
- Open-source tools for analyzing neural networks in NLP (e.g., Strobelt et
al., 2018; Rikters, 2018).
- Evaluation of analysis results: How do we know that the analysis is
valid?

BlackboxNLP 2019 is the second BlackboxNLP workshop. The programme and
proceedings of the previous edition, which was held at EMNLP 2018, can be
found [here](https://blackboxnlp.github.io/2018/).


## Submission

We accept two types of papers

- Archival papers. These are papers reporting on completed, original and
unpublished research, with maximum length of 8 pages + references. Papers
shorter than this maximum are also welcome. An optional appendix may appear after the references in the same pdf file. Accepted papers are expected to
be presented at the workshop and will be published in the workshop
proceedings. They should report on obtained results rather than intended
work. These papers will undergo double-blind peer-review, and should thus
be anonymized. Archival papers will be included in the workshop proceedings 
and the ACL anthology.

- Extended abstracts. These may report on work in progress or may be cross
submissions that have already appeared in a non-NLP venue. The extended
abstracts are of maximum 2 pages + references. These submissions are
non-archival in order to allow submission to another venue. The selection
will not be based on a double-blind review and thus submissions of this
type need not be anonymized. Abstracts will be posted on the workshop website
but will not be included in the proceedings.

Both papers and abstracts should follow the official ACL 2019 style guidelines and should be submitted via softconf:

[https://www.softconf.com/acl2019/blackboxnlp](https://www.softconf.com/acl2019/blackboxnlp)

Accepted submissions will be presented at the workshop: most as posters, some as oral presentations (determined by the program committee).

### Dual submissions
Dual submissions of archival papers with other venues are allowed. Please let us know as soon as possible if 
you decide to withdraw a paper accepted elsewhere. Also please consider that dual submissions increase reviewing burden 
for the whole community.

### Preprints
Papers posted to preprint servers such as arxiv can be submitted without any restrictions on when they were posted.



## Organizers

### Tal Linzen
Tal Linzen (tal.linzen@jhu.edu) is an Assistant Professor of Cognitive Science at Johns Hopkins University. He develops computational cognitive models of language. In addition to his work in psycholinguistics and cognitive neuroscience, he has studied the syntactic capabilities of contemporary artificial neural networks and the linguistic information encoded in word embeddings, in work that has appeared in TACL, EACL and CoNLL. He has co-organized the first edition of BlackboxNLP, and has also organized two editions of the workshop on Cognitive Modeling and Computational Linguistics, co-located with EACL 2017 and with SCiL 2018.

### Grzegorz Chrupała
Grzegorz Chrupała (g.chrupala@uvt.nl) is an Assistant Professor at the Department of Cognitive Science and Artificial Intelligence at Tilburg University. His research focuses on computational models of language learning from multimodal signals such as speech and vision and on the analysis and interpretability of representations emerging in
multilayer neural networks. His work has appeared in venues such as *Computational Linguistics*, ACL, EMNLP and CoNLL. He has served as area chair for ACL, EMNLP and CoNLL and he co-organized the first edition of BlackboxNLP.

### Yonatan Belinkov
Yonatan Belinkov (belinkov@seas.harvard.edu) is a Postdoctoral Fellow at the Harvard School of Engineering and Applied Sciences (SEAS) and the MIT Computer Science and Artificial Intelligence Laboratory (CSAIL). 
His recent research focuses on representations of language in neural network models, with applications in machine translation and speech recognition. 
His research has been published at ACL, EMNLP, TACL, ICLR, and NeurIPS. 
His PhD dissertation at MIT analyzed internal language representations in deep learning models. 

### Dieuwke Hupkes
Dieuwke Hupkes (d.hupkes@uva.nl) is a PhD student at the University of Amsterdam.
The main focus of her research is understanding how recurrent neural networks can understand and learn the structures that occur in natural language.
Developing methods to interpret and interact with neural networks has therefore been an important area of focus in her research.
She authored 5 articles directly relevant to the workshop, one of them published in a top AI journal (Journal of Artificial Intelligence), and she is co-organizing a workshop on compositionality, neural networks, and the brain to be held at the Lorentz Center in the summer of 2019.


## Program committee

 - 	Samira Abnar 
 - 	Željko Agić 
 - 	Afra Alishahi 
 - 	Antonios Anastasopoulos 
 - 	Niranjan Balasubramanian 
 - 	Joost Bastings 
 - 	Lisa Beinborn 
 - 	Laurent Besacier 
 - 	Or Biran 
 - 	Samuel R. Bowman 
 - 	Stergios Chatzikyriakidis 
 - 	Miryam de Lhoneux 
 - 	Ewan Dunbar 
 - 	Jacob Eisenstein 
 - 	Allyson Ettinger 
 - 	Antske Fokkens 
 - 	Robert Frank 
 - 	Richard Futrell 
 - 	Sharon Goldwater 
 - 	Kristina Gulordava 
 - 	David Harwath 
 - 	Germán Kruszewski 
 - 	Yair Lakretz 
 - 	Shalom Lappin 
 - 	Jindřich Libovický 
 - 	Nelson F. Liu 
 - 	Pranava Madhyastha 
 - 	David Mareček 
 - 	Paola Merlo 
 - 	Raymond Mooney 
 - 	Sebastian Padó 
 - 	Yves Peirsman 
 - 	Adam Poliak 
 - 	Rudolf Rosa 
 - 	Carolyn Rose 
 - 	Hassan Sajjad 
 - 	Wojciech Samek 
 - 	Naomi Saphra 
 - 	Rico Sennrich 
 - 	Pia Sommerauer 
 - 	György Szaszák 
 - 	Francesca Toni 
 - 	Adina Williams 
 - 	Roberto Zamparelli 
 - 	Fabio Massimo Zanzotto 
 - 	Willem Zuidema 


## Sponsors

<img src="GoogleLogo_Color.png" width="200px">
<br clear="all" />

<img src="Facebook-06-2015-Blue-on-White.png" width="250px">
<br clear="all" />

<a href="https://www.microsoft.com/en-us/research"><img src="MSFT_logo_rgb_C-Gray.png" width="300px"></a>

## Anti-Harassment Policy
BlackboxNLP 2019 adheres to the [ACL Anti-Harassment Policy](https://www.aclweb.org/adminwiki/sphp?title=Anti-Harassment_Policy).
