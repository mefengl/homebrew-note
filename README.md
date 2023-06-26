# homebrew-note

## untap unnecessary taps

This command untaps all taps, but skips those still in use by other formulas.

```shell
brew tap | xargs -I{} brew untap {}
```
