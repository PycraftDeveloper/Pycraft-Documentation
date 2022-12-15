ConditionalRender
=================

.. py:module:: moderngl.conditional_renderer
.. py:currentmodule:: moderngl

.. autoclass:: ConditionalRender

Attributes
----------

.. autoattribute:: ConditionalRender.mglo

Examples
--------

.. rubric:: Simple conditional rendering example

.. code-block:: python

    query = ctx.query(any_samples=True)

    with query:
        vao1.render()

    with query.crender:
        print('This will always get printed')
        vao2.render()  # But this will be rendered only if vao1 has passing samples.

.. toctree::
    :maxdepth: 2
