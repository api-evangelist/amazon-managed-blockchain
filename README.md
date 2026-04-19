# Amazon Managed Blockchain (amazon-managed-blockchain)
Amazon Managed Blockchain is a fully managed service that allows you to create and manage scalable blockchain networks using popular open-source frameworks such as Hyperledger Fabric and Ethereum. It eliminates the overhead required to create the network or join a public network, and automatically scales to meet the demands of thousands of applications running millions of transactions.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/amazon-managed-blockchain/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - AWS, Blockchain, Distributed Ledger, Hyperledger Fabric, Ethereum

## Timestamps

- **Created:** 2024-01-15
- **Modified:** 2026-04-19

## APIs

### Amazon Managed Blockchain API
The Amazon Managed Blockchain API provides a fully managed service for creating and managing scalable blockchain networks using open-source frameworks such as Hyperledger Fabric and Ethereum. Covers 27 operations for networks, members, nodes, proposals, invitations, and accessors management.

**Human URL:** [https://aws.amazon.com/managed-blockchain/](https://aws.amazon.com/managed-blockchain/)

#### Tags:

 - Blockchain, Distributed Ledger, Hyperledger Fabric, Ethereum

#### Properties

- [Documentation](https://docs.aws.amazon.com/managed-blockchain/)
- [OpenAPI](openapi/amazon-managed-blockchain-openapi-original.yaml)
- [GettingStarted](https://aws.amazon.com/managed-blockchain/getting-started/)
- [Pricing](https://aws.amazon.com/managed-blockchain/pricing/)
- [FAQ](https://aws.amazon.com/managed-blockchain/faqs/)

## Common Properties

- [Portal](https://aws.amazon.com/managed-blockchain/)
- [Documentation](https://docs.aws.amazon.com/managed-blockchain/)
- [TermsOfService](https://aws.amazon.com/service-terms/)
- [PrivacyPolicy](https://aws.amazon.com/privacy/)
- [Support](https://aws.amazon.com/premiumsupport/)
- [GitHubOrganization](https://github.com/aws)
- [Console](https://console.aws.amazon.com/managedblockchain/)
- [SignUp](https://portal.aws.amazon.com/billing/signup)
- [Login](https://signin.aws.amazon.com/)
- [StatusPage](https://health.aws.amazon.com/health/status)
- [Contact](https://aws.amazon.com/contact-us/)
- [SpectralRules](rules/amazon-managed-blockchain-spectral-rules.yml)
- [Vocabulary](vocabulary/amazon-managed-blockchain-vocabulary.yaml)
- [NaftikoCapability](capabilities/blockchain-network-operations.yaml)

## Features

| Name | Description |
|------|-------------|
| Hyperledger Fabric Support | Create permissioned blockchain networks using Hyperledger Fabric framework. |
| Ethereum Support | Create and participate in public Ethereum networks. |
| Network Member Management | Invite AWS accounts to join your network as members and manage their access. |
| Peer Node Management | Create and manage peer nodes to participate in blockchain network transactions. |
| Proposal and Voting | Create and vote on proposals to manage network configuration changes. |

## Use Cases

| Name | Description |
|------|-------------|
| Supply Chain Transparency | Track products through supply chains with immutable blockchain records shared across organizations. |
| Financial Settlement | Automate financial settlement processes with smart contracts on Hyperledger Fabric. |
| Healthcare Data Sharing | Share patient data securely across healthcare providers using blockchain consent records. |
| Digital Asset Management | Manage digital assets and NFTs on Ethereum through a fully managed blockchain service. |

## Integrations

| Name | Description |
|------|-------------|
| Amazon S3 | Store blockchain application code and configuration in S3 buckets. |
| AWS KMS | Encrypt blockchain network data using AWS Key Management Service. |
| Amazon CloudWatch | Monitor blockchain node and network metrics in CloudWatch. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Amazon Managed Blockchain OpenAPI](openapi/amazon-managed-blockchain-openapi-original.yaml)

### JSON Schema

153 schema files available in the [json-schema/](json-schema/) directory.

### JSON Structure

153 structure files available in the [json-structure/](json-structure/) directory.

### JSON-LD

- [Amazon Managed Blockchain Context](json-ld/amazon-managed-blockchain-context.jsonld)

### Examples

153 example files available in the [examples/](examples/) directory.

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [Amazon Managed Blockchain](capabilities/shared/managed-blockchain.yaml) — 6 operations for network, member, and node management

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Blockchain Network Operations](capabilities/blockchain-network-operations.yaml) | Amazon Managed Blockchain | 6 | Blockchain Architect, Blockchain Developer |

## Vocabulary

- [Amazon Managed Blockchain Vocabulary](vocabulary/amazon-managed-blockchain-vocabulary.yaml) — Unified taxonomy mapping 6 resources, 6 actions, 1 workflow, and 2 personas

## Rules

- [Amazon Managed Blockchain Spectral Rules](rules/amazon-managed-blockchain-spectral-rules.yml) — 18 rules across 7 categories

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
