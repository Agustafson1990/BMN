# BMN

ByteMe Networks public operations repository.

## Purpose

This repository is used to manage public operational resources for ByteMe Networks, LLC, including:

- SSH public key distribution
- Automation scripts
- Deployment references
- Infrastructure standards
- Internal operational templates

## Intended Use

Servers may pull approved public files from this repository using scheduled sync jobs.

Examples:

- authorized_keys files
- shell scripts
- deployment templates
- documentation

## Security Rules

This repository must never contain:

- Private SSH keys
- Passwords
- API tokens
- .env files
- Customer data
- Internal secrets
- Payment credentials

Only public operational materials belong here.

## Current Structure

```text
SSH-Keys/
Scripts/
Docs/
Templates/
