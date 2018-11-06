## Venue

The workshop will be collocated with [EMNLP 2018](http://emnlp2018.org/) in Brussels. 

## Important dates

- July 19. Submission deadline (11:59pm Pacific Daylight Savings Time, UTC-7h).
- August 3. Notification of acceptance.
- August 30. Camera ready (11:59pm Pacific Daylight Savings Time, UTC-7h).
- November 1. Workshop.

## Proceedings

The workshop proceedings are available via ACL Anthology: <a href="https://t.co/yxzNHYbv69">proceedings</a>

## Workshop program


| Time         | Program item                                  |
|--------------|-----------------------------------------------|
| 09:00-09:10  | Opening remarks                               |
| 09:10-10:00  | Invited talk 1: [Yoav Goldberg](index.md#yoav-goldberg)|
| 10:00-11:00  | Poster session 1 (10:30-11 tea break)         |
| 11:00-12:30  |  Oral presentation session 1 (6 x 15 minutes) |
| 12:30-14:00  | Lunch                                         |
| 14:00-14:50  | Invited talk 2: [Graham Neubig](index.md#graham-neubig)|
| 14:50-16:00  | Poster session 2 (15:30-16 tea break)         |
| 16:00-16:50  | Invited talk 3: [Leila Wehbe](index.md#leila-wehbe)|
| 16:50-17:20  |  Oral presentation session 2 (2 x 15 minutes) |
| 17:20-17:30  | Best paper announcement and closing remarks   |


[Detailed program](program.md)

## Information for presenters

The maximal poster size is A0: 84 cm (width) by 118 cm (height), or 33 by 46 inch. Posters should be in *portrait* format.

Contributed talks should be 12 minute long, with 3 minutes for questions.

## Invited Speakers

###  Leila Wehbe  
<img src="http://www.cs.cmu.edu/~lwehbe/pic01.jpg" width="100px"> 

**Language representations in human brains and artificial neural networks**

When studying language in the brain, it has become more common to image the brain of humans while they process naturalistic language stimuli consisting of rich, natural text. To analyse the brain representation of such complex stimuli, vector representations derived from various NLP methods are extremely useful as a model of the information being processed in the brain. The recent deep learning revolution has ignited a lot of interest in using artificial neural networks as a source of high dimensional vector representation for modeling brain processes. However, these representations are hard to interpret and the problem becomes increasingly difficult: how do we study complex brain activity -- a black box we want to understand -- using hard-to-interpret artificial neural network representations -- another black box we want to understand? In this talk, I will summarize the recent effort in modeling the brain processing of language, the use of artificial neural networks in this process, and how inferences about brain processes and about artificial neural network representations can still be made under this setup.

Bio: [Leila Wehbe](http://www.cs.cmu.edu/~lwehbe/) is an assistant professor of Machine Learning at Carnegie Mellon University. Previously, we was a postdoctoral researcher at the Gallant Lab in the Helen Wills Neuroscience Institute at UC Berkeley. She obtained her PhD from the Machine Learning Department and the Center for the Neural Basis of Cognition at Carnegie Mellon University, where she worked with Tom Mitchell. She works on studying language representations in the brain when subjects engage in naturalistic language tasks. Specifically, she combines functional neuroimaging with natural language processing and machine learning tools to build spatiotemporal maps of the information represented in the brain during language processing.

### Graham Neubig
<img src="http://www.phontron.com/images/neubig-headshot-2016-small.jpg" width="100px"> 

**Learning with Latent Linguistic Structure**

<a href="https://t.co/fbAdkyO8jy">Slides</a>

Neural networks provide a powerful tool to model language, but also
depart from standard methods of linguistic representation, which
usually consist of discrete tag, tree, or graph structures. These
structures are useful for a number of reasons: they are more
interpretable, and also can be useful in downstream tasks. In this
talk, I will discuss models that explicitly incorporate these
structures as latent variables, allowing for unsupervised or
semi-supervised discovery of interpretable linguistic structure, with
applications to part-of-speech and morphological tagging, as well as
syntactic and semantic parsing.

Bio: [Graham Neubig](http://www.phontron.com/) is an assistant professor at the Language Technologies Intitute of Carnegie Mellon University. His work focuses on natural language processing, specifically multi-lingual models that work in many different languages, and natural language interfaces that allow humans to communicate with computers in their own language. Much of this work relies on machine learning to create these systems from data, and he is also active in developing methods and algorithms for machine learning over natural language data. He publishes regularly in the top venues in natural language processing, machine learning, and speech, and his work occasionally wins awards such as best papers at EMNLP, EACL, and WNMT. He is also active in developing open-source software, and is the main developer of the DyNet neural network toolkit.

### Yoav Goldberg
<img src="https://www.cs.bgu.ac.il/~yoavg/uni/me.jpg" width="100px">

**Trying to Understand Recurrent Neural Networks for Language Processing**

<a href="https://t.co/DL0smjHchA">Slides</a>

Recurrent neural networks (RNNs), and in particular LSTM networks, emerge as very capable learners for sequential data. Thus, my group started using them everywhere, achieving strong results on many language understanding and modeling tasks. However, little is known about how RNNs represent sequences, what they actually encode, and what they are capable representing. In this talk, I will describe some attempts at trying to shed light on the inner-working of RNNs. Particularly, I plan to describe at least two of the following: a method for comparing what is captured in vector representations of sentences based on different encoders (Adi et al, ICLR 2017, and more generally the notion of diagnostic classification), a framework for extracting a finite-state automata from trained RNNs (Weiss et al, ICML 2018), and a formal difference between the representation capacity of different RNN variants (Weiss et al, ACL 2018).

Bio: [Yoav Goldberg](http://u.cs.biu.ac.il/~yogo/) is a Senior Lecturer at Bar Ilan University's Computer Science Department. Before that, he was  a Research Scientist at Google Research New York.
He works on problems related to Natural Language Processing and Machine Learning. In particular he is interested in syntactic parsing, structured-prediction models, learning for greedy decoding algorithms, multilingual language understanding, and cross domain learning. Lately, he is also interested in neural network based methods for NLP. He recently published a book on the subject. 



## Description
Neural networks have rapidly become a central component in language and speech understanding systems in the last few years. The improvements in accuracy and performance brought by the introduction of neural networks has typically come at the cost of our understanding of the system: what are the representations and computations that the network learns? The goal of this workshop is to bring together people who are attempting to peek inside the neural network black box, taking inspiration from machine learning, psychology, linguistics and neuroscience. The topics of the workshop will include, but are not limited to:


- Applying analysis techniques from neuroscience to analyze high-dimensional vector representations (such as Haxby et al., 2001; Kriegeskorte, 2008) in artificial neural networks;
- Analyzing the network's response to strategically chosen inputs in order to infer the linguistic generalizations that the network has acquired (e.g., Linzen et al., 2016);
- Examining the performance of the network on simplified or formal languages;
- Proposing modifications to neural network architectures that can make them more interpretable (e.g., Palangi et al., 2017);
- Scaling up neural network analysis techniques developed in the connectionist literature in the 1990s (Elman, 1991);
- Testing whether interpretable information can be decoded from intermediate representations (e.g., Adi et al.,  2017; Chrupała et al., 2017);
- Translating insights on neural networks interpretation from the vision domain (e.g., Zeiler & Fergus, 2014) to language.

##  Submission types

- Archival papers. These are papers reporting on completed, original and unpublished research, with maximum length of 8 pages + references. Papers shorter than this maximum are also welcome. Accepted papers are expected to be presented at the workshop and will be published in the workshop proceedings. They should report on obtained results rather than intended work. These papers will undergo double-blind peer-review, and should thus be anonymized.

- Extended abstracts. These may report on work in progress or may be cross submissions that have already appeared in a non-NLP venue. The extended abstracts are of maximum 2 pages + references. These submissions are non-archival in order to allow submission to another venue. The selection will not be based on a double-blind review and thus submissions of this type need not be anonymized.

Both categories of submissions should use EMNLP 2018 templates:

- Latex: [http://emnlp2018.org/downloads/emnlp18-latex.zip](http://emnlp2018.org/downloads/emnlp18-latex.zip)
- Word: [http://emnlp2018.org/downloads/emnlp18-word.zip](http://emnlp2018.org/downloads/emnlp18-word.zip)

Both papers and abstracts should be submitted via softconf: [https://www.softconf.com/emnlp2018/BlackboxNLP/](https://www.softconf.com/emnlp2018/BlackboxNLP/)

Accepted submissions will be presented at the workshop: most as posters, some as oral presentations (determined by the program committee).

The workshop will have a best paper award, sponsored by the Department of Cognitive Science at Johns Hopkins University.

### Dual submissions

Dual submissions of archival papers with EMNLP (or another conference) are allowed. Please let us know as soon as possible if you decide to withdraw a paper accepted elsewhere. Also please consider that dual submissions increase reviewing burden for the whole community.


## Organizers

**[Tal Linzen](http://tallinzen.net/)** is an Assistant Professor of Cognitive Science at Johns Hopkins University. He develops computational cognitive models of language. In addition to his work in psycholinguistics and cognitive neuroscience, he has studied the syntactic capabilities of contemporary artificial neural networks and the linguistic information encoded in word embeddings, in work that has appeared in TACL, EACL and CoNLL. He has co-organized the workshop on Cognitive Modeling and Computational Linguistics which was co-located with EACL 2017, and is co-organizing the next installation of the same workshop at the Society for Computation in Linguistics in January 2018.

**[Afra Alishahi](https://ilk.uvt.nl/~aalishah/)** is an Associate Professor of Cognitive Science and Artificial Intelligence at Tilburg University, the Netherlands. Her main research interest is developing computational models for studying the process of human language acquisition. Recently she has been studying the emergence of linguistic structure in grounded models of language learning. She has chaired CoNLL 2015, and organized the EACL Workshop on Cognitive Aspects of Computational Language Acquisition in 2009.

**[Grzegorz Chrupała](http://grzegorz.chrupala.me)** is an Assistant Professor at the Department of Cognitive Science and Artificial Intelligence at Tilburg University. His recent research focus has been on computational models of language learning from multimodal signals such as speech and vision and on the analysis and interpretability of representations emerging in multilayer recurrent neural networks. He regularly serves on program committees of major NLP and AI conferences, workshops and journals. He was area co-chair for Machine Learning at ACL 2017, for Discourse and Dialogue, Summarization and Generation, and Multimodal NLP and Speech at EMNLP 2018, and general chair for Benelearn 2018.

## Program committee

- Željko	Agić	- IT University of Copenhagen
- Niranjan	Balasubramanian	- Stony Brook University
- Roberto	Basili	- University of Roma, Tor Vergata
- Laurent	Besacier	- LIG
- Yonatan	Belinkov	- MIT CSAIL
- Or	Biran	- n-Join
- Pravesh	Biyani	- IIIT Delhi
- Arianna	Bisazza	- Leiden University
- Samuel	Bowman	- New York University
- Bill	Byrne	- University of Cambridge
- Kyunghyun	Cho	- New York University
- Ryan	Cotterell	- Johns Hopkins University
- Barry	Devereux	- Queen's University, Belfast
- Ewan	Dunbar	- Ecole Normale Supérieure et Ecole des Hautes Etudes en Sciences Sociales
- Indranil	Dutta	- The English and Foreign Languages University
- Allyson	Ettinger	- University of Maryland
- Antske	Fokkens	- VU Amsterdam
- Robert	Frank	- Yale University
- Alexander Fraser - University of Munich
- Alona	Fyshe	- University of Alberta
- Lieke	Gelderloos	- Tilburg University
- Yoav	Goldberg	- Bar Ilan University
- John	Hale	- Cornell University and Google DeepMind
- David	Harwath	- Massachusetts Institute of Technology
- Ákos	Kádár	- Tilburg University
- Philipp	Koehn	- Johns Hopkins University
- Adhiguna	Kuncoro	- University of Oxford and DeepMind
- Ignacio	Iacobacci	- Sapienza University of Rome
- Angeliki	Lazaridou	- DeepMind
- Miryam	de Lhoneux	- Uppsala University
- Nelson F.	Liu	- University of Washington
- Adam	Lopez	- University of Edinburgh
- David	Mareček	- Charles University in Prague
- Rebecca	Marvin	- Johns Hopkins University
- Paola	Merlo	- University of Geneva
- Marie-Francine	Moens	- KU Leuven
- Yves	Peirsman	- NLP Town
- Mohammad Taher	Pilehvar	- University of Cambridge
- Barbara	Plank	- IT University of Copenhagen
- Delip	Rao	- Johns Hopkins University
- Brian	Roark	- Google Inc.
- Jan	Šnajder	- University of Zagreb
- Whitney	Tabor	- University of Connecticut
- Adina	Williams	- New York University
- Fabio Massimo	Zanzotto	- University of Rome Tor Vergata
- Willem	Zuidema	- University of Amsterdam


## Sponsors

Department of Cognitive Science, Johns Hopkins University

<img src="Amazon-logo-RGB.png" width="200px">

