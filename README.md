# HubSpot MCP Server

A Model Context Protocol (MCP) server for integrating HubSpot with GenAI applications.

## Overview

CRM, Marketing, Sales and Service Hub integration

## Features

- Comprehensive HubSpot API coverage
- Multiple authentication methods
- Enterprise-ready with rate limiting
- Full error handling and retry logic
- Async support for better performance

## Installation

```bash
pip install hubspot-mcp-server
```

Or install from source:

```bash
git clone https://github.com/asklokesh/hubspot-mcp-server.git
cd hubspot-mcp-server
pip install -e .
```

## Configuration

Create a `.env` file or set environment variables according to HubSpot API requirements.

## Quick Start

```python
from hubspot_mcp import HubspotMCPServer

# Initialize the server
server = HubspotMCPServer()

# Start the server
server.start()
```

## License

MIT License - see LICENSE file for details
