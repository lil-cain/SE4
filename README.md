SE4
===

Simple Standard Service Endpoints


Description
-----------

SE4 is intended to provide a simple convention for getting standard service information, including:
* status
* whether service is able to accept requests
* whether service deems itself to be healthy
* more detailed information on health of downstream dependencies

See the [SE4 Spec here](SE4.md)


Advice
------

As with all ideas that developed over time, there are parts of this spec which are slightly inconsistent or that you believe are irrelevant.  We encourage people to take the very simple concept and apply it to their situation.  These simple endpoints have been of great value to the Engineering teams at Beamly.


History
-------

SE4 was the fourth software engineering spec drafted when Beamly first began in 2011, for lack of a better name SE4 stuck.

Originally it was used by one team during an effort to simplify working with finer grained services, the idea being you should not need to know anything about the service in order to discover some basic operational information.  The convention proved very useful and became widely adopted within Beamly to the extent that is now mandatory that all services expose this information.


