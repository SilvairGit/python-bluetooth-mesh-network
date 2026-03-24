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
  salt and key derivation helpers (`s1`, `k1`, `k2`, `k3`, `k4`), and
  key wrappers for application, device, and network keys
- **Mesh message handling**: network PDU packing/unpacking for access,
  control, proxy configuration, and proxy solicitation messages, plus
  nonce helpers and segmented access message packing
- **Beacons**: unprovisioned device, secure network, and private mesh
  beacon parsing/packing
- **Provisioning**: provisioning PDU parsing/building, provisioning
  bearer control and generic provisioning transaction handling, and
  provisioning encryption/decryption helpers

Installation
------------

This project requires Python 3.14.

You can install "bluetooth-mesh-network" via `pip`_ from `PyPI`_::

    $ pip install bluetooth-mesh-network

You can also add it to a Poetry-managed project::

    $ poetry add bluetooth-mesh-network

If you want to work on this repository locally, install the project and development
dependencies with Poetry::

    $ poetry install

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
