..
    Warning: Do not edit this file. It is automatically generated from the
    software project's code and your changes will be overwritten.

    The tool to generate this file lives in openstack-doc-tools repository.

    Please make any changes needed in the code, then run the
    autogenerate-config-doc tool from the openstack-doc-tools repository, or
    ask for help on the documentation mailing list, IRC channel or meeting.

.. _nova-conductor:

.. list-table:: Description of conductor configuration options
   :header-rows: 1
   :class: config-ref-table

   * - Configuration option = Default value
     - Description

   * - ``topic`` = ``conductor``

     - (String) Topic exchange name on which conductor nodes listen.

       - **Deprecated**

         There is no need to let users choose the RPC topic for all services - there is little gain from this. Furthermore, it makes it really easy to break Nova by using this option.

   * - ``workers`` = ``None``

     - (Integer) Number of workers for OpenStack Conductor service. The default will be the number of CPUs available.
