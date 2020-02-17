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

Istio’s architecture is divided into the data plane and the control plane. In the data plane, Istio support is added to a service by deploying a sidecar proxy within your environment. This sidecar proxy sits alongside a microservice and routes requests to and from other proxies. Together, these proxies form a mesh network that intercepts network communication between microservices. The control plane manages and configures proxies to route traffic. The control plane also configures components to enforce policies and collect telemetry. [ReadMore][istio] 

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


## chopsticks

chopsticks is an essential collection of Scala libraries for everyday use. It's designed specifically to build high performance, production-grade functional reactive stream systems.

## Caffeine

Caffeine is an awesome Java caching library. It has an impressive performance and a neat Java 8 API. ... So this is the thinner wrapper we can came with to make Caffeine easy and idiomatic to use in Scala.


## PureConfig 

PureConfig is a nifty library that serves as a front-end for other libraries. ... PureConfig is not a configuration library. It can be seen as a better front-end for existing libraries. It uses the Typesafe Config library for loading raw configurations and then uses the raw configurations to do its magic.

## Enumeratum 

Enumeratum is a type-safe and powerful enumeration implementation for Scala that offers exhaustive pattern match warnings, integrations with popular Scala libraries, and idiomatic usage that won't break your IDE.

## Jsoniter Scala. 

Scala macros that generate codecs for case classes, standard types, and collections to get maximum performance of JSON parsing and serialization.

## Cloudhopper SMPP

Efficient, scalable, rock-solid, and flexible Java implementation of the Short Messaging Peer to Peer Protocol (SMPP).
Twitter exclusively relies on this library for its global SMS infrastructure.  [ReadMore][cloudhopper-smpp] 

## Netty 

Netty is a NIO client server framework which enables quick and easy development of network applications such as protocol servers and clients. It greatly simplifies and streamlines network programming such as TCP and UDP socket server.

## Avro4s

Avro4s is a schema/class generation and serializing/deserializing library for Avro written in Scala. The objective is to allow seamless use with Scala without the need to to write boilerplate conversions yourself, and without the runtime overhead of reflection. Hence, this is a macro based library and generates code for use with Avro at compile time.

The features of the library are:
-  Schema generation from classes at compile time
-  Boilerplate free serialization of Scala types into Avro types
-  Boilerplate free deserialization of Avro types to Scala types

## embedded-kafka

A library that provides an in-memory Kafka instance to run your tests against.

## akka-http-json

Akka HTTP’s marshalling and unmarshalling infrastructure makes it rather easy to seamlessly convert application-domain objects from and to JSON. 

## RocksDB 

RocksDB is an embeddable persistent key-value store for fast storage. RocksDB can also be the foundation for a client-server database but our current focus is on embedded workloads.

#### RocksDB JNI

RocksDB JNI gives you a Java interface to the RocksDB C++ library which is an embeddable persistent key-value store for fast storage.

## MetalLB

MetalLB is a load-balancer implementation for bare metal Kubernetes clusters, using standard routing protocols.

## Calico

Calico is an open source networking and network security solution for containers, virtual machines, and native host-based workloads. Calico supports a broad range of platforms including Kubernetes, OpenShift, Docker EE, OpenStack, and bare metal services.

Calico combines flexible networking capabilities with run-anywhere security enforcement to provide a solution with native Linux kernel performance and true cloud-native scalability. Calico provides developers and cluster operators with a consistent experience and set of capabilities whether running in public cloud or on-prem, on a single node or across a multi-thousand node cluster. [ReadMore][Calico] 

## Grafana 

Grafana allows you to query, visualize, alert on and understand your metrics no matter where they are stored. Create, explore, and share dashboards with your team and foster a data driven culture.

## Prometheus

An open-source monitoring system with a dimensional data model, flexible query language, efficient time series database and modern alerting approach.

## Prometheus Operator 

Prometheus Operator creates/configures/manages Prometheus clusters atop Kubernetes - coreos/prometheus-operator.

## Confluent Kafka 

Confluent Kafka is a fully managed Kafka service and enterprise stream processing platform. Real-time data streaming for AWS, GCP, Azure or serverless

## Strimzi Kafka Operator

Strimzi provides a way to run an Apache Kafka cluster on Kubernetes in various deployment configurations.

## Sbt 

sbt (Scala Build tool) is an open-source build tool for Scala and Java projects, similar to Java's Maven and Ant. Its main features are: Native support for compiling Scala code and integrating with many Scala test frameworks. Continuous compilation, testing, and deployment.

[istio]: <https://www.redhat.com/en/topics/microservices/what-is-istio>
[cloudhopper-smpp]: <https://github.com/fizzed/cloudhopper-smpp>
[Calico]: <https://docs.projectcalico.org/introduction/>
