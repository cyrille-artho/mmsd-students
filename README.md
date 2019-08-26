**Interested in a Master's thesis at the cutting edge of combinatorics or software engineering?**

## Possible student projects for KTH students in collaboration with the [ERATO-MMSD Center](https://group-mmm.org/eratommsd/) in Tokyo:

### A combinatorial approach to detect unstable configurations
Many cyber-physical systems have controllers and algorithms that depend on parameters; they reflect real-world conditions (in a simulation) or settings of the controller itself. The problem of finding an unstable configuration pair is concerned with finding a setting that works well, but fails if one or a few parameters are changed slightly. The challenge is to find a similar pair of configurations that shows such instability.
In this project, we aim to apply combinatorial approaches to search efficiently through configurations that are affected by pair-wise (or k-wise) changes. This extends prior work by Arcaini and Yamada, members of the MMSD-ERATO research center in Japan.

### Synthesizing attacks on wireless communication
In his recent work, Cetinkaya showed an efficient [jamming attack on wireless communication](https://epubs.siam.org/doi/pdf/10.1137/17M1135438). That attack was found by specifying the attack pattern a priori.
We plan to evaluate the feasibility of synthesizing such an attack from scratch, by using the Fourier transform of the attack waveform as a parametric representation of the attack signal. By adapting state space optimization techniques from combinatorial testing and other domains, we can prioritize the search of certain frequencies or combinations thereof.

### Impact of different test methodologies on fault localization
Fault localization benefits from having a high number of labeled test cases. However, this is hard to come by: Unit test suites usually have a relatively minimal set of tests to cover certain functionality or fulfill code coverage criteria. While fully automated testing techniques such as random testing or symbolic execution have potentially the ability to increase code coverage, they often produce false positives, due to a lack of a precise test oracle. Therefore, they tend to produce unlabeled tests.
Model-based testing has the potential to include accurately labeled test cases, if the model includes a precise oracle. The goal of this project is to evaluate different test methods, and combinations thereof, to fault localization, to extend recent work by Zhang et al. on [using machine learning to assign a label to unlabeled test cases.](https://www.sciencedirect.com/science/article/pii/S0164121217301589)
Such work can reuse some existing models from [Modbat](https://people.kth.se/~artho/modbat/), and also create models for some examples from [Defects4J](https://github.com/rjust/defects4j), such as Apache commons-lang, Apache commons-math, and Mockito.
