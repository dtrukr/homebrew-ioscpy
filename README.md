# ioscpy Homebrew tap

This tap installs the macOS host from the public [dtrukr/ioscpy](https://github.com/dtrukr/ioscpy) fork. The matching protocol 5 device package must be built from that fork and installed on the jailbroken iPhone.

```bash
brew tap dtrukr/ioscpy
brew install dtrukr/ioscpy/ioscpy
ioscpy --version
```

The formula is also maintained at `packaging/homebrew/ioscpy.rb` in the ioscpy fork. It is pinned to a tested commit and archive checksum. Update both copies together.
