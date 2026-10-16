# Awesome-API-Development-Testing

## Top API Development & Testing Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on API Client IDEs, Contract Testing & Filesystem-First Collaboration*  

**Last updated: October 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **API Development & Testing**. These tools enable developers to explore, test, and document APIs—from GUI clients with collection sync to filesystem-first IDEs where API definitions live alongside your code in Git.



**Examples** include Postman, Insomnia, Paw, RapidAPI, Thunder Client, Hoppscotch, HTTPie, Apidog, SwaggerHub, and Stoplight (the category leaders).



**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, Git-native API testing, and open API documentation—ideal for developers, platform teams, and organizations seeking transparent, vendor-independent API workflows.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [Sector Overview & Market Dynamics](#sector-overview--market-dynamics)
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)



## Sector Overview & Market Dynamics

The global API testing market is valued at approximately **$1.85B to $2.85B** (projected to reach over $3.2B with an 18–21% CAGR), while the broader API management ecosystem spans **$8.6B to $10.0B+**. The API development and testing sector is **moderately fragmented**—anchored by major category leaders like Postman and SmartBear, yet fiercely contested by rapid Git-native/open-source alternatives, specialized IDE extensions, and new AI-driven automation tools.



## SaaS/Hosted Platforms

| Platform | Description | Scale (Valuation / Revenue) | Starting Paid Pricing | Free Tier Limits |
| :--- | :--- | :--- | :--- | :--- |
| **[Postman](https://www.postman.com/)** | Industry-standard API platform for designing, building, and testing APIs with collections, mock servers, and automated runs. | **$5.6B valuation** (~$270M ARR) | **$9/user/month** (Solo, billed annually) or **$19/user/month** (Team) | **Free forever plan**: 1 user, unlimited collection runs, unlimited mock servers, and 50 AI credits per month (team collaboration/shared workspaces require paid plans). |
| **[Insomnia](https://insomnia.rest/)** | API client for REST, GraphQL, WebSockets, SSE, and gRPC with design-first spec editing, test suites, and MCP support. | **$2.0B valuation** (~$145M ARR for parent Kong Inc.) | **$12/user/month** (Pro, billed annually) | **Free forever plan (Essentials)**: Up to 3 users for Git Sync projects, unlimited local/cloud projects, and 1,000 mock server requests/month. |
| **[SwaggerHub](https://swagger.io/tools/swaggerhub/)** | Collaborative API design and documentation platform built on OpenAPI, featuring versioning and code generation. | **$1.8B+ valuation** (~$150M+ revenue for parent SmartBear) | **$19/user/month** (Individual, billed annually) or **$49/user/month** (Team) | **Free forever plan**: Up to 3 public APIs, 5 reusable domains, 1 public product portal with SmartBear branding, and 10 testing/AI credits. |
| **[Stoplight](https://stoplight.io/)** | API design-first platform providing visual OpenAPI/AsyncAPI editing, mocking (Prism), and style guide governance (Spectral). | **$1.8B+ valuation** (Acquired by SmartBear) | **$39/user/month** (Startup/Team tier) | **Free forever plan**: Up to 3 user seats, 1 workspace project, visual design editor, and basic API documentation generation. |
| **[RapidAPI](https://rapidapi.com/)** | Global API marketplace and developer hub offering discovery, testing, and monetization across 40,000+ APIs. | **$1.0B valuation** (~$40M ARR; Acquired by Nokia) | **$10/user/month** (Team Hub basic seat) | **Free forever plan**: Free account with basic API testing and marketplace access; individual APIs offer free tiers typically capped at 100–500 requests/day or 500k requests/month. |
| **[Paw](https://paw.cloud/)** | Native macOS API client featuring dynamic values, environment configuration, code generation, and team sync. | **$1.0B valuation** (Acquired by RapidAPI / Nokia) | **Free** ($0 for full Mac client; integrated with RapidAPI Studio) | **Free forever plan**: Completely free for personal and commercial usage with full native macOS feature access and local file storage. |
| **[Hoppscotch Cloud](https://hoppscotch.io/)** | Managed cloud version of the lightweight, open-source API client for REST, GraphQL, SSE, and WebSockets. | **$3M+ valuation** ($3M Seed funded; ~$1M ARR) | **$6/user/month** (Business, billed annually) | **Free forever plan**: Unlimited personal collections, environments, and multi-protocol testing; team workspaces and shared cloud collaboration require paid plans. |
| **[HTTPie Cloud](https://httpie.io/)** | Cloud-synced, visual and web client paired with the popular human-friendly command-line HTTP client. | **~$550k ARR** (Boutique / Bootstrapped developer platform) | **$9/user/month** (Team tier, billed annually) | **Free forever plan**: Unlimited local and incognito requests, cross-device cloud sync for personal libraries, and preview access to HTTPie AI. |
| **[Apidog](https://apidog.com/)** | Unified platform integrating API design, automated testing, mocking, and documentation with OpenAPI synchronization. | **Bootstrapped** (Private, self-funded startup) | **$9/user/month** (Basic, billed annually) | **Free forever plan**: Up to 4 team members, up to 5 projects, 1 sprint branch per project, and unlimited collection runs / mock servers. |
| **[Thunder Client](https://www.thunderclient.com/)** | Lightweight, editor-native REST API client extension for VS Code and JetBrains IDEs. | **Bootstrapped** (Private indie developer tool) | **$3/user/month** (Starter, billed annually) | **Free forever plan**: Free for non-commercial/personal use; limited to basic manual requests (0 automated collection runs, environments/collections limited, advanced protocols require paid plans). |





## Open-Source GitHub Projects



- **[Bruno](https://github.com/usebruno/bruno)**  

  **The most important shift in API client architecture—offline-first, Git-native API testing** (MIT) . **40,000+ GitHub stars** . **Bruno stores collections as plain text files (`.bru` format) on your filesystem**—no cloud sync, no accounts, no lock-in . **What Postman Cloud users get through team sync, Bruno users get through Git**—branches, pull requests, code review, and history work exactly as they do for source code . **Chosen by teams that refuse to put API collections in a proprietary cloud** . **Secret management** stored locally in `.env` files, never synced . **CLI for CI/CD** (`bru run collection.bru`) with exit codes and JUnit reporting . **Desktop app** for macOS, Windows, and Linux . **VS Code extension** for editing `.bru` files in-editor . **The reference implementation for Git-native API clients.**



- **[Hoppscotch](https://github.com/hoppscotch/hoppscotch)**  

  **The most widely adopted open-source API request builder** (MIT) . **75,000+ GitHub stars** . **Lightweight browser-based UI** with collections, environments, and team collaboration . Supports **REST, GraphQL, WebSocket, SSE, MQTT, and Socket.IO** . **Self-hostable** with Docker for teams that want their own instance . **The most accessible open-source alternative to Postman.**



- **[Insomnia (Kong)](https://github.com/Kong/insomnia)**  

  **Open-source API client for REST, GraphQL, gRPC, and WebSockets** (Apache-2.0) . **Cross-platform desktop app** with environment variables, code generation, and plugin ecosystem . **The longest-running open-source API client**—now maintained by Kong .



- **[HTTPie CLI](https://github.com/httpie/cli)**  

  **User-friendly command-line HTTP client** (BSD-3-Clause) . **35,000+ GitHub stars** . **JSON support, syntax highlighting, and intuitive syntax** . **The most popular CLI alternative to curl**—designed for humans, not machines .



- **[curl](https://github.com/curl/curl)**  

  **The universal command-line tool for transferring data with URLs** (curl License) . **37,000+ GitHub stars** . **Supports HTTP, HTTPS, FTP, FTPS, SCP, SFTP, TFTP, DICT, TELNET, LDAP, FILE, and more** . **The foundation of API testing**—every API client ultimately shells out to something curl-like .



- **[REST Client (VS Code)](https://github.com/Huachao/vscode-restclient)**  

  **VS Code extension for sending HTTP requests and viewing responses** (MIT) . **5,000+ GitHub stars** . **Write requests in `.http` files** and execute directly from the editor. **The most popular VS Code-native API testing extension.**



- **[HTTP File Runner](https://github.com/christianhelle/httpfile)**  

  **Cross-platform CLI tool for executing `.http` files** (MIT) . **The simplest way to run HTTP files from scripts and CI pipelines** . **Fills the gap left by IDE-only `.http` runners.**



- **[Swagger UI](https://github.com/swagger-api/swagger-ui)**  

  **Visual documentation for OpenAPI specifications** (Apache-2.0) . **28,000+ GitHub stars** . **The standard for API documentation**—interactive, self-hosted, and framework-agnostic .



- **[Redoc](https://github.com/Redocly/redoc)**  

  **OpenAPI documentation generator** (MIT) . **24,000+ GitHub stars** . **Three-panel design** optimized for reading—not just testing. **The most readable API documentation** in the open-source ecosystem .



- **[OpenAPI Generator](https://github.com/OpenAPITools/openapi-generator)**  

  **Generate API clients, server stubs, and documentation from OpenAPI specs** (Apache-2.0) . **23,000+ GitHub stars** . **Supports 50+ languages and frameworks** . **The standard for SDK generation from specifications.**



- **[Schemathesis](https://github.com/schemathesis/schemathesis)**  

  **Property-based API testing from OpenAPI/GraphQL schemas** (MIT) . **2,700+ GitHub stars** . **Automatically generates test cases that find crashes, validation errors, and spec violations.** **The most rigorous open-source API testing tool**—finds edge cases humans miss .



- **[Dredd](https://github.com/apiaryio/dredd)**  

  **Language-agnostic HTTP API testing framework** (MIT) . **4,200+ GitHub stars** . **Tests API implementations against OpenAPI/Swagger specifications**—catches drift between docs and behavior .



- **[Newman (Postman CLI)](https://github.com/postmanlabs/newman)**  

  **Command-line collection runner for Postman** (Apache-2.0) . **7,000+ GitHub stars** . **Runs Postman collections in CI/CD** with JUnit and HTML reporting . **The bridge between Postman GUI and automated pipelines.**



### Additional Strong Open-Source Options



- **[Kreya](https://github.com/boris-schwarz/kreya)** — Cross-platform API client for gRPC, WebSocket, and REST (open-core) . **The most focused open-source gRPC client.**

- **[gRPCurl](https://github.com/fullstorydev/grpcurl)** — Command-line tool for interacting with gRPC servers (MIT) . **The standard CLI for gRPC testing.**

- **[grpc-ui](https://github.com/fullstorydev/grpcui)** — Interactive web UI for gRPC services (MIT) . **The browser-based gRPC explorer.**

- **[BloomRPC](https://github.com/bloomrpc/bloomrpc)** — GUI client for gRPC services (MIT) . **The desktop gRPC client.**

- **[grpcurl](https://github.com/fullstorydev/grpcurl)** — See above.

- **[Pact](https://github.com/pact-foundation/pact-js)** — Contract testing framework (MIT) . **The standard for consumer-driven contract testing** .

- **[WireMock](https://github.com/wiremock/wiremock)** — HTTP mock server (Apache-2.0) . **6,000+ GitHub stars** . **The standard for API mocking.**

- **[Mockoon](https://github.com/mockoon/mockoon)** — Desktop API mocking tool (MIT) . **6,000+ GitHub stars** . **The most accessible API mocking tool** for local development.

- **[k6](https://github.com/grafana/k6)** — Load testing tool (AGPL-3.0) . **25,000+ GitHub stars** . **The standard for API performance testing.**

- Community **n8n** workflows for API testing automation and collection sync.



**Frameworks for building custom systems**: Combine **Bruno** for Git-native API testing with **Hoppscotch** for browser-based collaboration, **Schemathesis** for property-based testing, **OpenAPI Generator** for SDK generation, **Swagger UI** or **Redoc** for documentation, and **k6** for load testing—creating a fully self-hosted, enterprise-grade API development platform.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- API testing tools handling credentials and production endpoints must follow security best practices and comply with data protection regulations.

- **Bruno represents the most significant architectural shift in API tooling.** It stores collections as plain text files on your filesystem—**no cloud sync, no accounts, no lock-in** . **What Postman Cloud users get through team sync, Bruno users get through Git**—branches, pull requests, code review, and history . **The choice between Postman and Bruno is fundamentally a choice about where your API definitions live.**

- **Property-based testing finds bugs humans miss.** Schemathesis automatically generates test cases from OpenAPI schemas that find crashes, validation errors, and spec violations . **This is the most rigorous approach to API testing in the open-source ecosystem.**

- **Contract testing prevents integration drift.** Dredd tests implementations against specifications . Pact enables consumer-driven contract testing . **Both catch the gap between docs and behavior before production.**

- **CLI tools compose into pipelines.** Newman runs Postman collections in CI . HTTP File Runner executes `.http` files from scripts . **API testing without CI/CD automation is incomplete.**

- Self-hosted open-source solutions require proper security hardening, secret management, and ongoing maintenance. **API credentials in collections must never be committed to Git**—Bruno's local `.env` approach is the correct pattern.



---



**Made for developers, platform teams, and organizations building transparent API testing solutions.**  

Let's make API Development & Testing more open, data-driven, and Git-native.
