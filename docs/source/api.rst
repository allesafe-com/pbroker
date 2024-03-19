
API Reference
=============


.. _pybroker-api-broker:

Broker
------

.. autoclass:: pybroker.api.Broker
    :members: grab, find, serve, stop, show_stats


.. _pybroker-api-proxy:

Proxy
-----

.. autoclass:: pybroker.proxy.Proxy
    :members: create, types, is_working, avg_resp_time, geo, error_rate, get_log
    :member-order: groupwise


.. _pybroker-api-provider:

Provider
--------

.. autoclass:: pybroker.providers.Provider
    :members: proxies, get_proxies
    :member-order: groupwise
