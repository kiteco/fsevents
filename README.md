Note: This repository was forked in order to add a operating system agnostic .go file so `go get` does not fail on non-darwin machines.

# FSEvents bindings for Go (macOS)

[![GoDoc](https://godoc.org/github.com/fsnotify/fsevents?status.svg)](https://godoc.org/github.com/fsnotify/fsevents) [![Build Status](https://travis-ci.org/fsnotify/fsevents.svg?branch=master)](https://travis-ci.org/fsnotify/fsevents) [![codecov](https://codecov.io/gh/fsnotify/fsevents/branch/master/graph/badge.svg)](https://codecov.io/gh/fsnotify/fsevents) [![Reviewed by Hound](https://img.shields.io/badge/Reviewed_by-Hound-8E64B0.svg)](https://houndci.com)

[FSEvents](https://developer.apple.com/library/mac/documentation/Darwin/Reference/FSEvents_Ref/) allows an application to monitor a whole file system or portion of it. FSEvents is only available on macOS.

**Warning:** This API should be considered unstable.

## Contributing

Request features and report bugs using the [GitHub Issue Tracker](https://github.com/fsnotify/fsevents/issues).

fsevents carries the same [LICENSE](https://github.com/fsnotify/fsevents/blob/master/LICENSE) as Go. Contributors retain their copyright, so you need to fill out a short form before we can accept your contribution: [Google Individual Contributor License Agreement](https://developers.google.com/open-source/cla/individual).
