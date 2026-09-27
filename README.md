# sortie

Go CLI that organizes a messy folder by file extension

Small but I use it weekly.

## How to use

```bash
./bin/sortie ~/Downloads --dry-run
./bin/sortie ~/Downloads
```

## Features

- Single static binary, no runtime deps
- Skips hidden files and folders by default
- Groups files into folders by extension
- Dry-run prints the plan before moving anything

## Installation

```bash
go build -o bin/ ./...
```

## Project structure

```text
├── .github/
│   └── workflows/
│       └── ci.yml
├── docs/
│   └── roadmap.md
├── examples/
│   └── quickstart.md
├── .gitignore
├── CODE_OF_CONDUCT.md
├── CONTRIBUTING.md
├── LICENSE
├── SECURITY.md
├── go.mod
└── main.go
```

## Development

```bash
go build ./...
go vet ./...
```

## Why

Needed this for myself; figured others might too.

## License

MIT. Do whatever you want.
