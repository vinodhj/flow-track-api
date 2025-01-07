# Flow-Tracker-API

Flow-Tracker-API is a robust backend service designed for seamless expense tracking and financial management. This project leverages modern technologies and best practices to ensure scalability, maintainability, and high performance.

## Features

- **Expense Tracking:** Track income, expenses, and budgets efficiently.
- **GraphQL API:** Powerful and flexible GraphQL APIs for data querying and mutation.
- **Microservices Architecture:** Modular design with independent services for improved scalability.
- **GraphQL Mesh Gateway:** Unified GraphQL gateway for integrating multiple microservices.
- **TypeScript:** Ensuring type safety and enhanced development experience.
- **Node.js:** Fast and scalable backend runtime.

## Technologies Used

### Core Stack
- **Backend:** Node.js
- **Programming Language:** TypeScript
- **API:** GraphQL
- **Gateway:** GraphQL Mesh

### Architecture
- **Microservices:** Services are split into distinct units for modular development and deployment.
- **Gateway:** GraphQL Mesh is used as the unified gateway to aggregate and expose data from all services.

### Additional Tools
- **Database:** D1 db
- **Testing:** Jest for unit and integration testing.
- **Containerization:** Docker for easy deployment and scaling.


## Project Structure

```
flow-tracker-api/
├── src/
│   ├── gateway/       # GraphQL Mesh gateway setup
│   ├── services/      # Microservices implementations
│   ├── utils/         # Shared utilities
│   ├── types/         # TypeScript type definitions
│   ├── resolvers/     # GraphQL resolvers
│   └── index.ts       # Entry point
├── tests/             # Test cases
├── .env.example       # Example environment configuration
├── package.json       # Project metadata and dependencies
├── README.md          # Project documentation
└── tsconfig.json      # TypeScript configuration
```

## Contributing

Contributions are welcome! Please follow these steps to contribute:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-name`).
3. Make your changes and commit them (`git commit -m 'Add feature'`).
4. Push to the branch (`git push origin feature-name`).
5. Open a pull request.

## License

This project is licensed under the [MIT License](LICENSE).
