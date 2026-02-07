## Yandex Go

Name: Yandex Go

Link: <https://yandex.ru/go/>

Description: Yandex Go is a cloud-based service that provides a platform for building and deploying Go applications.

## Main components

Yandex GO component diagram

We have API Gateway, which is a gateway that allows you to connect your applications to the Yandex Go platform. It is responsible for routing requests to the appropriate services and handling authentication and authorization.

Core services are the ones that are responsible for the actual work of the application.

## Data flow

![Data flow](diagrams/out/yandex-go/architecture-component/Component%20Diagram.svg)
![Link](diagrams/src/yandex-go/architecture-component.puml)

In this group of steps we will describe the data flow of the application.

The application will be built using the Go programming language. The application will communicate with the Yandex Go platform using the API Gateway.

## Deployment

![Deployment](diagrams/out/yandex-go/architecture-deployment/Deployment%20Diagram.svg)
![Link](diagrams/src/yandex-go/architecture-deployment.puml)

Components will be deployed to the cloud using the Yandex Go platform.

## Assumptions

-I assume the pricing service handles surge pricing calculations based on demand and supply in real-time.

-I assume the pricing service has a queue of incoming requests to process.

-I assume the pricing service has a queue of outgoing requests to process.

## Open questions

How does the actual load balancing mechanism work between the microservices in production?

How does the actual load balancing mechanism work between the microservices in production?
