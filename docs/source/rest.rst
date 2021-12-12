Usage
=====

.. _installation:

Installation
------------

To use Lamadava, first install it using pip:

.. code-block:: console

   (.venv) $ pip install lamadava

Creating recipes
----------------

To retrieve a list of random ingredients,
you can use the ``lamadava.get_random_ingredients()`` function:

.. autofunction:: lamadava.get_random_ingredients

The ``kind`` parameter should be either ``"meat"``, ``"fish"``,
or ``"veggies"``. Otherwise, :py:func:`lamadava.get_random_ingredients`
will raise an exception.

.. autoexception:: lamadava.InvalidKindError

For example:

>>> from lamadava import Client
>>> cl = Client(api_key="")
>>> cl.a1_user("user")
