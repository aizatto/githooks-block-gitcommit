I want an easy way to force block gitcommits by entering "macros" into my code.

This is useful when I want to play around code which I shouldn't commit. ie:

- secrets
- passwords
- credentials
- api keys

To install

```sh
git config core.hooksPath $(git rev-parse --show-toplevel)/.githooks
```