..
  Warning: Do not edit this file. It is automatically generated and your
  changes will be overwritten. The tool to do so lives in the
  openstack-doc-tools repository.

.. list-table:: Description of configuration options for ``[filter-slo]`` in ``proxy-server.conf``
   :header-rows: 1
   :class: config-ref-table

   * - Configuration option = Default value
     - Description
   * - ``max_get_time`` = ``86400``
     - Time limit on GET requests (seconds)
   * - ``max_manifest_segments`` = ``1000``
     - Maximum number of segments.
   * - ``max_manifest_size`` = ``2097152``
     - Maximum size of segments.
   * - ``min_segment_size`` = ``1048576``
     - Minimum size of segments.
   * - ``rate_limit_after_segment`` = ``10``
     - Rate limit the download of large object segments after this segment is downloaded.
   * - ``rate_limit_segments_per_sec`` = ``0``
     - Rate limit large object downloads at this rate. contact for a normal request. You can use '* replicas' at the end to have it use the number given times the number of replicas for the ring being used for the request. paste.deploy to use for auth. To use tempauth set to:
   * - ``use`` = ``egg:swift#slo``
     - Entry point of paste.deploy in the server.
