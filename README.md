# RekValdNets

## Project Overview

RekValdNets is designed to facilitate the exchange of data between data purchasers and validators on the Request Network, a decentralized data marketplace. This platform connects data purchasers with data providers (validators) to ensure a seamless and secure transfer of information.

### Vision

RekValdNets aims to create a decentralized and transparent data marketplace where data purchasers can easily access high-quality data from trusted validators. By leveraging the Request Network, RekValdNets ensures secure, reliable, and efficient data transactions, promoting the growth of decentralized finance and data exchange.

### Key Components

- **RekValdNets Marketplace**: This user interface allows data purchasers to browse and register with validators. Validators use this UI to register their services.
- **Request Network Validator Server**: This server acts as a mediator that relays requests between data purchasers and validators, ensuring decentralization and avoiding single points of failure.
- **Validator Output Server**: Operated by validators, this server setup provides data to purchasers via API endpoints.

Data purchasers register through the RekValdNets UI and can access data from their chosen validators based on their subscription plan. Validators register their services through the RekValdNets UI and set up their Validator Node to serve data to purchasers.

## Technical Overview

RekValdNets is built using modern web technologies and blockchain protocols to ensure security, scalability, and ease of use. The following components and technologies are integral to the project:

- **Frontend**: The RekValdNets Marketplace is built with React.js to provide a responsive and dynamic user experience.
- **Backend**: The Request Network Validator Server is built with Node.js, facilitating communication between data purchasers and validators.
- **Blockchain Integration**: The platform leverages the Request Network protocol to handle secure and transparent data transactions.
- **API Endpoints**: Validator Output Servers provide data via RESTful API endpoints, ensuring easy integration and data retrieval for purchasers.

## User Guides

This project caters to three main user groups, each with dedicated guides to help you get started:

- **[Data Purchasers](DATA_PURCHASER.md)**: If you're interested in purchasing data, refer to the Data Purchaser Guide for instructions on how to register and access data.
- **[Validators](VALIDATOR.md)**: Validators looking to sell data on the Request Network should check out the Validator Setup Instructions for a comprehensive guide on setting up and maintaining a Validator node.
- **[Contributors/Developers](CONTRIBUTING.md)**: Developers interested in contributing to the project can find local development setup and contribution guidelines in the Developer Guide.

## Getting Started

For more detailed information and to begin your interaction with RekValdNets, please refer to the respective user guides linked above. Whether you're a data purchaser, a validator, or a developer, these guides will provide the necessary steps to engage with the platform effectively.

## Resources

- [Request Network main repository](https://github.com/RequestNetwork/requestNetwork)
- [Join the Request Hub](https://request-slack.herokuapp.com/)
- [Documentation website](http://docs.request.network)

By offering these examples and resources, RekValdNets aims to support users in building innovative solutions using the Request Network, fostering the growth of decentralized financial applications and data marketplaces.