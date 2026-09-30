# Homebrew tap

```bash
brew install --cask shayredmond/tap/meetloaf --no-quarantine
```

`--no-quarantine` is required: MeetLoaf is ad-hoc signed rather than
notarized, so macOS would otherwise refuse to open it.

`Casks/meetloaf.rb` is generated — the release workflow in
[shayredmond/meetloaf](https://github.com/shayredmond/meetloaf) writes it
from `packaging/homebrew/meetloaf.rb`. Edit it there, not here.
