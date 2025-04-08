# simplelogin
Since i can't find a good implementation of the simplelogin api, had to DIY

# SimpleLogin API Client

A Python client for interacting with the SimpleLogin API.

## Features

*   List aliases
*   List mailboxes
*   Create custom aliases
*   Create random aliases

## Installation

Requires the `requests` library:

```bash
pip install requests
```

## Usage

### Initialization

First, import the client and initialize it with your SimpleLogin API key.

````python
from simplelogin import SimpleLoginClient, AliasMode

api_key = "YOUR_API_KEY"  # Replace with your actual API key
client = SimpleLoginClient(api_key)
