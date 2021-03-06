=========================================================
Particle swarm optimization (PSO) with constraint support
=========================================================

The ``pyswarm`` package is a gradient-free, evolutionary optimization package 
for python that supports constraints.

What's New
==========

- This version allows for the return of a model object in the second return position.  Particularly, useful if you
are using a package like sklearn and want to return the optimal model object.

- This is the initial release, but it should work out of the box. The syntax is
similar to the other SciPy optimization routines (the ones like ``fmin_slsqp``).
Currently, only a single objective is supported, but with any number of
constraints (or none).

Requirements
============

- NumPy

Installation and download
=========================

See the `package homepage`_ for helpful hints relating to downloading
and installing pyswarm.


Source Code
===========

The latest, bleeding-edge, but working, `code
<https://github.com/tisimst/pyDOE/tree/master/pyswarm>`_
and `documentation source
<https://github.com/tisimst/pyswarm/tree/master/doc/>`_ are
available `on GitHub <https://github.com/tisimst/pyswarm/>`_.

Contact
=======

Any feedback, questions, bug reports, or success stores should
be sent to the `author`_. I'd love to hear from you!

License
=======

This package is provided under two licenses:

1. The *BSD License*
2. Any other that the author approves (just ask!)

References
==========

- `Particle swarm optimization`_ on Wikipedia

.. _author: mailto:tisimst@gmail.com
.. _Particle swarm optimization: http://en.wikipedia.org/wiki/Particle_swarm_optimization
.. _package homepage: http://pythonhosted.org/pyswarm
