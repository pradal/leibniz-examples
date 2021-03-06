![Leibniz logo](https://github.com/khinsen/leibniz/raw/master/logo/horizontal-leibniz-logo-500-x-150-png.png)

[Leibniz](https://github.com/khinsen/leibniz) is a digital scientific notation under development. It should be considered experimental at this point.

This repository contains example documents that use Leibniz. These documents are meant to illustrate what a digital scientific notation looks like, and how it can be used.

All content in this repository is published under the [Creative Commons Attribution](https://creativecommons.org/licenses/by/4.0/) licence.

## Quick guide to Leibniz

In the Leibniz documents, computationally relevant definitions and rules are shown on a blue background. Computed content is shown on a green background.

An important distinction in Leibniz that is often neglected in traditional mathematical notation is the one between values and variables. For example, a time *value* t refers to a specific moment in time, whereas a time *variable* t stands for an *arbitrary* time value. In Leibniz, variables are typeset in italics.

Each example also contains a link to an XML version, which contains just the definitions and rules. It is meant to be processed by software. There is also a link to the source code, which is written in an extension of the [Scribble](https://docs.racket-lang.org/scribble/index.html) language, which is the documentation language of the [Racket](http://racket-lang.org/) software ecosystem.


## List of examples

 [Leibniz by example](examples/leibniz-by-example.html) is the first example you should look at, because it contains many explanations of Leibniz itself. You can also consult the machine-readable version of the equations it contains as an [XML](examples/leibniz-by-example.xml) file, and have a look at the [source code](https://github.com/khinsen/leibniz-examples/blob/master/examples/leibniz-by-example.scrbl) from which both the human-readable and the machine-readable versions are generated.

Other examples:
- Basic [mathematical functions](examples/functions.html) ([XML](examples/functions.xml), [source code](https://github.com/khinsen/leibniz-examples/blob/master/examples/functions.scrbl))
- [Euclid's GCD algorithm](examples/euclid_gcd.html) for the greatest common divisor of two natural numbers ([XML](examples/euclid_gcd.xml), [source code](https://github.com/khinsen/leibniz-examples/blob/master/examples/euclid_gcd.scrbl))
 - [Heron's algorithm](examples/heron.html) for computing square roots ([XML](examples/heron.xml), [source code](https://github.com/khinsen/leibniz-examples/blob/master/examples/heron.scrbl))
 - [Boolean algebra](examples/boolean.html), ([XML](examples/boolean.xml), [source code](https://github.com/khinsen/leibniz-examples/blob/master/examples/boolean.scrbl)])
 - [Masses and mass units](examples/masses.html) ([XML](examples/masses.xml), [source code](https://github.com/khinsen/leibniz-examples/blob/master/examples/masses.scrbl))
- A more general [framework for physical quantities](examples/quantities.html) ([XML](examples/quantities.xml), [source code](https://github.com/khinsen/leibniz-examples/blob/master/examples/quantities.scrbl))
