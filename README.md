# ECMA-55 Minimal BASIC Test Programs

**Endeavor: Retro-BASIC**  
**Repository: \<[http://source.retro-basic.net/ecma55.test](http://source.retro-basic.net/ecma55.test)\>**  
**Version: 1.0!0 (alpha)**  
**Environments: ECMA55 (Minimal BASIC)**  
**Compliance: Retro-Frame 1.0**  
**License: MIT (see `LICENSE`)**  

Copyright (c) 2026 Ingo Boehmer \<ingo@retro-leisure.net\>

All product names, logos, and brands are property of their respective owners.


## Contents

1. Overview

2. How to run the programs

3. Usage

4. Security level

5. References


## 1. Overview

This repository provides small **ECMA-55 Minimal BASIC** programs which
are intended to test the behavior of ECMA-55 conforming interpreters or
compilers.

Development of this software is subject to Retro-BASIC and complies to the
**Retro-Frame Common Documentation**.


## 2. How to run the programs

The Minimal BASIC test programs are located in the `src/` directory.

In order to run the programs, you need an **ECMA-55 Minimal BASIC** compliant
interpreter or compiler (Retro-C, for example, provides the simple interpreter
**RECMA55**).

Please note that some of the test programs will intentionally produce errors
and may even not run at all.


## 3. Usage

See `doc/test-doc.txt` for the expected results of the test programs.


## 4. Security level

All ECMA-55 Minimal BASIC test programs have security level *medium*. They
should not do any harm on your computer but do not assume that pseudo-random
number generation by the function `RND` and the statement `RANDOMIZE` is secure
(i.e. not predictable and not revealing any information about your system)
unless the interpreter or compiler assures this property. Otherwise, it may be
necessary to run the ECMA-55 Minimal BASIC demo programs in security level
*low*.


## 5. References

### ECMA-55 Minimal BASIC

ECMA-55 Minimal BASIC standard (withdrawn), European Computer Manufacturers
Association, January 1978, see
\<[https://ecma-international.org/publications-and-standards/standards/ecma-55/](https://ecma-international.org/publications-and-standards/standards/ecma-55/)\>.

### RECMA55

Retro ECMA-55-compliant Minimal BASIC Interpreter, see
\<[http://source.retro-c.net/comp.stdc.recma55](http://source.retro-c.net/comp.stdc.recma55)\>.

### Retro-Frame Common Documentation

Retro-Frame Common Documentation, see
\<[http://source.retro-frame.net/common](http://source.retro-frame.net/common)\>.
