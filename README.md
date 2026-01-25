# TanStack Skills

Claude Code skills for the complete TanStack ecosystem. Comprehensive API documentation, code examples, TypeScript patterns, best practices, and common pitfalls for AI-assisted development.

## Quick Install (Plugin Marketplace)

```bash
# Add the marketplace
/plugin marketplace add tanstack-skills/tanstack-skills

# Install all TanStack skills
/plugin install tanstack-all@tanstack-skills

# Or install individual plugins
/plugin install tanstack-query@tanstack-skills
/plugin install tanstack-router@tanstack-skills
/plugin install tanstack-start@tanstack-skills
```

## Available Plugins

### Bundle Plugins

| Plugin | Description |
|--------|-------------|
| `tanstack-all` | All 13 TanStack skills - complete ecosystem coverage |
| `tanstack-core` | Start + Router + Query - the essential full-stack trio |
| `tanstack-ui` | Table + Form + Virtual - headless UI components |
| `tanstack-data` | Query + Store + DB - state management and data layer |

### Individual Plugins

| Plugin | Status | Description |
|--------|--------|-------------|
| `tanstack-start` | RC | Full-stack React framework with SSR, streaming, server functions |
| `tanstack-router` | Stable | Type-safe file-based routing with search params and data loading |
| `tanstack-query` | Stable | Async state management with caching, mutations, and SSR |
| `tanstack-table` | Stable | Headless tables with sorting, filtering, pagination, virtualization |
| `tanstack-form` | Stable | Headless forms with sync/async/schema validation |
| `tanstack-db` | Beta | Client-first reactive database with live queries |
| `tanstack-ai` | Alpha | Provider-agnostic AI SDK with streaming and tool calling |
| `tanstack-virtual` | Stable | Virtualization for lists and grids with dynamic sizing |
| `tanstack-pacer` | Beta | Debouncing, throttling, rate limiting, queuing |
| `tanstack-store` | Alpha | Framework-agnostic reactive data store |
| `tanstack-devtools` | Alpha | Centralized devtools panel with plugin architecture |
| `tanstack-config` | Stable | Build, lint, and publish configuration toolkit |
| `tanstack-cli` | Stable | Project scaffolding with 30+ integrations and MCP server |

## Installation Methods

### Method 1: Plugin Marketplace (Recommended)

```bash
# Step 1: Add this repository as a marketplace
/plugin marketplace add tanstack-skills/tanstack-skills

# Step 2: Install plugins you need
/plugin install tanstack-all@tanstack-skills      # Everything
/plugin install tanstack-core@tanstack-skills     # Start + Router + Query
/plugin install tanstack-query@tanstack-skills    # Just Query
```

### Method 2: Direct Git URL

```bash
/plugin marketplace add https://github.com/tanstack-skills/tanstack-skills.git
/plugin install tanstack-all@tanstack-skills
```

### Method 3: Local Clone

```bash
git clone https://github.com/tanstack-skills/tanstack-skills.git
/plugin marketplace add ./tanstack-skills
/plugin install tanstack-all@tanstack-skills
```

## Managing Plugins

```bash
# List installed plugins
/plugin list

# Update marketplace
/plugin marketplace update

# Disable a plugin
claude plugin disable tanstack-query@tanstack-skills

# Uninstall a plugin
claude plugin uninstall tanstack-query@tanstack-skills
```

## What's Included

Each skill provides:

- **Overview** - Package names, installation, and core concepts
- **API Reference** - Hooks, functions, classes, and their signatures
- **Code Examples** - Real-world usage patterns with TypeScript
- **TypeScript Patterns** - Type inference, generics, and type safety tips
- **Best Practices** - Recommended patterns and architectural guidance
- **Common Pitfalls** - Mistakes to avoid and how to fix them
- **Integration Patterns** - How libraries work together

## TanStack Ecosystem

```
┌─────────────────────────────────────────────────────────────┐
│                      TanStack Start                         │
│              (Full-stack React Framework)                   │
├─────────────────────────────────────────────────────────────┤
│  Router  │  Query  │  Form  │  Table  │  Virtual  │  AI    │
├──────────┴─────────┴────────┴─────────┴───────────┴────────┤
│     DB     │    Store    │    Pacer    │    Devtools       │
├─────────────────────────────────────────────────────────────┤
│                Config  │  CLI (scaffolding + MCP)           │
└─────────────────────────────────────────────────────────────┘
```

## Repository Structure

```
tanstack-skills/
├── .claude-plugin/
│   └── marketplace.json      # Marketplace manifest
├── plugins/
│   ├── tanstack-all/         # Bundle: all skills
│   ├── tanstack-core/        # Bundle: start + router + query
│   ├── tanstack-ui/          # Bundle: table + form + virtual
│   ├── tanstack-data/        # Bundle: query + store + db
│   ├── tanstack-start/       # Individual plugin
│   ├── tanstack-router/
│   ├── tanstack-query/
│   ├── tanstack-table/
│   ├── tanstack-form/
│   ├── tanstack-virtual/
│   ├── tanstack-store/
│   ├── tanstack-db/
│   ├── tanstack-ai/
│   ├── tanstack-pacer/
│   ├── tanstack-devtools/
│   ├── tanstack-config/
│   └── tanstack-cli/
└── README.md
```

## License

MIT
