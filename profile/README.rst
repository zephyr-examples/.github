A collection of examples demonstrating the use of the Zephyr RTOS. The examples
are arranged into repositories, where each repository focuses on a particular 
piece of functionality.

Prerequisites
*************

It is assumed that the reader is already familiar with the Zephyr RTOS, if not
then see the `Introduction to Zephyr`_ for a high-level overview, and the 
documentation's `Getting Started Guide`_ to start developing.

Getting Started
***************

The examples are structured as `Zephyr Workspace Applications`_ and should
therefore be cloned into the `zephyrproject` folder so that the resulting
directory structure looks like the following:

.. code-block:: none

    zephyrproject/
    ├─── .west/
    │    └─── config
    ├─── zephyr/
    ├─── bootloader/
    ├─── modules/
    ├─── tools/
    └─── <example>/
         └── app/

Each repository contains one or more examples. Each example has a README file
that describes the functionality demonstrated, build and programming
instructions and details of the hardware used for development and testing.

.. _Introduction to Zephyr: https://docs.zephyrproject.org/latest/introduction/index.html
.. _Getting Started Guide: https://docs.zephyrproject.org/latest/develop/getting_started/index.html
.. _Zephyr Workspace Applications: https://docs.zephyrproject.org/latest/develop/application/index.html#zephyr-workspace-application
