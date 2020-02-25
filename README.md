# Resiliency Pattern Models

This repository contains a collection of [microservice relisiency patterns](https://docs.microsoft.com/en-us/azure/architecture/patterns/category/resiliency) modeled as Continuous-Time Markov Chains (CTMC) using the [PRISM](https://www.prismmodelchecker.org/) probabilistic model checker. 

The collection is under development and so far includes CTMC models for the following resiliency patterns:

* [Retry pattern](https://docs.microsoft.com/en-us/azure/architecture/patterns/retry)
* [Circuit Breaker pattern](https://docs.microsoft.com/en-us/azure/architecture/patterns/circuit-breaker)

These two pattern models are described and analyzed in our companion ICSA 2020 paper (link below).

See the PRISM [documentation](https://www.prismmodelchecker.org/doc/) to learn more about its CTMC specification language and how to use the tool to analyze CTMC models.

Please contact us if you have any question or would like to contribute to improve our pattern catalog.

## Publications

MENDONÇA, N. C., ADERALDO, C. M., CÁMARA, J., GARLAN, D. "Model-Based Analysis of Microservice Resiliency Patterns." In: IEEE International Conference on Software Architecture (ICSA 2020), Salvador, Brazil. [[PDF]](/publications/ICSA2020.pdf)

