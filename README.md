# InsightFlow API Documentation

Public API reference documentation for the InsightFlow platform, built with [Mintlify](https://mintlify.com).

## What's included

- **102 API endpoints** across 20 resource groups
- Quick Start guide with cURL, JavaScript, and Python examples
- Error handling reference
- Interactive API playground
- OpenAPI 3.0.3 specification

## Development

Install the [Mintlify CLI](https://www.npmjs.com/package/mint):

```bash
npm i -g mint
```

Preview locally:

```bash
mint dev
```

View at `http://localhost:3000`.

## Deployment

Changes pushed to `main` are automatically deployed via the Mintlify GitHub app.

## Structure

```
├── docs.json                  # Site configuration
├── openapi.json               # OpenAPI specification
├── index.mdx                  # Landing page
├── global.css                 # Custom styles
└── api-reference/
    ├── introduction.mdx       # API overview
    ├── quickstart.mdx         # Quick start guide
    ├── errors.mdx             # Error handling
    ├── openapi.json           # OpenAPI spec
    └── [endpoints]/           # 20 endpoint groups
```
