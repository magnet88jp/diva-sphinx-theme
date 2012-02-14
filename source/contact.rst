===============================
テーマのサンプル (Theme sample)
===============================

これは ``trstyle`` テーマのサンプルです.
Donec sed odio dui. Cras justo odio, dapibus ac facilisis in,
egestas eget quam. Vestibulum id ligula porta felis euismod semper.
Fusce dapibus, tellus ac cursus commodo, tortor mauris condimentum nibh,
ut fermentum massa justo sit amet risus.

   Donec sed odio dui. Cras justo odio, dapibus ac facilisis in,
   egestas eget quam. Vestibulum id ligula porta felis euismod semper.
   Fusce dapibus, tellus ac cursus commodo, tortor mauris condimentum nibh,
   ut fermentum massa justo sit amet risus.

Donec sed odio dui. Cras justo odio, dapibus ac facilisis in,
egestas eget quam. Vestibulum id ligula porta felis euismod semper.


Heading Level2
==============
Donec sed odio dui. Cras justo odio, dapibus ac facilisis in,
egestas eget quam. Vestibulum id ligula porta felis euismod semper.
Fusce dapibus, tellus ac cursus commodo, tortor mauris condimentum nibh,
ut fermentum massa justo sit amet risus.

Heading Level3
--------------
Donec sed odio dui. Cras justo odio, dapibus ac facilisis in,
egestas eget quam. Vestibulum id ligula porta felis euismod semper.
Fusce dapibus, tellus ac cursus commodo, tortor mauris condimentum nibh,
ut fermentum massa justo sit amet risus.

Heading Level4
~~~~~~~~~~~~~~
Donec sed odio dui. Cras justo odio, dapibus ac facilisis in,
egestas eget quam. Vestibulum id ligula porta felis euismod semper.
Fusce dapibus, tellus ac cursus commodo, tortor mauris condimentum nibh,
ut fermentum massa justo sit amet risus.

Heading Level5
^^^^^^^^^^^^^^
Donec sed odio dui. Cras justo odio, dapibus ac facilisis in,
egestas eget quam. Vestibulum id ligula porta felis euismod semper.
Fusce dapibus, tellus ac cursus commodo, tortor mauris condimentum nibh,
ut fermentum massa justo sit amet risus.

Heading Level6
``````````````
Donec sed odio dui. Cras justo odio, dapibus ac facilisis in,
egestas eget quam. Vestibulum id ligula porta felis euismod semper.
Fusce dapibus, tellus ac cursus commodo, tortor mauris condimentum nibh,
ut fermentum massa justo sit amet risus.


Admonitions
===========

.. danger::
   This is sample of "Danger" admonition directive.

.. error::
   This is sample of "Error" admonition directive.

.. warning::
   This is sample of "Warning" admonition directive.

.. caution::
   This is sample of "Caution" admonition directive.

.. attention::
   This is sample of "Attention" admonition directive.

.. important::
   This is sample of "Important" admonition directive.

.. note::
   This is sample of "Note" admonition directive.

.. hint::
   This is sample of "Hint" admonition directive.

.. tip::
   This is sample of "Tip" admonition directive.

.. admonition:: Here is admonition title

   This is sample of "Admonition" admonition directive.

   - One
   - Two
   - Three


sphinx.ext.todo
===============

.. todo::
   This is sample of "todo" directive.

Literal Block
=============

.. code-block:: python

   import sys

   Usage = """
   Usage:
   $ python factorial.py 
   """

   def fact(x):
       if x == 0:
           return 1
       else:
           return x * fact(x-1)

   if (len(sys.argv)>1) :
       print fact(int(sys.argv[1]))
   else:
       print Usage

.. code-block:: python

   >>> from pygments.styles import STYLE_MAP
   >>> STYLE_MAP.keys()
   ['default', 'emacs', 'friendly', 'colorful']


Field List
=============

:Name: sphinxjp.themes.trstyle
:Author: junichi KAKISAKO
:License: MIT
:long long field name: This should be in the same line as the field name.
