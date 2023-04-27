@def title = "Franklin Sandbox n.1"
@def hasmath = true
@def hascode = true

# Set up

## Update title

## Update config.md file

* change author

* add site name for GitHub

## Create a table of contents (optional)

\toc

## Upload using GitHub Desktop

# Examples

## How to enter text

## How to render math equations

## How to insert Julia code (with outputs!)

## How to insert a table from a CSV file

## How to insert and image file

## How to insert a clickable thumbnail to a Youtube video

## How to inject raw HTML

<!--# Franklin syntax sandbox

This page is meant as a sandbox for Franklin Syntax so that you can quickly practice or experience things.

## Sandbox

Write whatever you want here to practice Franklin Syntax:

```julia:./ex1
using LinearAlgebra, Random
Random.seed!(135)
a, b = randn(50), randn(50)
println(dot(a, b))
println(sum(ai * bi for (ai, bi) ∈ zip(a, b)))
```

\output{./ex1}

(yet another example that floating point arithmetics can be complicated).

$$ \forall x \in \R:\quad \scal{x, x} \ge 0 $$

\newcommand{\E}{\mathbb E}

Surely some people remember the ordering, but I always forget:

$$ \varphi(\E[X]) \le \E[\varphi(X)] $$

for $\varphi$ convex.
-->