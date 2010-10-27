================================================
Pydenticons - Identicon implementation in Python
================================================

All meaningful source by Shin Adachi <shn@glucose.jp>.

setup.py by James Socol.


Requirements
============

Requires PIL.


Usage
=====

Usage is pretty simple::

    import pydenticons
    pydenticons.render_identicon(code, size)

Where `code` is an integer or long (maybe an integer MD5) and `size` is
1/3 of the length of a side. (ie: if `size = 12`, the image is `36x36`.)

Return a PIL Image class instance which have generated identicon image.
`size` specifies patch size. Generated image size is 3 * `size`.
