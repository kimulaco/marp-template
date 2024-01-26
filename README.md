# marp template

## Setup

```bash
corepack enable
pnpm i
```

If you are using VSCode, recommend installing [Marp for VS Code](https://marketplace.visualstudio.com/items?itemName=marp-team.marp-vscode). You can preview your presentation on VSCode.

## Development

```bash
# Preview mode
pnpm run dev

# Check code format
pnpm run format

# Fix code format
pnpm run format:fix
```

## Build

```bash
# Build to all format
pnpm run build

# Build to HTML
pnpm run build:html

# Build to PDF
pnpm run build:pdf

# Build to PowerPoint
pnpm run build:pptx
```
