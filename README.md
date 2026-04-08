# Telnyx KnowledgeBase

The official source of truth for all Telnyx product documentation. Content in this repo is automatically synced to [support.telnyx.com](https://support.telnyx.com).

## Overview

This repository contains Telnyx's customer-facing product documentation in Markdown format. Engineering squads own and maintain the docs for their products — not just the initial write-up, but ongoing updates as features change and evolve.

**support.telnyx.com** automatically tracks this repo for new files and updates, so merging to `main` means publishing to customers.

## Repository Structure

```
docs/
├── voice/              # Voice & SIP products
├── messaging/          # SMS, MMS, 10DLC
├── numbers/            # Phone numbers, porting
├── networking/         # IP, private networking
├── wireless/           # IoT, SIM management
├── ai/                 # AI products & APIs
├── storage/            # Cloud storage
├── identity/           # Verify, lookup
├── fax/                # Fax services
└── account/            # Billing, portal, API keys
```

> **Note:** This structure is a starting point. Squads should organize their docs in whatever way makes sense for their product area.

## For Telnyx Engineering Squads

You own your product docs. That means:

1. **Write docs when you ship** — new product or feature = new or updated doc
2. **Keep them current** — if the product changes, the docs change too
3. **All changes via PR** — every merge requires approval from a maintainer

### Quick Start

```bash
git clone git@github.com:team-telnyx/KnowledgeBase.git
cd KnowledgeBase
git checkout -b docs/your-product-update
# Make your changes
git push origin docs/your-product-update
# Open a PR
```

## For Customers & Community

We welcome contributions that improve accuracy and clarity! See [CONTRIBUTING.md](.github/CONTRIBUTING.md) for details on what's in scope and how to submit changes.

## File Format

All documentation files must be **Markdown (`.md`)**. This keeps things simple, version-controllable, and compatible with the support site's rendering pipeline.

## Publishing

Merging to `main` = publishing to [support.telnyx.com](https://support.telnyx.com). The site syncs automatically — no manual deployment needed.

**Review carefully before approving PRs.** What gets merged is what customers see.
