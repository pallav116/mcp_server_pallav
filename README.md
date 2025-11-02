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

This project is licensed under the MIT License — feel free to use and improve it!

## Example Usage
json
{
  "file_path": "example.txt",
  "keyword": "function",
  "max_results": 10,
  "context_lines": 2
}

text


## Test File (test_files/example.txt)
```txt
# Sample Code File
def calculate_total(items):
    """Calculate total price of items"""
    total = 0
    for item in items:
        total += item.price
    return total

def validate_user(user):
    """Validate user data"""
    if not user.email:
        return False
    if len(user.password) < 8:
        return False
    return True

class UserManager:
    def __init__(self):
        self.users = []
    
    def add_user(self, user):
        """Add a new user"""
        if validate_user(user):
            self.users.append(user)
            return True
        return False

# Utility functions
def format_date(date_string):
    """Format date string"""
    # Date formatting logic here
    pass
