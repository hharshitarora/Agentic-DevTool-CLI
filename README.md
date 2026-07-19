# Agentic DevTool CLI

As a Founding Engineer, I created the Agentic DevTool CLI—a mission-critical tool for observability and secret management in agentic development workflows. This project emphasizes efficiency and security in the modern AI development lifecycle.

## Technical Stack

- **Frontier LLM Orchestration**: Integrated secret management and observability trace streaming.
- **Backend**: Node.js CLI built with Commander.js.
- **Observability**: Direct streaming to Honeycomb for performance analysis.

## Impact

An essential side project for developers building AI agents, providing a standardized way to manage secrets and monitor agent behavior, leading to faster debugging and more secure deployments.

## Infrastructure

The infrastructure for this project is managed using Terraform.
See the [terraform/](./terraform/) directory for configuration details.

## Installation

```bash
npm install
npm run build
npm link
```

## Usage

```bash
agentic-cli secret-init
agentic-cli trace-stream
```
