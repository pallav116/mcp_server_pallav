🔍 MCP File Search Server

A fast Model Context Protocol (MCP) server for quick and context-aware file searches.

![MCP Server](https://img.shields.io/badge/MCP-Server-blue)
![Python](https://img.shields.io/badge/Python-3.8%2B-green)
![License](https://img.shields.io/badge/License-MIT-yellow)

## Features

* Advanced file search with line numbers and context
* Recursive directory scanning
* Context-aware results showing nearby lines
* Case-insensitive matching
* Async/await for better performance
* Configurable limits and context size

## Quick Start

### Prerequisites

* Python 3.8 or higher
* pip installed

### Installation

```bash
git clone https://github.com/yourusername/mcp-file-search-server
cd mcp-file-search-server
pip install -r requirements.txt
```

### Run

```bash
python main.py
```

### Example

```bash
python main.py --query "async def" --path ./src
```

## License

MIT License

