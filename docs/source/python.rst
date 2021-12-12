Python
=====

.. _installation:

Installation
------------

To use Lamadava, first install it using pip:

.. code-block:: console

   $ pip install lamadava

Usage
------------

You need to pass the key to the Client and call the function you want to get the result

For example:

>>> from lamadava import Client
>>> cl = Client(api_key="")
>>> cl.a1_user("user")
