Change Log
==========
New in version 1.3.5
--------------------
* Bug fix for HashClient when retries is set to zero.
* Adding the VERSION command to the clients.

New in version 1.3.4
--------------------
* Bug fix for the HashClient that corrects behavior when there are no working servers.

New in version 1.3.3
--------------------
* Adding caching to the Travis build.
* A bug fix for pluggable hashing in HashClient.
* Adding a default_noreply argument to the Client ctor.

New in version 1.3.2
--------------------
* Making the location of Memcache Exceptions backwards compatible.

New in version 1.3.0
--------------------
* Python 3 Support
* Introduced HashClient that uses consistent hasing for allocating keys across many memcached nodes. It also can detect servers going down and rebalance keys across the available nodes.
* Retry sock.recv() when it raises EINTR

New in version 1.2.9
--------------------
* Introduced PooledClient a thread-safe pool of clients

