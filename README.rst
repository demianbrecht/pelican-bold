pelican-bold
============

Just another theme for `Pelican`_.

Installation
============

* Clone the repo: ``git clone git://github.com/demianbrecht/pelican-bold.git``
* Set ``THEME`` to the cloned path

Supported features
==================

* Articles
  * Categories
  * Tags
* Pages
* Feeds
* Social

Currently unsupported features
==============================

* Translations
* Links
* Menuitems

Supported settings
==================

* ``FEED_DOMAIN``

  Per-category feed links are rendered along with post category headers.

* ``TWITTER_USERNAME``
* ``DISQUS_SITENAME``
* ``GOOGLE_ANALYTICS``
* ``SOCIAL``

  Social links are icon-only. If you want to add an icon, simply add a 32x32
  icon to ``/static/images/icons`` and add a corresponding entry to
  ``/static/css/base.css`` (``ul.social a[...]``)

Custom settings
===============

There are two settings custom to this theme:

* ``PLUS_ONE``

  This will render a Google "+1" badge with every article

* ``SITESUBTITLES`` (note plurality)

  Using the native Pelican ``SITESUBTITLE`` will render a single site title.
  Using the custom setting will render two stamp strips for the site title as
  shown in the screenshot. It expects a tuple (or list) of two items::

    SITESUBTITLES = ('Left Side', 'Right Side')

.. _`Pelican`: http://docs.getpelican.com/en/3.1.1/
