# Homebrew Tap for Hermano

This repository contains the Homebrew formula for installing [Hermano](https://github.com/hermano-tools/hermano-cli), a CLI tool for creating ebooks from web content using AI.

## Installation

```bash
# Add the tap
brew tap hermano-tools/hermano

# Install hermano
brew install hermano
```

## Usage

After installation, you can use the `hermano` command:

```bash
# Show help
hermano --help

# Create an ebook from a URL
hermano create --url https://example.com --output my-ebook.epub
```

## License

MIT 