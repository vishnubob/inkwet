# Ink Wet

This is a place holder for inkwet, which is my plan to build a python library
to generalize algorithmic computational designs in two dimensions.  The rough
outline of features I'm trying to build are:

- A comprehensive 2D vector layer
- Boolean construction
- Wide export compatibility
- Best practices SVG export
- Intelligent curve classes
- Node support (eg. NodeBox)
- Optimization algorithms (eg. pontiff)
- Laser cutter and vinyl cutter layout optimization
- TrueType support
- More ideas to come.

## Related projects

I've written a collection of 2D design programs in python over the past few
years, and some of the work is generalizable and appropriate for inkwet.

- [pontiff](https://github.com/vishnubob/pontiff)
- [snowflake](https://github.com/vishnubob/snowflake)
- [lsystem](https://github.com/vishnubob/lsystem)
- [twodee](https://github.com/vishnubob/twodee)
- [harmonograph](https://github.com/vishnubob/harmonograph)
- [cubism](https://github.com/vishnubob/pycon2016/tree/master/cubism)

These are some influences:

- [NodeBox](https://github.com/nodebox/nodebox)
- [Processing](http://py.processing.org/)

## Motivation

I use python to generate designs for 2D fabrication.  For example, laser
cutters or vinyl cutters.  I cover this topic in my PyCon 2016 talk "[Laser
Cutters, 3D Printers, and
Python](https://www.youtube.com/watch?v=UwL-ncEr-_I)".  Check it out for more
information.

When I approach a new design, I find myself reinventing the wheel and repeating
myself.  This library will be a focal point for these use cases with the goal
of making richer and fuller computational designs with explicit design intent. 

The last comprehensive-leaning library I built was
[pyscad](https://github.com/vishnubob/pyscad).  This taught me a lot about the
power of algorithmic constructive geometry, but it was my first attempt at a
library within this domain.  pyscad, however, suffered from a few catastrophic
defects: it was too complicated, it was not documented, and I was the only
user. I am, therefore, setting a new bar for this library: to attract at
least one user who isn't me.

## The name is ... weird?

When I name a new open source project, I roughly follow these priorities:

1. **non-offensive** (this is not difficult)
2. **unique** (this **is** difficult)
3. **consistent** (`unicorn_dynamite` is rarely appropriate)
4. **easy** (short is sweet)
5. **fun** (fun to type, for example)

## Interested?

Do you enjoy constructing 2D designs from python?  Want a general purpose
toolkit?  Step up, and lend me your ideas and code.

