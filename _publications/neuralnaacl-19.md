---
title: "Neural Constituency Parsing of Speech Transcripts"
collection: publications
permalink: /publication/neuralnaacl-19
excerpt: 'Parsing speech with Transformer.'
date: 2019-06-02
venue: 'Proceedings of the 2019 Conference of the North American Chapter of the Association for Computational Linguistics: Human Language Technologies, Volume 1 (Long and Short Papers)'
paperurl: 'http://academicpages.github.io/files/paper3.pdf'
authors: 'Paria Jamshid Lou, <strong>Yufei Wang</strong>, Mark Johnson'
---
This paper studies the performance of a neural self-attentive parser on transcribed speech. Speech presents parsing challenges that do not appear in written text, such as the lack of punctuation and the presence of speech disfluencies (including filled pauses, repetitions, corrections, etc.). Disfluencies are especially problematic for conventional syntactic parsers, which typically fail to find any EDITED disfluency nodes at all. This motivated the development of special disfluency detection systems, and special mechanisms added to parsers specifically to handle disfluencies. However, we show here that neural parsers can find EDITED disfluency nodes, and the best neural parsers find them with an accuracy surpassing that of specialized disfluency detection systems, thus making these specialized mechanisms unnecessary. This paper also investigates a modified loss function that puts more weight on EDITED nodes. It also describes tree-transformations that simplify the disfluency detection task by providing alternative encodings of disfluencies and syntactic information.

[ACL Anthology](https://www.aclweb.org/anthology/N19-1282/)
