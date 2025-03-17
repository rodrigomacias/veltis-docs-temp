# Veltis Documentation

Documentation for Veltis - Biotech IP Tokenization Platform

## Overview

This repository contains the documentation for the Veltis platform, which enables users to create, fractionalize, list, and trade IP NFTs (Intellectual Property Non-Fungible Tokens) in a decentralized marketplace.

## Documentation Structure

The documentation is organized into the following sections:

- **User Guides**: Instructions for using the Veltis platform
- **API Documentation**: Details about the backend API endpoints
- **Smart Contract Documentation**: Information about the smart contracts
- **Development Guides**: Guides for developers working on the Veltis platform
- **Deployment Guides**: Instructions for deploying the Veltis platform

## Tech Stack

- Docusaurus for documentation framework
- GitHub Pages for hosting
- Swagger/OpenAPI for API documentation

## Prerequisites

- Node.js (v16 or higher)
- npm or yarn

## Development Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/Veltiscapital/veltis-docs.git
   cd veltis-docs
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Start the development server:
   ```bash
   npm start
   ```

4. Open your browser and navigate to `http://localhost:3000`

## Building the Documentation

To build the documentation for production:

```bash
npm run build
```

The build artifacts will be stored in the `build/` directory.

## Deployment

The documentation is deployed to GitHub Pages. The deployment is automated through GitHub Actions when changes are pushed to the main branch.

## Contributing

We welcome contributions to the Veltis documentation! To contribute:

1. Fork the repository
2. Create a new branch for your changes
3. Make your changes
4. Submit a pull request

## Documentation Sections

### User Guides

- Getting Started
- Creating an IP NFT
- Fractionalizing an IP NFT
- Trading IP NFTs and Fractions
- Managing Your Portfolio

### API Documentation

- Authentication
- NFT Endpoints
- Fractionalization Endpoints
- Marketplace Endpoints
- User Endpoints

### Smart Contract Documentation

- IPNFTRegistry
- SimpleIPNFTRegistry
- FractionalizationFactory
- Marketplace

### Development Guides

- Setting Up the Development Environment
- Frontend Development
- Backend Development
- Smart Contract Development
- Testing

### Deployment Guides

- Frontend Deployment
- Backend Deployment
- Smart Contract Deployment

## License

This project is licensed under the MIT License - see the LICENSE file for details.