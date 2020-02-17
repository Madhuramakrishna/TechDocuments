# This is xCode documentation is to understand TechStacks

## Jaeger

Jaeger, inspired by Dapper and OpenZipkin, is a distributed tracing system released as open source by Uber Technologies. It is used for monitoring and troubleshooting microservices-based distributed systems, including:

   - Distributed context propagation
   - Distributed transaction monitoring
   - Root cause analysis
   - Service dependency analysis
   - Performance / latency optimization

##  Istio  
Istio is an open source service mesh platform that provides a way to control how microservices share data with one another. It includes APIs that let Istio integrate into any logging platform, telemetry, or policy system. Istio is designed to run in a variety of environments: on-premise, cloud-hosted, in Kubernetes containers, in services running on virtual machines, and more.

Istio’s architecture is divided into the data plane and the control plane. In the data plane, Istio support is added to a service by deploying a sidecar proxy within your environment. This sidecar proxy sits alongside a microservice and routes requests to and from other proxies. Together, these proxies form a mesh network that intercepts network communication between microservices. The control plane manages and configures proxies to route traffic. The control plane also configures components to enforce policies and collect telemetry. [ReadMore][df1] 

## Java UUID Generator (JUG)

Java UUID Generator (JUG) is a Java library for generating Universally Unique IDentifiers, UUIDs (see http://en.wikipedia.org/wiki/UUID). It can be used either as a component in a bigger application, or as a standalone command line tool.


## Monix
Asynchronous Programming for Scala and Scala.js

Monix is a high-performance Scala / Scala.js library for composing asynchronous, event-based programs.

It started as a proper implementation of ReactiveX, with stronger functional programming influences and designed from the ground up for back-pressure and made to cleanly interact with Scala’s standard library, compatible out-of-the-box with the Reactive Streams protocol. It then expanded to include abstractions for suspending side effects and for resource handling, being one of the parents and implementors of cats-effect.

A Typelevel project, Monix proudly exemplifies pure, typeful, functional programming in Scala, while making no compromise on performance.

Highlights:

   - exposes the kick-ass Observable, Iterant, Task and Coeval data types, along with all the support they need
   - modular, only use what you need
   - designed for true asynchronicity, running on both the JVM and Scala.js
   - really good test coverage, code quality and API documentation as a primary project policy


## better-files

better-files is a dependency-free pragmatic thin Scala wrapper around Java NIO. It is an alternative to the IO interface present in the Scala standard library and defines idiomatic helpers to handle IO in a sane and elegant way.

## Quicklens
Quicklens is a small library which allows to modify deeply nested fields in case classes e.g.: modify(person)(_.address.street.name). using(_. toUpperCase) , without the need to create dedicated lens objects








[df1]: <https://www.redhat.com/en/topics/microservices/what-is-istio>
