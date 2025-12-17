=========================
bluetooth-mesh-network
=========================

.. image:: https://img.shields.io/pypi/v/bluetooth-mesh-network.svg
   :target: https://pypi.org/project/bluetooth-mesh-network
   :alt: PyPI version

.. image:: https://img.shields.io/pypi/pyversions/bluetooth-mesh-network.svg
   :target: https://pypi.org/project/bluetooth-mesh-network
   :alt: Python versions

----

Bluetooth mesh network layer library for Python provides cryptographic
operations, network PDU encoding/decoding and provisioning support
as defined in Bluetooth SIG specifications.

What is this thing?
--------------------

This library implements the network layer of Bluetooth Mesh protocol,
including security and provisioning mechanisms.

https://www.bluetooth.com/specifications/mesh-specifications

Supported features include:

- **Cryptography**: AES-CCM encryption/decryption, AES-CMAC, AES-ECB,
  key derivation functions (network key, application key, device key)
- **Network layer**: Network PDU encoding/decoding, beacon parsing
  (Unprovisioned Device, Secure Network, Private Mesh)
- **Provisioning**: Generic Provisioning PDU support

Installation
------------

You can install "bluetooth-mesh-network" via `pip`_ from `PyPI`_::

    $ pip install bluetooth-mesh-network

Contributing
------------

Contributions are very welcome. Tests can be run with `pytest`_, please ensure
the coverage at least stays the same before you submit a pull request.

License
-------

Distributed under the terms of the `GPL-2.0`_ license, "bluetooth-mesh-network" is
free and open source software.

Issues
------

If you encounter any problems, please `file an issue`_ along with a detailed description.

.. _`GPL-2.0`: http://opensource.org/licenses/GPL-2.0
.. _`file an issue`: https://github.com/SilvairGit/python-bluetooth-mesh-network/issues
.. _`pytest`: https://github.com/pytest-dev/pytest
.. _`pip`: https://pypi.org/project/pip/
.. _`PyPI`: https://pypi.org/project
