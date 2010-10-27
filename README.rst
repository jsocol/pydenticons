================================================
Pydenticons - Identicon implementation in Python
================================================

All meaningful source by Shin Adachi <shn@glucose.jp>.
setup.py by James Socol


Requirements
============

Requires PIL.


Usage
=====

    import pydenticons
    pydenticons.render_identicon(code, size)

Return a PIL Image class instance which have generated identicon image.
`size` specifies patch size. Generated image size is 3 * `size`.
