yawd-admin, a django administration website
======================================================

.. image:: docs/yawd-admin-screenshot.png
	:align: center

yawd-admin is an
administration website for django. It extends the default django admin
site and offers the following:

* A clean and beautiful bootstrap user interface
* Hand-written pure HTML5/CSS3 code with indented HTML output
* Responsive interface, optimized for mobile phones and tablets
* Register custom database settings (options) editable from the UI. You can use all **standard django form fields** for these settings
* Integration with google analytics for displaying statistics in the admin home page
* Register your applications to the top-bar navigation
* Refurbished original django admin widgets
* Mechanism for opening the original django admin popup windows with fancybox
* Seamless integration with `yawd-translations` for multilingual admin websites

History
==============

v0.8.0
++++++++++++
is developped under django 1.9.5 and does NOT work with older Django releases.

v0.7.4
++++++++++++
is developped under django 1.8.x and does NOT work with older Django releases.
Installation : pip -e git+https://github.com/mwolff44/yawd-admin.git@0.7.4#egg=yawd-admin

v0.7.2
++++++++++++
is developped under django 1.7.x and does NOT work with older Django releases.

v0.7.1
++++++++++++
is developped under django 1.6.x and does NOT work with older Django releases.

v0.7.0
++++++
is developed under Django 1.5.x and does NOT work with older Django releases.

v0.6.1
++++++

is the last version intended to work with Django 1.4. New features will not be backported to the ``0.6.x`` branch. Since many of us run production systems tied to Django 1.4, both v0.6.1 and the latest documentation will be online on readthedocs.org.

Usage and demo
==============

IMPORTANT : installation information is not up to date ! to get this repo do not use pypi for the moment but clone this repo !

See the `yawd-admin documentation <http://yawd-admin.readthedocs.org/en/latest/>`_
for information on how to install the demo and use yawd-admin.

Screenshots
===========

Side navigation for change forms
++++++++++++++++++++++++++++++++

.. image:: docs/yawd-admin-affix.png
	:align: center

Sortable changelists
++++++++++++++++++++

.. image:: docs/sortable-changelists.png
	:align: center

Modal inlines
+++++++++++++

.. image:: docs/contacts-email-addresses.png
	:align: left

Admin db options
++++++++++++++++

.. image:: docs/admin-options-full.png
