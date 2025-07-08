# Martin Kennedy's PCC-specific tap

## How do I install these formulae?

`brew install hurricos/postgresql/<formula>`

Or `brew tap hurricos/postgresql` and then `brew install <formula>`.

Or, in a `brew bundle` `Brewfile`:

```ruby
tap "hurricos/postgresql"
brew "<formula>"
```

## Documentation

`brew help`, `man brew` or check [Homebrew's documentation](https://docs.brew.sh).

## Notes for next time

A tap is a set of formulae, not a specific formula. This *should* be
called `homebrew-pcc` instead.
