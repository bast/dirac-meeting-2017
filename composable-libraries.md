name: inverse
layout: true
class: middle, inverse

---

# Composable libraries for quantum chemistry and other random thoughts

## [Radovan Bast](http://bast.fr)

### [NeIC](https://neic.nordforsk.org)/ [UiT The Arctic University of Norway](https://uit.no)

Text is free to share and remix under [CC-BY-SA-4.0](https://creativecommons.org/licenses/by-sa/4.0/).

Code examples: [MIT license](http://opensource.org/licenses/mit-license.html)

Credits: [Roberto Di Remigio](http://totaltrash.xyz),
         [Ole Martin Bjørndalen](https://github.com/olemb)

---

layout: false

Write me ...

---

## There are many ways to interface with Python

- SWIG
- F2PY
- Boost
- PyBind11
- Cython
- CFFI

---

## Motivations for interfacing with Python

- Fast and easy prototyping
- Leveraging Python packages
- Distribute via PyPI
- Test with pytest
- Simple I/O (e.g. parse input with a one-liner)

---

## CFFI example


---

## How to include libraries in larger projects

- Submodules
- Subtrees
- Download/link at build time

---

template: inverse

## If you rewrite the entire code (even in a new language), can you distribute the new code?

---

## Clean room design (AKA Chinese wall technique)

- Team A studies the code
- Team B never sees the code
- Team A explains the implementation to team B (specifications are validated by lawyers)
- Team B implements the algorithm based on the specs


### Everything that is not fair use or clean room design is derivative work

- Consider this when using or distributing code
- Consider this when choosing a license
- Choose a standard license
