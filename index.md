---
layout: default
---

# BanditFuzz

BanditFuzz is a multi-agent reinforcement learning guided performance fuzzing algorithm. BanditFuzz has extensively been considered in the context of Satisfiability Modulo Theories (SMT)  solvers. BanditFuzz constructs inputs that expose performance issues in a set of target solvers relative to a set of reference solvers. The `banditfuzz` tool is the first performance fuzzer that supports the entirety of the theories in the SMT-LIB initiative. 

## People
* Joseph Scott
* Federico Mora
* Hammad Rehman
* Trishal Sudula
* Vijay Ganesh (Principal Investigator)

The BanditFuzz team would like to thank Aina Niemetz, Mathias Periner, Martin Brain, Murphy Berzish, and Mitja Kulczynski for their feedback while the project was under development. 

## SMT '20 Talk

[![Talk](https://img.youtube.com/vi/OfZaIUXltf4/0.jpg)](https://youtu.be/OfZaIUXltf4?t=4013)


## Publications

[BanditFuzz: A Reinforcement-Learning Based Performance Fuzzer for SMT Solvers](https://www.semanticscholar.org/paper/BanditFuzz%3A-A-Reinforcement-Learning-Based-Fuzzer-Scott-Mora/4dd1361dd215cc2d02f178f4ec307b74a4f51cbb)

```
@inproceedings{DBLP:conf/vstte/ScottMG20,
  author    = {Joseph Scott and
               Federico Mora and
               Vijay Ganesh},
  editor    = {Maria Christakis and
               Nadia Polikarpova and
               Parasara Sridhar Duggirala and
               Peter Schrammel},
  title     = {BanditFuzz: {A} Reinforcement-Learning Based Performance Fuzzer for
               {SMT} Solvers},
  booktitle = {Software Verification - 12th International Conference, {VSTTE} 2020,
               and 13th International Workshop, {NSV} 2020, Los Angeles, CA, USA,
               July 20-21, 2020, Revised Selected Papers},
  series    = {Lecture Notes in Computer Science},
  volume    = {12549},
  pages     = {68--86},
  publisher = {Springer},
  year      = {2020},
  url       = {https://doi.org/10.1007/978-3-030-63618-0\_5},
  doi       = {10.1007/978-3-030-63618-0\_5},
  timestamp = {Mon, 03 Jan 2022 22:15:02 +0100},
  biburl    = {https://dblp.org/rec/conf/vstte/ScottMG20.bib},
  bibsource = {dblp computer science bibliography, https://dblp.org}
}
```

[BanditFuzz: Fuzzing SMT Solvers with Multi-agent Reinforcement Learning](https://www.springerprofessional.de/en/banditfuzz-fuzzing-smt-solvers-with-multi-agent-reinforcement-le/19849098)

```
@inproceedings{DBLP:conf/fm/ScottSRMG21,
  author    = {Joseph Scott and
               Trishal Sudula and
               Hammad Rehman and
               Federico Mora and
               Vijay Ganesh},
  editor    = {Marieke Huisman and
               Corina S. Pasareanu and
               Naijun Zhan},
  title     = {BanditFuzz: Fuzzing {SMT} Solvers with Multi-agent Reinforcement Learning},
  booktitle = {Formal Methods - 24th International Symposium, {FM} 2021, Virtual
               Event, November 20-26, 2021, Proceedings},
  series    = {Lecture Notes in Computer Science},
  volume    = {13047},
  pages     = {103--121},
  publisher = {Springer},
  year      = {2021},
  url       = {https://doi.org/10.1007/978-3-030-90870-6\_6},
  doi       = {10.1007/978-3-030-90870-6\_6},
  timestamp = {Wed, 15 Dec 2021 10:33:04 +0100},
  biburl    = {https://dblp.org/rec/conf/fm/ScottSRMG21.bib},
  bibsource = {dblp computer science bibliography, https://dblp.org}
}
```

If you are a researcher leveraging ideas from BanditFuzz, please consider citing our work. To cite the BanditFuzz algorithm, please use the VSTTE paper. To cite the tool or multi-agent formulation, please use the FM paper.

<!-- > This is a blockquote following a header.
>
> When something is important enough, you do it even if the odds are not in your favor.

### Header 3

```js
// Javascript code with syntax highlighting.
var fun = function lang(l) {
  dateformat.i18n = require('./lang/' + l)
  return true;
}
```

```ruby
# Ruby code with syntax highlighting
GitHubPages::Dependencies.gems.each do |gem, version|
  s.add_dependency(gem, "= #{version}")
end
```

#### Header 4

*   This is an unordered list following a header.
*   This is an unordered list following a header.
*   This is an unordered list following a header.

##### Header 5

1.  This is an ordered list following a header.
2.  This is an ordered list following a header.
3.  This is an ordered list following a header.

###### Header 6

| head1        | head two          | three |
|:-------------|:------------------|:------|
| ok           | good swedish fish | nice  |
| out of stock | good and plenty   | nice  |
| ok           | good `oreos`      | hmm   |
| ok           | good `zoute` drop | yumm  |

### There's a horizontal rule below this.

* * *

### Here is an unordered list:

*   Item foo
*   Item bar
*   Item baz
*   Item zip

### And an ordered list:

1.  Item one
1.  Item two
1.  Item three
1.  Item four

### And a nested list:

- level 1 item
  - level 2 item
  - level 2 item
    - level 3 item
    - level 3 item
- level 1 item
  - level 2 item
  - level 2 item
  - level 2 item
- level 1 item
  - level 2 item
  - level 2 item
- level 1 item

### Small image

![Octocat](https://github.githubassets.com/images/icons/emoji/octocat.png)

### Large image

![Branching](https://guides.github.com/activities/hello-world/branching.png)


### Definition lists can be used with HTML syntax.

<dl>
<dt>Name</dt>
<dd>Godzilla</dd>
<dt>Born</dt>
<dd>1952</dd>
<dt>Birthplace</dt>
<dd>Japan</dd>
<dt>Color</dt>
<dd>Green</dd>
</dl>

```
Long, single-line code blocks should not wrap. They should horizontally scroll if they are too long. This line should be long enough to demonstrate this.
```

```
The final element.
``` -->
