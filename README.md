# kickoff-skeletons

![GitHub](https://img.shields.io/github/license/martinohmann/kickoff-skeletons?color=orange)

Skeleton repository for [kickoff](https://github.com/martinohmann/kickoff).

## Getting started

Clone the repository into your local config directory (replace
`~/.config/kickoff/skeletons` with `~/Library/Application\ Support/kickoff` on
OSX):

```
mkdir -p ~/.config/kickoff
git clone https://github.com/martinohmann/kickoff-skeletons ~/.config/kickoff/skeletons
```

Verify that the skeletons are recognized by `kickoff`:

```
kickoff list
```

**Hint**: you can also store it in a different directory if you like. In this
case pass the location via the `--skeletons-dir` flag to the list command above.

## Customization

Fork and customize this repository to your needs! I'd be happy about receiving
pull requests for other useful project skeletons.

## License

The source code of kickoff-skeletons is released under the MIT License. See the bundled
LICENSE file for details.
