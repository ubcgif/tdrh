.. _elements:

Elements of the TDRH version 2 package
======================================

This section provides a brief description of each program in the TDRH version 2 package. In addition, we describe the file formats for all input and supporting files used by the coding library.

Program Library
---------------

The main executable programs within the TDRH version 2 program library are:

    - **create_octree_mesh_td_v2:** creates an OcTree mesh based on the survey geometry
    - **tdrh_v2:** used to forward model or invert TEM data

Also included are the following OcTree utility programs:

    - **blk3cellOct:** creates conductivity models on an OcTree mesh
    - **interface_weights:** creates weights on the faces of cells

Main Input Files
----------------

Here, we describe the main input files for executables contained with the TDRH version 2 coding package.

.. tOcTree::
    :maxdepth: 1

    Create OcTree mesh <inputfiles/createOcTree>
    Create OcTree model <inputfiles/createModel>
    Forward modeling <inputfiles/forward>
    Create face weights <inputfiles/weightsFiles>
    Inversion <inputfiles/inversion>


Supporting Files
----------------

Here, we describe the formats of supporting files used to run TDRH executable files. The input files for each executable program are described in the :ref:`running the programs<running>` section.

.. toctree::
    :maxdepth: 1

    Survey Index File <files/indexFile>
    Observations File <files/obsFile>
    Predicted Data File <files/preFile>
    Time Channels File <files/timeFile>
    Transmitter/Receiver File <files/receiverFile>
    Topography File <files/topoFile>
    OcTree Mesh File <files/octree_mesh>
    Model File <files/model>
    Model and Face Weights Files <files/weights>
    Wave File <files/waveFile>












