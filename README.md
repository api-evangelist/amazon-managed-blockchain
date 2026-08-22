# Amazon Managed Blockchain (amazon-managed-blockchain)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

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
