# Literate Ruby Specification

This is an experiment in "literate specification". Literate specification takes inspiration from "literate programming", an idea created by Donald Knuth:

> I believe that the time is ripe for significantly better documentation of programs, and that we can best achieve this by considering programs to be works of literature. Hence, my title: "Literate Programming."

> Let us change our traditional attitude to the construction of programs: Instead of imagining that our main task is to instruct a computer what to do, let us concentrate rather on explaining to human beings what we want a computer to do.

> The practitioner of literate programming can be regarded as an essayist, whose main concern is with exposition and excellence of style. Such an author, with thesaurus in hand, chooses the names of variables carefully and explains what each variable means. He or she strives for a program that is comprehensible because its concepts have been introduced in an order that is best for human understanding, using a mixture of formal and informal methods that reinforce each other.

&mdash; Donald Knuth. "Literate Programming (1984)" in Literate Programming. CSLI, 1992, pg. 99. See <http://www.literateprogramming.com>.


## The problem with documentation and code

Literate programming is a powerful idea. It refocuses the purpose of writing programs on the humans that are writing, reading, and maintaining the programs. It explicitly makes the narrative of the program primary, rather than the structure and organization of the program source code.

Unfortunately, by combining these two very different things into one physical shape, one must necessarily be subordinate to the other. It is impossible to be otherwise. We much more commonly see the "documentation", in the form of comments embedded in source code, as the subordinate one. The flow and organization of the documentation is then subordinate to organization of the source code.

While literate programming inverts this more commonly observed relationship between documentation and source code, it does not produce a notably more useful solution to the inherent tension. Documentation and source code have independent and separate proper forms. The former influenced by human cognition and the latter influenced by the particular mechanics of the programming language.

While code and documentation are forever destined to be oil and water, there _are_ two things that mix together very well: documentation and tests. If mixed just so, we have a good chance of creating a useful specification:

> _specification_ noun: an act of identifying or describing something precisely or of stating a precise requirement

&mdash; Apple Dictionary


## A literate specification system

As defined here, a "literate specification" is comprised of five parts:

1. The human readable text of the specification, which is suitable for documentation.
1. A special-purpose specification language with a defined logic that enables reasoning about the specification.
1. Example source code that illustrates the specification. Execution of the example code results in a state that shows compliance or noncompliance with the specification the source code illustrates.
1. A system that implements the specification and is architected such that all aspects of the specification are observable and controllable.
1. A system that processes the literate specification and causes the example source code to be run on the system that implements the specification.


## Code of Conduct

Participation in this project is governed by the Rubinius [Code of Conduct](http://rubinius.com/code-of-conduct/).


## Online Discussion

[![Gitter](https://badges.gitter.im/rubinius/literate-ruby.svg)](https://gitter.im/rubinius/literate-ruby?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge)


## License

For any part of this work for which the license is applicable, this work is licensed under the [Attribution-NonCommercial-NoDerivatives 4.0 International](http://creativecommons.org/licenses/by-nc-nd/4.0/) license. See LICENSE.CC-BY-NC-ND-4.0.

<a rel="license" href="http://creativecommons.org/licenses/by-nc-nd/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-nd/4.0/88x31.png" /></a><br /><span xmlns:dct="http://purl.org/dc/terms/" property="dct:title">Literate Ruby Specification</span> by <a xmlns:cc="http://creativecommons.org/ns#" href="http://literate-ruby.com" property="cc:attributionName" rel="cc:attributionURL">Brian Shirai</a> is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-nd/4.0/">Creative Commons Attribution-NonCommercial-NoDerivatives 4.0 International License</a>.<br />Based on a work at <a xmlns:dct="http://purl.org/dc/terms/" href="https://github.com/rubinius/literate-ruby" rel="dct:source">https://github.com/rubinius/literate-ruby</a>.

Any part of this work for which the CC-BY-NC-ND-4.0 license is not applicable is licensed under the [Mozilla Public License 2.0](). See LICENSE.MPL-2.0.

Any part of this work that is known to be derived from an existing work is licensed under the license of that existing work. Where such license is known, the license text is included in the LICENSE.ext file, where "ext" indicates the license.
