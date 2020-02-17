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

## 






[df1]: <https://www.redhat.com/en/topics/microservices/what-is-istio>
