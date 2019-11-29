---
title: "Neural Constituency Parsing of Speech Transcripts"
collection: publications
permalink: /publication/neuralparsing
excerpt: 'This paper is about the number 3. The number 4 is left for future work.'
date: 2015-10-01
venue: 'Journal 1'
paperurl: 'http://academicpages.github.io/files/paper3.pdf'
citation: 'Your Name, You. (2015). &quot;Paper Title Number 3.&quot; <i>Journal 1</i>. 1(3).'
---
This paper studies the performance of a neural self-attentive parser on transcribed speech. Speech presents parsing challenges that do not appear in written text, such as the lack of punctuation and the presence of speech disfluencies (including filled pauses, repetitions, corrections, etc.). Disfluencies are especially problematic for conventional syntactic parsers, which typically fail to find any EDITED disfluency nodes at all. This motivated the development of special disfluency detection systems, and special mechanisms added to parsers specifically to handle disfluencies. However, we show here that neural parsers can find EDITED disfluency nodes, and the best neural parsers find them with an accuracy surpassing that of specialized disfluency detection systems, thus making these specialized mechanisms unnecessary. This paper also investigates a modified loss function that puts more weight on EDITED nodes. It also describes tree-transformations that simplify the disfluency detection task by providing alternative encodings of disfluencies and syntactic information.

[ACL Anthology](https://www.aclweb.org/anthology/N19-1282/)