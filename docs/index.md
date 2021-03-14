---
hide:
  - navigation
---

# Glossary
APL is rife with jargon. Since it is older than many of the more popular languages of today, some of the terms are quite different to those used for similar constructs in modern programming and computer science literature.

## Alpha `⍺`
[APL Functional Symbol Alpha](https://unicode-table.com/en/237A/)

Left [argument](#argument) in dfns

## Argument
An [array](#array) value which is passed to a [function](#function).

## Array
[APL Wiki](https://aplwiki.com/wiki/Array)

## Catenate
[APL Wiki](https://aplwiki.com/wiki/Catenate)

Join two arrays along their [first axis](#first axis) `⍪` or [last axis](#last axis)`,`.

Join two arrays along specified axes `⍪[a] ,[a]`.

Join two arrays by pairing cells of rank `j` and `k`: `⍪⍤j k` (first axis), `,⍤j k` (last axis)

## Dfn
A style of function definition which encourages a [functional programming]() style. Its left argument is referred to using [`⍺`](#alpha) and its

### Synonyms
lambda, curly brace function

## Dop

## First axis
The first number in the shape `⍴⍵` of an array `⍵`.

First-axis functions and operators operate on or between [major cells](major cell) of an array.

### First axis functions
- [reverse](#reverse)-first
- [catenate](#catenate)-first

### First axis operators
- [reduce](#reduce)-first

## Fold
Monadic operator [reduce]

## Function

### Synonyms
operator (unary, binary, tertiary), procedure, subroutine

## Monadic
An entity which accepts one.

A monadic function takes one argument to its right which is an [array](#array).

A monadic operator takes one operand to its left which is a [function](#function). Example: [reduce `/`]().

### Synonyms
unary

## Omega

## Dyadic
An entity which accepts two.

A dyadic function takes two arguments, one to [its left](#alpha) and one to [its right](#omega).

**Synonyms:** binary

## Niladic

## Operator

## Reduce
[APL Wiki](https://aplwiki.com/wiki/Reduce)

Monadic operator `f/` (or reduice-[first](#first axis)`f⌿`)

## Tradfn

## Valence

## Variable