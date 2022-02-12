# seminar-wise21-deltaslim

Group 3: Delta-slim triangles

This is a project which originated as part of a seminar on hyperbolic geometry. The aim is to visualise the delta hypernbolicity of the hyperbolic space by triangles in the Poincaré disk and half-plane model.\
These visuilasations rely on the python package [hyperbolic](https://github.com/cduck/hyperbolic) by Casey Duckering. 

## Deltahyperbolicity and delta-slim triangles

It is easy to imagine how spheric triangles are “fatter” than Euclidian ones. 
Just like this, hyperbolic triangles look slimmer in comparison. 
Gromov used this property to generalize hyperbolic spaces.
Imagine delta-neighborhoods of the sides of a triangle. 
If every edge of a triangle is covered by the delta neighborhoods of the two other edges, the triangle is called delta-slim.
If every triangle on a space has this property, then the space is also delta-slim.
A metric space is hyperbolic, if there is a delta so that every triangle is delta-slim 
This implies the existence of a global delta in hyperbolic spaces. 
Our project had the aim to visualize the delta neighborhoods for different triangles in the Poincaré disk model,
to compute the minimal delta for different triangles, 
and to show how these minimal deltas interplay with the global solution.

## Setup

hyperbolic is available on PyPI:
```
$ pip3 install hyperbolic
```

Install drawSvg also to display the hyperbolic geometry:
```
$ pip3 install drawSvg
```

## Examples

Choose points interactively in this [widget](https://github.com/hegl-lab/proseminar-wise21-deltaslim/blob/main/examples/widget.ipynb) and explore deltaslim triabgles in the Poincaré disk model.\
Images produced may look like this:

![Triangle with deltaneigbourhood](https://github.com/hegl-lab/proseminar-wise21-deltaslim/blob/main/examples/images/poincare_triangle_nbh.png)

![Triangle with surrounding Triangle](https://github.com/hegl-lab/proseminar-wise21-deltaslim/blob/main/examples/images/poincare_triangle_2_surroundingIdealTriangle.png)

See these Jupyter [notebooks](https://github.com/hegl-lab/proseminar-wise21-deltaslim/tree/main/examples) to view the examples:

- [Poincaré disk](https://github.com/hegl-lab/proseminar-wise21-deltaslim/blob/main/examples/poincare.ipynb)
- [Half-plane](https://github.com/hegl-lab/proseminar-wise21-deltaslim/blob/main/examples/halfplane.ipynb)

This distribution is found:

![histogram](https://github.com/hegl-lab/proseminar-wise21-deltaslim/blob/main/examples/images/histo_3000_64_4.png)

