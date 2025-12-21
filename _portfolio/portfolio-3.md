---
title: "Abstract Polynomial Python Toolkit"
excerpt: "A Python module to perform a wide variety of operations on polynomials with coefficients in rings/fields beyond the real numbers. This project was inspired by my first course in abstract algebra."
collection: portfolio
date: 2024-12-01
---

(GitHub)[https://github.com/larsenbier/PyPolynomials]

A python Polynomial class to handle operations on polynomials with coefficients in the following rings: Z, Q, R, C, Z/nZ, and F[x]/p(x) , where F is a field and p(x) is irreducible in F (i.e. field extensions).
Implemented algorithms to compute polynomial inverses, greatest common divisors, and division, while using abstract algebra to safeguard the algorithms against situations where the they may fail.
Created Ring and Field classes with the flexibility to support many abstract, user-defined rings, fields, and polynomials.
