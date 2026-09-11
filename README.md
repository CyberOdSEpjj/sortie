# sortie

Small Go tool: declutter ~/Downloads in one command

## Install

```bash
go build -o bin/ ./...
```

## What it does

- Groups files into folders by extension
- Skips hidden files and folders by default
- Single static binary, no runtime deps
- Dry-run prints the plan before moving anything

## Examples

```bash
./bin/sortie ~/Downloads --dry-run
./bin/sortie ~/Downloads
```

## Project structure

```text
├── docs/
│   ├── configuration.md
│   └── roadmap.md
├── examples/
│   └── quickstart.md
├── .gitignore
├── CHANGELOG.md
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

## 说明

个人练习项目, 谨慎用于生产环境。

## License

MIT licensed, see LICENSE.
