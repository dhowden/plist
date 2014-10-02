#plist Parser

This is a fork of the `plist` package from rsc's Google Code Repo: [https://code.google.com/p/rsc/source/browse/#hg%2Fplist](https://code.google.com/p/rsc/source/browse/#hg%2Fplist)

A Go package for parsing Apple `.plist` XML files.

## Changes

- Support for `<date>` tag.
- Support for unmarshalling `<dict>` tags into a `map[String]Value`.
