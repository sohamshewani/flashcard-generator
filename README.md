# Flashcard Generator

A CLI tool to generate customizable flashcard decks from text files for efficient spaced repetition learning.

## Requirements
- Python 3.8+
- click
- toml
- tomlkit

## Usage
```bash
$ flashcard-generator --help
```

## Installation
```bash
$ pip install .
```

## Example
```text
# sample.txt
word: definition
word2: definition2
```

```bash
$ flashcard-generator sample.txt
```

## Contributing
See the [CONTRIBUTING](CONTRIBUTING.md) document.

## License
MIT License
