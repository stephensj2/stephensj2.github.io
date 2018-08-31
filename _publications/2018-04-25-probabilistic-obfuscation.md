---
title: "Probabilistic Obfuscation through Covert Channels"
collection: publications
permalink: /publication/EuroSP2018
abstract: "This paper presents a program obfuscation framework that uses covert channels through the program's execution environment to obfuscate information flow through the program. Unlike prior works on obfuscation, the use of covert channels removes visible information flows from the computation of the program and reroutes them through the program's runtime system and/or the operating system. This renders these information flows, and the corresponding control and data dependencies, invisible to program analysis tools such as symbolic execution engines. Additionally, we present the idea of probabilistic obfuscation which uses imperfect covert channels to leak information with some probabilistic guarantees. Experimental evaluation of our approach against state of the art detection and analysis techniques show the engines are not well-equipped to handle these obfuscations, particularly those of the probabilistic variety."
date: 2018-04-25
venue: 'Proceedings of the Third IEEE European Symposium on Security and Privacy'
shortvenue: 'EuroS&P'
year: 2018
status: 'In'
authors: 'Jon Stephens, Babak Yadegari, Christian Collberg, Saumya Debray, Carlos Scheidegger'
paperurl: 'https://stephensj2.github.io/files/probabilistic-obfuscation-covert.pdf'
awards:
citation:
---

Authors: {{ page.authors }}

Abstract: {{ page.abstract }}

Full Text: [pdf]({{page.paperurl}})

Bibtex: 
@inproceedings{stephens2018probabilistic,
  title={Probabilistic Obfuscation Through Covert Channels},
  author={Stephens, Jon and Yadegari, Babak and Collberg, Christian and Debray, Saumya and Scheidegger, Carlos},
  booktitle={2018 IEEE European Symposium on Security and Privacy (EuroS&P)},
  year={2018},
  organization={IEEE}
}
