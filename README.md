# Event Calculus, an introduction

This paper is a presentation of Event Calculus (in a barebone, simplified version).
Event calculus is a way to represent reasoning about events and how they interacts with the world around them. It is an extention of first order logic, and can represent concept like consequences of action, inertia, impossible state of the world, etc.

To show how it works, I use Pathfinding as an example.
For now, it only show the formulas needed to define pathfinding in Event Calculus, and present a way to abduct the plan.

## Building the paper

Before building this paper, the following packages need to be installed:

- [latexmk]
  (see [installation instructions][install])

A [Makefile](Makefile) is provided to build the paper:

```sh
$ make
```
