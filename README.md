# Licenser

Verify and append licenses to your GitHub repositories.

## Supported Licenses & Languages

Licenses:

- Apache 2.0

Languages:

- Bazel
- C/C++
- Dockerfile
- Golang
- Make
- Python
- Shell
- YAML

## Install

To install on macOS, use Homebrew.

```sh
brew install liamawhite/licenser/licenser
```

To install on other platforms, download from the [releases section](https://github.com/liamawhite/licenser/releases).

## Verifying Licenses in your Files

To verify that licenses are present in all files in a repository, run the `verify` command, with the `--recurse` flag, passing in the directory to start from.

```sh
licenser verify -r .
```

## Apply Licenses to your Files

To prepend licenses to all files in a repository, run the `apply` command, with the `--recurse` flag, passing in the directory to start from and the copyright owner.

```sh
licenser apply -r . "Copyright Owner"
```
