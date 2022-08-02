# Minidev

You can install the `.mpackage` file using the Package Manager. You will need to update a few things for use in your city:

1. The `Plot List - City` trigger looks for `ashtan2` to strt the lines. You should replace this with whatever your city's subdivision id is.
2. The same trigger will need instances of `"Ashtan"` replaced with whatever city you are.

```
ashtan2 (30, 46)                         SomeoneCool               0
```

^ That `ashtan2` is what you're looking for in your `develop plotlist` output.

## Extra

The package checks if you have svof's `ndb` available. If you don't, nothing happens. If you do, it triggers a check for every plot owner and will, once it has data for them, report if the person is a city enemy.
