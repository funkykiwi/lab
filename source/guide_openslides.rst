.. highlight:: console

.. author:: ullli <uli@alternativschule-berlin.de>
.. tag:: lang-python
.. tag:: plenary meetings and conferences
.. tag:: web

.. sidebar:: About

  .. image:: _static/images/pretix.svg
      :align: center

##########
openslides
##########

.. tag_list::

OpenSlides is a all-in-one solution for running plenary meetings and conferences. The current presentation is shown on the main screen, while the agenda, motions, list of speakers on others. Working on elections and documents in parallel with all participants is possible.

----

.. note:: For this guide you should be familiar with the basic concepts of

  * :manual:`Python <lang-python>` and its package manager pip
  * :manual:`supervisord <daemons-supervisord>`

License
=======

All relevant legal information can be found here

  * https://github.com/OpenSlides/OpenSlides/blob/master/LICENSE

Prerequisites
=============

.. include:: includes/my-print-defaults.rst

Your URL needs to be setup:

::

 [isabell@stardust ~]$ uberspace web domain list
 isabell.uber.space
 [isabell@stardust ~]$

Installation
============

Step 1
------
