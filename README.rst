Introduction
============

.. image:: https://readthedocs.org/projects/circuitpython-wiiclassic/badge/?version=latest
    :target: https://circuitpython-wiiclassic.readthedocs.io/
    :alt: Documentation Status

.. image:: https://img.shields.io/discord/327254708534116352.svg
    :target: https://adafru.it/discord
    :alt: Discord

.. image:: https://github.com/jfurcean/CircuitPython_WiiClassic/workflows/Build%20CI/badge.svg
    :target: https://github.com/jfurcean/CircuitPython_WiiClassic/actions
    :alt: Build Status

.. image:: https://img.shields.io/badge/code%20style-black-000000.svg
    :target: https://github.com/psf/black
    :alt: Code Style: Black

CircuitPython library for the Nintendo Wii Classic Controller


Dependencies
=============
This driver depends on:

* `Adafruit CircuitPython <https://github.com/adafruit/circuitpython>`_
* `Bus Device <https://github.com/adafruit/Adafruit_CircuitPython_BusDevice>`_

Please ensure all dependencies are available on the CircuitPython filesystem.
This is easily achieved by downloading
`the Adafruit library and driver bundle <https://circuitpython.org/libraries>`_.


Usage Example
=============

.. code-block:: python

    import board
    import wiiclassic

    controller = wiiclassic.WiiClassic(board.I2C())

Contributing
============

Contributions are welcome! Please read our `Code of Conduct
<https://github.com/jfurcean/CircuitPython_WiiClassic/blob/master/CODE_OF_CONDUCT.md>`_
before contributing to help this project stay welcoming.

Documentation
=============

For information on building library documentation, please check out `this guide <https://learn.adafruit.com/creating-and-sharing-a-circuitpython-library/sharing-our-docs-on-readthedocs#sphinx-5-1>`_.
