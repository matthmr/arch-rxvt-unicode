# NOTE

This is the mh fork of arch's `rxvt-unicode` package. My changes are mostly for
my use-case only.


The master branch is not where most of the action occurs, instead, look for
merges against versions in the `pkg` branch

# Changes

## [mh-fixes.patch](./mh-fixes.patch)

1. fixed a bug with mouse events that made it so that the `release` event
   wouldn't register
