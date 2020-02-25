# PRISM Models

The following PRISM models and properties are available:

* [Simple Proxy model](./simple-proxy-ctmc.prism): A CTMC model for a client-server system in which a client process invokes a server process via a simple proxy, with no resiliency pattern implemented.

* [Retry model](./retry-ctmc.prism): A CTMC model for a client-server system in which a client process invokes 
a server process using the Retry pattern.

* [Static Circuit Breaker model](./static-circuit-breaker-ctmc.prism): A CTMC model for a client-server system in which a client process invokes a server process using a static variation of the Circuit Breaker pattern. The Circuit Breaker timeout value is constant.

* [Dynamic Circuit Breaker model](./dynamic-circuit-breaker-ctmc.prism): A CTMC model for a client-server system in which a client process invokes a server process using a dynamic variation of the Circuit Breaker pattern. The Circuit Breaker timeout value is dynamically defined.

* [Properties](./patterns-ctmc.props): Model properties to be checked in the above models using PRISM.

See our [ICSA 2020 paper](../publications/ICSA2020.pdf) for a more detailed description of each model.
