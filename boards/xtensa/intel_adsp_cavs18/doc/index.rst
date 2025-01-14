.. _intel_adsp_cavs18:

Intel ADSP CAVS 1.8
###################

Overview
********

This board configuration is used to run Zephyr on the Intel CAVS 1.8 Audio DSP.
This configuration is present, for example, on Intel `Whiskey Lake`_ microprocessors.
Refer to :ref:`intel_adsp_generic` for more details on Intel ADSP ACE and CAVS.

System requirements
*******************

Xtensa Toolchain
----------------

If you choose to build with the Xtensa toolchain instead of the Zephyr SDK, set
the following environment variables specific to the board in addition to the
Xtensa toolchain environment variables listed in :ref:`intel_adsp_generic`.

.. code-block:: shell

   export TOOLCHAIN_VER=RG-2017.8-linux
   export XTENSA_CORE=X6H3CNL_2017_8

Programming and Debugging
*************************

Refer to :ref:`intel_adsp_generic` for generic instructions on programming and
debugging applicable to all CAVS and ACE platforms.

.. _Whiskey Lake: https://www.intel.com/content/www/us/en/products/platforms/details/whiskey-lake.html
