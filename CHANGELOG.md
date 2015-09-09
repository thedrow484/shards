# CHANGELOG

## UNRELEASED

## v0.3.1

Fixes:

- don't install dependencies from optional groups recursively
- manager didn't install path dependencies anymore

## v0.3.0

Features:

- optional groups of dependencies, see #8
- generates default `shard.yml` from Git tags and `Projectfile` dependencies, see #6

Fixes:

- clone repository again when Git remote origin changes, see #4

## v0.2.0

Fixes:

- correctly accesses git versioned `shard.yml` files;
- correctly links/extracts the `src` folder as the `libs/<name>` folder for both
  Git and path resolvers.

## v0.1.0

Initial release.