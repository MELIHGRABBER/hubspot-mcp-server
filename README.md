# HubSpot MCP Server

<div align="center">

# Hubspot Mcp Server

[![GitHub stars](https://img.shields.io/github/stars/LokiMCPUniverse/hubspot-mcp-server?style=social)](https://github.com/LokiMCPUniverse/hubspot-mcp-server/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/LokiMCPUniverse/hubspot-mcp-server?style=social)](https://github.com/LokiMCPUniverse/hubspot-mcp-server/network)
[![GitHub watchers](https://img.shields.io/github/watchers/LokiMCPUniverse/hubspot-mcp-server?style=social)](https://github.com/LokiMCPUniverse/hubspot-mcp-server/watchers)

[![License](https://img.shields.io/github/license/LokiMCPUniverse/hubspot-mcp-server?style=for-the-badge)](https://github.com/LokiMCPUniverse/hubspot-mcp-server/blob/main/LICENSE)
[![Issues](https://img.shields.io/github/issues/LokiMCPUniverse/hubspot-mcp-server?style=for-the-badge)](https://github.com/LokiMCPUniverse/hubspot-mcp-server/issues)
[![Pull Requests](https://img.shields.io/github/issues-pr/LokiMCPUniverse/hubspot-mcp-server?style=for-the-badge)](https://github.com/LokiMCPUniverse/hubspot-mcp-server/pulls)
[![Last Commit](https://img.shields.io/github/last-commit/LokiMCPUniverse/hubspot-mcp-server?style=for-the-badge)](https://github.com/LokiMCPUniverse/hubspot-mcp-server/commits)

[![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://python.org)
[![MCP](https://img.shields.io/badge/Model_Context_Protocol-DC143C?style=for-the-badge)](https://modelcontextprotocol.io)

[![Commit Activity](https://img.shields.io/github/commit-activity/m/LokiMCPUniverse/hubspot-mcp-server?style=flat-square)](https://github.com/LokiMCPUniverse/hubspot-mcp-server/pulse)
[![Code Size](https://img.shields.io/github/languages/code-size/LokiMCPUniverse/hubspot-mcp-server?style=flat-square)](https://github.com/LokiMCPUniverse/hubspot-mcp-server)
[![Contributors](https://img.shields.io/github/contributors/LokiMCPUniverse/hubspot-mcp-server?style=flat-square)](https://github.com/LokiMCPUniverse/hubspot-mcp-server/graphs/contributors)

</div>

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
