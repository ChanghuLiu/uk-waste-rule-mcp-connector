# RegEvidenceHub Waste

Public connector metadata for the hosted **RegEvidenceHub Waste** MCP service operated by RegEvidenceHub.

## Remote MCP

`https://waste.regevidencehub.com/mcp`

This repository contains public installation and service-discovery metadata for the hosted MCP service.

## What it does

Evidence-linked England waste regulatory preflight for businesses, carriers, brokers, dealers, receiving sites, and waste operators.

## Installation

Use the remote MCP endpoint above, or import the included `.mcp.json` in clients that support MCP configuration files.

## Payment

Agent-native paid MCP actions use x402 where payment is required. Human-facing premium checkout remains available separately through RegEvidenceHub.

## Publisher

RegEvidenceHub — https://www.regevidencehub.com/


## Gemini CLI

Install this connector as a Gemini CLI extension:

```sh
gemini extensions install https://github.com/ChanghuLiu/uk-waste-rule-mcp-connector
```

The Gemini CLI extension connects to the hosted Streamable HTTP MCP endpoint above. Gemini CLI does not automatically sign x402 payments; paid tools may return a payment-required response and need a separate x402-capable payment workflow. Do not put wallet private keys in this extension.
