# MCP Primer Server

A TypeScript-based server project.

## Prerequisites

- Node.js (v18 or higher)
- npm (comes with Node.js)
- Cursor IDE (recommended)

## Installation

1. Clone the repository:
```bash
git clone git@github.com:jefersonprimer/mcp-primer-server.git
cd mcp-primer-server
```

2. Install dependencies:
```bash
npm install
```

## Running the Project

1. Development mode:
```bash
npm run dev
```

2. Build and run in production mode:
```bash
npm run build
npm start
```

## Adding MCP to Cursor

```json
{
  "mcpServers": {    
    "primer-mcp-server": {
      "command": "node",      
      "args": ["path/to/mcp-primer-server/build/index.js"]
    }
  }
}
```

## Project Structure

```
mcp-primer-server/
├── src/           # Source code
├── build/         # Compiled JavaScript files
├── node_modules/  # Dependencies
├── package.json   # Project configuration and dependencies
└── tsconfig.json  # TypeScript configuration
```

## License

This project is licensed under the MIT License - see the LICENSE file for details. 
