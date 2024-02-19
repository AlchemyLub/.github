# FloralHub

This organization contains a collection of microservices for a non-existing aggregator of flower shops. The purpose of this repository is to provide a tutorial for understanding fault tolerance patterns and exploring code examples related to microservices architecture.

## Purpose
The main objective of this repository is to serve as a learning resource for developers interested in understanding fault tolerance patterns in microservices architecture. By studying the code and examples provided in this repository, users can gain a better understanding of how to design and implement resilient microservices.

## Disclaimer
It is important to note that the services and information provided in this repository are purely fictional and do not correspond to any real services or flower shops. The purpose of the code and examples is solely for educational and tutorial purposes.

## Repository Structure
The repository is structured in a way that highlights different fault tolerance patterns commonly used in microservices architectures. Each microservice focuses on a specific aspect of the flower shop aggregator system.

The following are the key components included in this repository:

1. Florist: service responsible for aggregating various flower stores and their products, including pricing, availability, and location.

2. Gatekeeper: service is used to securely manage and control access to resources and confidential information within the organization. Used in conjunction with [Zitadel](https://zitadel.com/). 

3. DeliveryControlCenter: service manages the logistics of delivering flowers from different stores to the specified addresses.

4. FeedbackForge: service handles customer ratings and reviews for the flower stores, delivery service, and overall customer experience.

5. EventHub: service provides management of the event system and also stores a history of changes.

6. PaymentDefender: service manages the processing of payments for the floral orders, ensuring secure transactions and compliance with different payment methods.

7. Notifier: service sends notifications to customers regarding order status, delivery updates, and special promotions.

8. Gateway: service acts as an entry point for client requests, routing those requests to the appropriate microservices.

9. Arch: A service for providing architectural diagrams of a project. Keeps schemes up to date both for a specific service and for the whole project.

Additionally, the repository includes documentation, code examples, and configurations that demonstrate fault tolerance patterns such as circuit breaking, retry mechanisms, and graceful degradation.

## How to Use
To explore the repository and learn from the code examples, follow these steps:

1. Clone the repository to your local machine.
2. Navigate to each microservice directory and review the relevant code, configurations, and documentation.
3. Experiment with different fault tolerance patterns implemented in the microservices. Modify the code and observe the behavior to gain hands-on experience.
4. Refer to the provided tutorials and guides for detailed explanations of the fault tolerance patterns and their implementation.

> Please note that this repository is intended for educational purposes only and should not be deployed in a production environment.

## Contribution
Contributions to this repository are welcomed. If you have any suggestions, improvements, or additional fault tolerance patterns that could be added to the examples, feel free to open a pull request or create an issue.

However, since the purpose of this repository is purely educational, it is important to maintain a clear distinction between fictional services and real services. Please ensure that any contributions align with the goal of providing learning resources rather than creating real-world solutions.

## License
This repository is licensed under the MIT License. See the LICENSE file for more information.
