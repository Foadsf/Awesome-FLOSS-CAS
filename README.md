# Awesome-FLOSS-CAS

A curated list of outstanding Free, Libre, and Open Source Software (FLOSS) Computer Algebra Systems (CAS) for mathematicians, educators, and researchers.

## Table of Contents
- [Introduction](#introduction)
- [CAS List](#cas-list)
- [Comparison Table](#comparison-table)
- [Helps Needed](#helps-needed)
- [How to Contribute](#how-to-contribute)
- [License](#license)

## Introduction
This repository gathers and documents the best open-source computer algebra systems available. These tools are invaluable for various mathematical computations, symbolic manipulations, and educational purposes.

## CAS List

### Maxima
- **Description**: Maxima is a system for manipulating symbolic and numerical expressions, including differentiation, integration, and more.
- **Platform**: Cross-platform
- **License**: GPL
- **Website**: [Visit Maxima](http://maxima.sourceforge.net/)

### Sympy
- **Description**: Sympy is a Python library for symbolic mathematics, aiming to become a full-featured CAS.
- **Platform**: Cross-platform
- **License**: BSD
- **Website**: [Visit Sympy](https://www.sympy.org/)

### SageMath
- **Description**: Integrates many existing open-source mathematics software packages (including Symy, Maxima, and GiNaC) into a common interface.
- **Platform**: Cross-platform
- **License**: GPL
- **Website**: [Visit SageMath](http://www.sagemath.org/)

### Yacas
- **Description**: Yacas (Yet Another Computer Algebra System) is designed for easy extensibility, featuring a small core and its own programming language.
- **Platform**: Cross-platform
- **License**: LGPL
- **Website**: [Visit Yacas](https://www.yacas.org/)

### PanAxiom
- **Description**: PanAxiom includes several forks of the Axiom computer algebra system, focusing on different aspects of symbolic computation.
    - **Axiom**: [Visit Axiom](http://axiom-developer.org/)
    - **FriCAS**: [Visit FriCAS](http://fricas.sourceforge.net/)
    - **OpenAxiom**: [Visit OpenAxiom](http://www.open-axiom.org/)
- **Platform**: Cross-platform
- **License**: BSD, GPL

### FORM
- **Description**: FORM is a tool for large-scale algebraic calculations, specialized for computations in high-energy physics.
- **Platform**: Cross-platform
- **License**: GPLv3
- **Website**: [Visit FORM](https://www.nikhef.nl/~form/)

### Macaulay2
- **Description**: Macaulay2 is a software system devoted to supporting research in algebraic geometry and commutative algebra.
- **Platform**: Cross-platform
- **License**: GPL
- **Website**: [Visit Macaulay2](https://macaulay2.com/)

### Magnus
- **Description**: Magnus is a computer algebra system that focuses on computations in group theory, particularly for infinite groups.
- **Platform**: Unix
- **License**: Custom free software license
- **Website**: [Visit Magnus](https://en.wikipedia.org/wiki/Magnus_(computer_algebra_system))

### Mathomatic
- **Description**: Mathomatic is a portable, lightweight computer algebra system capable of symbolic calculation and manipulation.
- **Platform**: Cross-platform
- **License**: LGPL
- **Website**: [Visit Mathomatic](https://en.wikipedia.org/wiki/Mathomatic)

### REDUCE
- **Description**: REDUCE is one of the oldest and most comprehensive general-purpose computer algebra systems used in various scientific fields.
- **Platform**: Cross-platform
- **License**: BSD
- **Website**: [Visit REDUCE](http://www.reduce-algebra.com/)

### Euler Math Toolbox (EMT)
- **Description**: Euler Math Toolbox combines numerical and symbolic tools and is noted for integrating a powerful numerical engine with Maxima for symbolic operations.
- **Platform**: Windows, Linux
- **License**: GPL
- **Website**: [Visit EMT](http://euler-math-toolbox.de/)

### Mathics
- **Description**: Mathics is a free, open-source alternative to Mathematica that supports many of its standard library functions.
- **Platform**: Cross-platform
- **License**: AGPL
- **Website**: [Visit Mathics](http://mathics.github.io/)

### Cantor
- **Description**: Cantor integrates different mathematical software into a consistent KDE-integrated interface, providing a user-friendly environment.
- **Platform**: Cross-platform
- **License**: GPL
- **Website**: [Visit Cantor](https://edu.kde.org/cantor/)

### MathAction
- **Description**: MathAction provides a web interface to the Axiom/FriCAS computer algebra systems, facilitating collaborative mathematical work.
- **Platform**: Web
- **License**: BSD
- **Website**: [Visit MathAction](http://wiki.axiom-developer.org/MathActionFrontPage)

### SymbolicC++
- **Description**: SymbolicC++ brings symbolic manipulation capabilities directly into the C++ language, enabling symbolic computations in a standard programming environment.
- **Platform**: Cross-platform
- **License**: LGPL
- **Website**: [Visit SymbolicC++]([https://symboliccpp.github.io/](https://symboliccpp.sourceforge.net/))

### SymEngine
- **Description**: SymEngine is a fast symbolic manipulation library designed for use in larger systems like Python's SymPy.
- **Platform**: Cross-platform
- **License**: BSD
- **Website**: [Visit SymEngine](https://github.com/symengine/symengine)

### GiNaC
- **Description**: GiNaC is an open framework for symbolic computation within the C++ programming language that does not require external libraries.
- **Platform**: Cross-platform
- **License**: GPL
- **Website**: [Visit GiNaC](https://www.ginac.de/)

### Piranha
- **Description**: Piranha is a C++ library for symbolic mathematics, particularly focusing on multivariate polynomials and series manipulations.
- **Platform**: Cross-platform
- **License**: MPL
- **Website**: [Visit Piranha](https://github.com/bluescarni/piranha)


## Comparison Table

| **CAS**                | **Programming Language** | **Typical Applications**                          | **Notable Features**                             |
|------------------------|--------------------------|---------------------------------------------------|--------------------------------------------------|
| Maxima (WxMaxima, Jupyter) | Lisp                    | General mathematics, education                    | Symbolic computation, numerical methods, high precision |
| Python-Sympy (Jupyter) | Python                   | General mathematics, physics, engineering         | Integrates with Python, broad library support    |
| SageMath               | Python                   | Broad spectrum (algebra, calculus, number theory) | Integrates many CAS backends, extensive functionality |
| Yacas                  | Lisp (own language)      | Algebraic manipulations, education                | Easily extensible, lightweight                  |
| PanAxiom (Axiom, FriCAS, OpenAxiom) | Lisp              | Algebra, research, education                      | Strongly typed, algebraically oriented          |
| FORM                   | Own scripting language   | High energy physics                               | Handles very large expressions efficiently      |
| Macaulay2              | Own language             | Algebraic geometry, commutative algebra           | Grobner bases, characteristic sets              |
| Magnus                 | C++                      | Group theory, especially infinite groups          | Specialized in computational group theory       |
| Mathomatic             | C                        | Algebraic equations, education                    | Lightweight, portable                           |
| REDUCE                 | Lisp                     | General mathematics, physics                      | One of the oldest CAS, versatile                |
| Euler Math Toolbox (EMT)| C++, own scripting       | Numerical analysis, symbolic computations         | Numerical and symbolic capabilities             |
| Mathics                | Python                   | General purpose, similar to Mathematica           | Mathematica-compatible syntax, lightweight      |
| Cantor                 | C++ (KDE)                | Educational, integrates multiple backends         | User-friendly, part of KDE education project    |
| MathAction             | Web interface            | Web-based access to Axiom/FriCAS                  | Convenient web interface for Axiom              |
| SymbolicC++            | C++                      | Embedded algebra in C++ applications              | Symbolic manipulation in C++                    |
| SymEngine              | C++                      | Core for symbolic computations in Sympy           | Fast, efficient, used as backend for Sympy      |
| GiNaC                  | C++                      | Symbolic computations integrated in C++           | No external dependencies, robust                |
| Piranha                | C++                      | Polynomial arithmetic, large algebraic expressions| High-performance polynomial operations          |




## How to Contribute
We welcome contributions from the community! Here are some ways you can contribute:
- **Add a new CAS**: If you know of a FLOSS CAS that is not listed here, please submit a pull request with details following the format used in the CAS List.
- **Improve descriptions**: Help us improve the descriptions for each listed CAS to provide clearer and more comprehensive information.
- **Report Issues**: If you notice any errors or outdated information, please open an issue.

## Helps Needed

I am considering adding several features and resources:

1. **Tutorials and Examples:**
   - Include tutorials or example notebooks demonstrating how to use each CAS for common mathematical problems or specific applications, such as algebra, calculus, or physics.
   - Provide step-by-step guides for setting up and getting started with each system.

2. **Comparison Tables:**
   - Offer a more detailed comparison table highlighting each system's strengths and weaknesses, such as performance benchmarks, feature sets, and ease of use.

3. **Integration Guides:**
   - Provide documentation on integrating these systems with other software tools, such as data analysis platforms, scientific computing environments, or programming languages.

4. **Community Contributions:**
   - Set up a section for user-contributed scripts or modules.

5. **User Reviews and Experiences:**
   - Create a space where users can share their experiences, reviews, and tips for using different CAS tools. This could help new users make informed decisions based on community feedback.

6. **Video Demonstrations:**
   - Add video tutorials or demonstrations that provide visual and practical guidance on using the CAS tools effectively.

8. **Related Resources:**
   - Link to external resources, such as forums, blogs, and academic papers that discuss or use the listed CAS.

9. **License Information:**
   - Clearly document the licensing information for each CAS to ensure users understand how they can legally use and distribute the software.


To contribute, please fork the repository, make your changes, and submit a pull request.

## License
This curated list is published under the [Creative Commons License](LICENSE). Contributions to this repository are accepted under the same license.

