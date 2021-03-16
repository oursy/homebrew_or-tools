[![MacOS CI](https://github.com/Mizux/homebrew-or-tools/workflows/MacOS%20CI/badge.svg)](https://github.com/Mizux/homebrew-or-tools/actions?query=workflow%3A%22MacOS+CI%22)

# Homebrew formula for OR-Tools

Formula has been written from scratch to make it harder, better, faster, stronger.

## Usage

1. Add this repo as a tap.
```sh
brew tap or-tools/or-tools https://github.com/or-tools/homebrew_or-tools.git
```
2. Install OR-Tools:
```sh
brew install or-tools
```
3. Use OR-Tools as you usually do.

## Development process

1. Clone this repo into `/usr/local/Library/Tap/or-tools/`
2. Edit `or-tools.rb`
3. Reinstall or-tools: `brew uninstall ortools; brew install --verbose --debug --HEAD or-tools`

## Contributing

The [CONTRIBUTING.md](CONTRIBUTING.md) file contains instructions on how to
submit the Contributor License Agreement before sending any pull requests (PRs).
Of course, if you're new to the project, it's usually best to discuss any
proposals and reach consensus before sending your first PR.

## License

The OR-Tools software suite is licensed under the terms of the Apache 2.0 license.
<br>See [LICENSE](LICENSE) for more information.
