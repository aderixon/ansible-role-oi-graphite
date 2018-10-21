oi-graphite
===========

Install and configure the Graphite metrics storage monitoring system on
OpenIndiana Hipster.


Limitations
-----------

 * Not all permission issues resolved.
 * Only configures single, local instance.
 * whisper.py requires monkey patching for the fallocate bug on ZFS: see
   https://github.com/graphite-project/whisper/issues/79
 * Still a work in progress.


Author
------

Ade Rixon, http://www.big-bubbles.org.uk/


Acknowledgements
----------------

Outline install and Django setup code taken from
https://github.com/nsg/ansible-graphite
