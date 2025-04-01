# Fork Delete

Fork Delete is a command-line tool to cleanup your GitHub account by deleting forks where you do not have lingering open pull requests.

## Installation

Install with [Homebrew](https://brew.sh):

```shell
brew install vitorgalvao/tiny-scripts/fork-delete
```

Alternatively, download the executable at the root of this repository and call it directly. Ensure you have [`gh`](https://cli.github.com) installed and in your `PATH`.

## Usage

```
Delete your GitHub forks where you do not have pending pull requests.
Confirmation is requested before each deletion.

Usage:
  fork-delete

Options:
  -h, --help   Show this help.
```

## License

3-Clause BSD
