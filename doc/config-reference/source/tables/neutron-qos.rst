..
    Warning: Do not edit this file. It is automatically generated from the
    software project's code and your changes will be overwritten.

    The tool to generate this file lives in openstack-doc-tools repository.

    Please make any changes needed in the code, then run the
    autogenerate-config-doc tool from the openstack-doc-tools repository, or
    ask for help on the documentation mailing list, IRC channel or meeting.

.. _neutron-qos:

.. list-table:: Description of QoS configuration options
   :header-rows: 1
   :class: config-ref-table

   * - Configuration option = Default value
     - Description
   * - **[QOS]**
     -
   * - ``kernel_hz`` = ``250``
     - (Integer) Value of host kernel tick rate (hz) for calculating minimum burst value in bandwidth limit rules for a port with QoS. See kernel configuration file for HZ value and tc-tbf manual for more information.
   * - ``tbf_latency`` = ``50``
     - (Integer) Value of latency (ms) for calculating size of queue for a port with QoS. See tc-tbf manual for more information.
