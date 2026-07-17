# homebrew-tap

Homebrew formulae for [@sergiught](https://github.com/sergiught)'s tools.

## Usage

Add the tap once:

```sh
brew tap sergiught/tap
```

Then install any formula below. You can also install directly without tapping first:

```sh
brew install sergiught/tap/<formula>
```

## Formulae

| Formula | Description |
| --- | --- |
| [`ofga`](https://github.com/sergiught/openfga-cli) | A modern CLI & TUI for [OpenFGA](https://openfga.dev). |

### ofga

```sh
brew install sergiught/tap/ofga
```

Verify the install:

```sh
ofga version
```

## Updating

```sh
brew update
brew upgrade ofga
```

## Notes

Formulae in this tap are generated automatically by [GoReleaser](https://goreleaser.com) on each release, so the `.rb` files are not edited by hand.
