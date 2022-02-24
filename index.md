---
layout: default
---

# MachSMT

MachSMT is an algorithm selection tool for Satisfiability Modulo Theories (SMT) solvers. MachSMT supports the entirety of the SMT-LIB language. It deploys machine learning (ML) methods to construct both empirical hardness models (EHMs) and pairwise ranking comparators (PWCs) over state-of-the-art SMT solvers.  Given an input formula in SMT-LIB format, MachSMT leverages these learnt models to output a ranking of solvers based on predicted run time on that formula.

MachSMT has been extensivly evaluated to demonstrate its efficiency and efficacy. We have evaluated MachSMT on state-of-the-art solvers in SMT-COMP '19 and '20. We observe MachSMT frequently improves on competition winners. Second, we evaluate MachSMT to select configurations from a single underlying solver, namely `cvc5` and observe significant empirical emprovements of static competition scripts. 

MachSMT is not a replacement for SMT solvers by any means. Instead, it is a tool that enables users to leverage the collective strength of the diverse set of algorithms implemented as part of these sophisticated solvers.

## People
* Joseph Scott
* Aina Niemetz
* Mathias Periner
* Saeed Nejati
* Vijay Ganesh (Principal Investigator)

The MachSMT would like to thank Pascal Poupart for his feedback on earlier versions of this work. 

## SMT '20 Talk

[![Talk](https://img.youtube.com/vi/OfZaIUXltf4/0.jpg)](https://youtu.be/OfZaIUXltf4?t=5795)


## Publications

TACAS '21 [MachSMT: A Machine Learning-based Algorithm Selector for SMT Solvers}](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7984560/)

```
@inproceedings{DBLP:conf/tacas/ScottNPNG21,
  author    = {Joseph Scott and
               Aina Niemetz and
               Mathias Preiner and
               Saeed Nejati and
               Vijay Ganesh},
  editor    = {Jan Friso Groote and
               Kim Guldstrand Larsen},
  title     = {MachSMT: {A} Machine Learning-based Algorithm Selector for {SMT} Solvers},
  booktitle = {Tools and Algorithms for the Construction and Analysis of Systems
               - 27th International Conference, {TACAS} 2021, Held as Part of the
               European Joint Conferences on Theory and Practice of Software, {ETAPS}
               2021, Luxembourg City, Luxembourg, March 27 - April 1, 2021, Proceedings,
               Part {II}},
  series    = {Lecture Notes in Computer Science},
  volume    = {12652},
  pages     = {303--325},
  publisher = {Springer},
  year      = {2021},
  url       = {https://doi.org/10.1007/978-3-030-72013-1\_16},
  doi       = {10.1007/978-3-030-72013-1\_16},
  timestamp = {Fri, 14 May 2021 08:34:19 +0200},
  biburl    = {https://dblp.org/rec/conf/tacas/ScottNPNG21.bib},
  bibsource = {dblp computer science bibliography, https://dblp.org}
}
```


SMT '19 [An Algorithm Selection Approach for QF FP Solvers](http://smt2019.galois.com/papers/paper_7.pdf)

```
@misc{scott2019algorithm,
  author    = {Joseph Scott and
              Pascal Poupart and
              Vijay Ganesh},
  editor    = {Natasha Sharygina and
              Joe Hendrix},
  title     = {{An Algorithm Selection Approach for QF FP Solvers}},
  booktitle = {Proceedings of the 17th International Workshop on Satisfiabilit Modulo Theories co-located with the 22nd International Conference on the Theory and Applications of Satisfiability Testing (SAT) 2020) July 7-12, 2019},
  year      = {2019},
  url       = {http://smt2019.galois.com/papers/paper_7.pdf},
}
```

If you are a researcher leveraging ideas from MachSMT, please consider citing our work. To cite MachSMT, please use the TACAS paper. For the prelimiary work prior to MachSMT consider the SMT paper.

