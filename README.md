# Coraltalk Documentation

Customer-facing documentation for Coraltalk AI platform, built with Mintlify.

## Quick Start

```bash
# Install Mintlify CLI (if not already installed)
npm i -g mint

# Start local development server
mint dev

# Opens at http://localhost:3000
```

## Documentation Pages

### Getting Started (5 pages)
- **index.mdx** — Welcome page and overview
- **quickstart-coraltalk.mdx** — 5-minute quickstart for all user types
- **getting-started/introduction.mdx** — Detailed introduction
- **getting-started/for-teachers.mdx** — Complete teacher guide
- **getting-started/for-students.mdx** — Complete student guide

### Teaching Assistant (1 page)
- **teaching-assistant/customize-ta.mdx** — Configure Coral's personality and behavior

### Assessments (1 page)
- **assessments/oral-assignments.mdx** — Create and manage AI-evaluated oral assessments

### Integrations (1 page)
- **integrations/canvas-integration.mdx** — Canvas LMS LTI 1.3 setup

### Help (1 page)
- **troubleshooting/common-issues.mdx** — Comprehensive troubleshooting guide

## Total: 9 Pages

All pages include:
- Rich Mintlify components (Steps, Accordions, Tabs, Cards)
- Cross-references to related guides
- Practical examples and code samples
- Clear navigation paths

## Development Commands

```bash
mint dev              # Start dev server (http://localhost:3000)
mint dev --port 3333  # Use custom port
mint broken-links     # Check for broken links
mint update           # Update Mintlify CLI
```

## Requirements

- Node.js v19 or higher
- Mintlify CLI

## Configuration

All settings in `docs.json`:
- Navigation structure
- Theme colors (cyan: #0E7490)
- Logo and favicon
- Global anchors (demo, app)
- Social links

## Support

- **Email**: support@coraltalk.com
- **App**: https://coraltalk.com
- **Demo**: https://coraltalk.com/demo-req
