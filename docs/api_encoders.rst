.. _api_encoders:

==============
API - Encoders
==============

.. currentmodule:: picamerax

Encoders are typically used by the camera to compress captured images or video
frames for output to disk. However, picamerax also has classes representing
"unencoded" output (raw RGB, etc). Most users will have no direct need to use
these classes directly, but advanced users may find them useful as base classes
for :ref:`custom_encoders`.

.. note::

    It is strongly recommended that you familiarize yourself with the
    :mod:`~picamerax.mmalobj` layer before attempting to understand the encoder
    classes as they deal with several concepts native to that layer.

The inheritance diagram for the following classes is displayed below:

.. image:: images/encoder_classes.*
    :align: center


PiEncoder
=========

.. autoclass:: PiEncoder
    :private-members:


PiVideoEncoder
==============

.. autoclass:: PiVideoEncoder
    :private-members:


PiImageEncoder
==============

.. autoclass:: PiImageEncoder
    :private-members:


PiRawMixin
==========

.. autoclass:: PiRawMixin
    :private-members:


PiCookedVideoEncoder
====================

.. autoclass:: PiCookedVideoEncoder
    :private-members:


PiRawVideoEncoder
=================

.. autoclass:: PiRawVideoEncoder
    :private-members:


PiOneImageEncoder
=================

.. autoclass:: PiOneImageEncoder
    :private-members:


PiMultiImageEncoder
===================

.. autoclass:: PiMultiImageEncoder
    :private-members:


PiRawImageMixin
===============

.. autoclass:: PiRawImageMixin
    :private-members:


PiCookedOneImageEncoder
=======================

.. autoclass:: PiCookedOneImageEncoder
    :private-members:


PiRawOneImageEncoder
====================

.. autoclass:: PiRawOneImageEncoder
    :private-members:


PiCookedMultiImageEncoder
=========================

.. autoclass:: PiCookedMultiImageEncoder
    :private-members:


PiRawMultiImageEncoder
======================

.. autoclass:: PiRawMultiImageEncoder
    :private-members:

