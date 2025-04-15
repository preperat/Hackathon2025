# Hackathon2025 - LLM Infrastructure Proposal

## Overview
This repository contains the infrastructure proposal and documentation for the OMC hackathon focusing on Large Language Model (LLM) exploration. The architecture enables OMC employees to experiment with different LLM models while maintaining secure authentication through the existing OMC ADFS system, with added Retrieval Augmented Generation (RAG) capabilities.

## Key Features
- Integration with OMC ADFS for secure authentication
- Support for three different LLM models:
  - Llama 3 70B (Meta's flagship model)
  - CodeLlama 34B (specialized for code generation)
  - DeepSeek Coder 7B (efficient coding model)
- RAG capabilities for document-based knowledge augmentation
- Secure, network-isolated environment
- Persistent chat history and user preferences

## Documentation
The main documentation is available in the `Docs` directory:
- [Infrastructure Proposal (Markdown)](Docs/InfraProposal.md)
- [Infrastructure Proposal (PDF)](Docs/LLM-InfraProposal.pdf)
- [Architecture Diagram](Docs/aws-architecture.png)

## Technical Architecture
The infrastructure is designed to run on AWS with the following key components:
- Authentication Layer (OMC ADFS integration)
- User Interface (Open WebUI)
- Backend Infrastructure (Auto Scaling Groups)
- RAG Components (Document processing, vector database)
- Network Security and Data Privacy Controls

## Security Features
- End-to-end encryption for all communications
- Network isolation for LLM instances
- Zero-knowledge architecture
- Strict access controls
- Complete data privacy controls

## Getting Started
For detailed setup instructions and implementation guidelines, please refer to the [Infrastructure Proposal](Docs/InfraProposal.md).

## Contributing
This repository is part of the OMC hackathon initiative. For contribution guidelines, please contact the project maintainers.

## License
This project is proprietary and confidential. All rights reserved.

## Contact
For questions or support regarding this infrastructure proposal, please contact the OMC IT team. 