.. _preFile:

Predicted Data File
===================

predicted data files output from **tdrh_v2.exe** contain the transmitter, receiver and time indecies as well as the predicted data. The order of the data points is in the same order as the :ref:`survey index file <indexFile>`. Predicted data files take the format:

|
| :ref:`tx_ind<tdrh_pre_ln1>` :math:`\;` :ref:`rx_ind<tdrh_pre_ln2>` :math:`\;` :ref:`t_ind<tdrh_pre_ln3>` :math:`\;` :ref:`data_opt<tdrh_pre_ln4>` :math:`\;` :ref:`data<tdrh_pre_ln5>`
| :ref:`tx_ind<tdrh_pre_ln1>` :math:`\;` :ref:`rx_ind<tdrh_pre_ln2>` :math:`\;` :ref:`t_ind<tdrh_pre_ln3>` :math:`\;` :ref:`data_opt<tdrh_pre_ln4>` :math:`\;` :ref:`data<tdrh_pre_ln5>`
| :ref:`tx_ind<tdrh_pre_ln1>` :math:`\;` :ref:`rx_ind<tdrh_pre_ln2>` :math:`\;` :ref:`t_ind<tdrh_pre_ln3>` :math:`\;` :ref:`data_opt<tdrh_pre_ln4>` :math:`\;` :ref:`data<tdrh_pre_ln5>`
| :math:`\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\; \vdots`
| :ref:`tx_ind<tdrh_pre_ln1>` :math:`\;` :ref:`rx_ind<tdrh_pre_ln2>` :math:`\;` :ref:`t_ind<tdrh_pre_ln3>` :math:`\;` :ref:`data_opt<tdrh_pre_ln4>` :math:`\;` :ref:`data<tdrh_pre_ln5>`
|
|
|



Click here to `see an example file <https://github.com/ubcgif/tdrh/raw/tdrh_v2/assets/supporting_files/dpred.txt>`__ for an airborne TEM survey.


**Parameter Descriptions**


.. _tdrh_pre_ln1:

**tx_ind:** The index corresponding to the desired transmitter within the :ref:`transmitter file<receiverFile>`. 

.. _tdrh_pre_ln2:

**rx_ind:** The index corresponding to the desired receiver within the :ref:`receiver file<receiverFile>`.

.. _tdrh_pre_ln3:

**t_ind:** The index corresponding to the desired time within the :ref:`time channel file<timeFile>`.

.. _tdrh_pre_ln4:

**data_opt:**

    - A flag value of ??? is entered if the datum is the magnetic field *H* in units A/m
    - A flag value of ??? is entered if the datum is the time-derivative *dB/dt* in units T/s

.. _tdrh_pre_ln5:

**data:** The datum. Either H or dB/dt

