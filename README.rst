Conway's Game of Life
=====================

Simple pygame implementation of Conway's Game of Life.

.. contents::

Screenshot
----------

.. image:: screenshots/screenshot.png


Installation
------------

Install with pip::

  pip install Main

Running
-------

Run via launch script installed with pip package::

  Main

Run as a Python module::

  cd GameLife
  python -m Main

Using inside of code
--------------------

To import the class in to your own code::

  from Main.LifeGame import LifeGame
  LifeGame().run()


Controls
--------

There are a couple keybinds available:

- q - Quit
- s - Start/stop (toggle pause)
- r - Randomize the grid

