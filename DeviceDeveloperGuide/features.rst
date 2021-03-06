Features
========

Platform Architecture and Modules
---------------------------------

.. table:: Platform Architecture and Modules

   +-----------------------------------+-----------------------------------+
   | Feature                           | Version                           |
   +===================================+===================================+
   | Core Architecture                 | 9.0.2                             |
   +-----------------------------------+-----------------------------------+
   | UI Extension                      | 9.0.2                             |
   +-----------------------------------+-----------------------------------+
   | Network Extension                 | 6.1.4                             |
   +-----------------------------------+-----------------------------------+
   | File System Extension             | 3.0.0                             |
   +-----------------------------------+-----------------------------------+
   | HAL Extension                     | 1.0.4                             |
   +-----------------------------------+-----------------------------------+

Foundation Libraries
--------------------

.. table:: Foundation Libraries

   +-----------------------+-----------------------+-----------------------+
   | Name                  | Reference             | Versions              |
   +=======================+=======================+=======================+
   | BON                   | [B-ON]                | 1.2                   |
   +-----------------------+-----------------------+-----------------------+
   | DEVICE                |                       | 1.0                   |
   +-----------------------+-----------------------+-----------------------+
   | ECOM                  |                       | 1.1                   |
   +-----------------------+-----------------------+-----------------------+
   | ECOM-COMM             |                       | 1.1                   |
   +-----------------------+-----------------------+-----------------------+
   | EDC                   | [EDC]                 | 1.2                   |
   +-----------------------+-----------------------+-----------------------+
   | FS                    |                       | 2.0                   |
   +-----------------------+-----------------------+-----------------------+
   | HAL                   |                       | 1.0                   |
   +-----------------------+-----------------------+-----------------------+
   | KF                    | [KF]                  | 1.4                   |
   +-----------------------+-----------------------+-----------------------+
   | MICROUI               | [MUI]                 | 2.0                   |
   +-----------------------+-----------------------+-----------------------+
   | NET                   |                       | 1.1                   |
   +-----------------------+-----------------------+-----------------------+
   | NLS                   |                       | 2.0                   |
   +-----------------------+-----------------------+-----------------------+
   | SNI                   | [SNI]                 | 1.2                   |
   +-----------------------+-----------------------+-----------------------+
   | SP                    | [SP]                  | 2.0                   |
   +-----------------------+-----------------------+-----------------------+
   | SSL                   |                       | 2.0                   |
   +-----------------------+-----------------------+-----------------------+

Platform Characteristics
------------------------

.. table:: Platform Characteristics

    +---------------+-----------------+----------------------------------+-----------------------------------+-------------------+
    | Name          | Item            | MicroEJ platform Characteristics | MicroEJ simulator Characteristics | User Configurable |
    +===============+=================+==================================+===================================+===================+
    |               | Heap Partition  | 1                                | 1                                 |                   |
    |               +-----------------+----------------------------------+-----------------------------------+-------------------+
    | RAM Optimizer | Immortal Space  | Yes                              | Yes                               | Yes               |
    |               +-----------------+----------------------------------+-----------------------------------+-------------------+
    |               | Immutable Space | Yes (static)                     | Yes (static)                      |                   |
    +---------------+-----------------+----------------------------------+-----------------------------------+-------------------+
    | Debug         | Symbolic        | No                               | JDWP (Socket)                     | Yes               |
    +---------------+-----------------+----------------------------------+-----------------------------------+-------------------+
    | MicroEJ Code  | Location        | In Flash (in place execution)    | n/a                               |                   |
    +---------------+-----------------+----------------------------------+-----------------------------------+-------------------+

..
   | Copyright 2008-2020, MicroEJ Corp. Content in this space is free 
   for read and redistribute. Except if otherwise stated, modification 
   is subject to MicroEJ Corp prior approval.
   | MicroEJ is a trademark of MicroEJ Corp. All other trademarks and 
   copyrights are the property of their respective owners.
