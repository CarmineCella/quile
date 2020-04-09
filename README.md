# Skicl

The Skicl programming language is a hybrid dialect of Lisp, Scheme and TCL: 

![Genealogy](docs/skicl_anchestors.png)

It has been designed to be small, easy to expand and easy to embed in host applications. It is made of a single small C++ header (~ 800 loc) and some additional files written using Skicl itself.

Skicl includes several neat features among which:

* homoiconicity and introspection
* macros
* tail recursion
* static and dynamic scoping
* partial evaluation
* lambda functions with closures

For an overview on the language, please see [overview.tcl](examples/overview.tcl).

(c) 2020 by Carmine E. Cella, www.carminecella.com
