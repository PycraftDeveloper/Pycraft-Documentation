Introduction
==========

Welcome to Pycraft's new formatting guide!
In this guide you will learn more about the structure that we follow in the source code for Pycraft. To start with, it is not mandatory that this is read before you start work on Pycraft, and nor os it a replacement for the excellent PEP-8 Guide for code formatting in Python - it is however an extension of this concept. This guide aims to maintain a constant style of formatting through Pycraft and its sister projects (for example the Installer), in order to make it easier to transfer from code written by one developer to another. If you are confused by the structure of Pycraft, or by something in this guide then don't hesitate to get in touch (ways of how to do so can be found in the Introduction tab). Each area in this guide will feature a description, an example (likely not taken from Pycraft for simplicity), our reasoning for this decision, any additional information regarding this formatting feature in Pycraft's source code and be preceeded by a text description about what that section of the guide is for.

Docstring Formatting Guide
==========

Welcome to Pycraft's docstring formatting guide. Docstrings are a relatively recent addition to the source code of Pycraft - only being introduced in Pycraft v9.5.5 as structural changed allowed for the use of docstrings to be effective -, and act as text descriptions and overviews of the function of that area of code, as well as that area's required parameters, keyword arguments and outputs. Currently any subroutine (procedure or function) and class must have a docstring, with the exception of a class instantiation method with no function; which can be identified as being identical to:

.. code-block:: python
   :linenos:

   def __init__(self):
      pass

Module Formatting Guide
==========



Class Formatting Guide
==========



Subroutine Formatting Guide
==========



Variable and Constant Formatting Guide
==========



Shader Formatting Guide
==========



Directory Formatting Guide
==========



