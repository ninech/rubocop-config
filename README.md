# nine rubocop config

This is our common rubocop configuration. Change your own `~/.rubocop.yml` to look like this:

```
inherit_from:
  - https://raw.githubusercontent.com/ninech/rubocop-config/master/rubocop.yml
```

You can then still overwrite settings to fit your needs. But rather create a pull request in this repo if you want to change anything.

## Updates

To update these settings to a new version of Rubocop you can use this gem: https://github.com/pocke/mry.
