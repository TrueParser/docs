# TrueParser Documentation

This repository contains the source code for the official TrueParser documentation, powered by [Mintlify](https://mintlify.com).

## Project Overview

TrueParser is a unified orchestration platform for technical document parsing. This documentation is divided into two primary sections:

1.  **[Platform Guides](/index)**: Introduction, Quickstart, and Dashboard guides.
2.  **[API Reference](/api-reference/endpoints)**: Detailed endpoint documentation for document ingestion and lifecycle management.

Join our [Discord](https://discord.gg/trueparser) to connect with the community.

---

## Development

To preview changes locally, you'll need the [Mintlify CLI](https://www.npmjs.com/package/mint).

### Installation

```bash
npm i -g mint
```

### Local Preview

Run the following command at the root of the repository:

```bash
mint dev
```

Your local preview will be available at `http://localhost:3000`.

## Publishing

Changes pushed to the `main` branch are automatically deployed via the Mintlify GitHub App.

## Maintenance

- **`docs.json`**: Controls the sidebar navigation and global theme configuration.
- **`dashboard/`**: Documentation for Dashboard account and resource management.
- **`api-reference/`**: Endpoint specifications.

### AI-assisted writing

To use Mintlify's documentation skills with your AI coding tool:

```bash
npx skills add https://mintlify.com/docs
```

---

_For technical support, contact the TrueParser team or visit [trueparser.com](https://trueparser.com)._
