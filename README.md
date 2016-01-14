Note: This repository was forked in order to add a operating system agnostic .go file so `go get` does not fail on non-darwin machines.

# FSEvents bindings for Go (OS X)

[![GoDoc](https://godoc.org/github.com/go-fsnotify/fsevents?status.svg)](https://godoc.org/github.com/go-fsnotify/fsevents)

[FSEvents](https://developer.apple.com/library/mac/documentation/Darwin/Reference/FSEvents_Ref/) allows an application to monitor a whole file system or portion of it. FSEvents is only available on OS X.

**Warning:** This API should be considered unstable.

## Contributing

Request features and report bugs using the [GitHub Issue Tracker](https://github.com/go-fsnotify/fsevents/issues).

fsevents carries the same [LICENSE](https://github.com/go-fsnotify/fsevents/blob/master/LICENSE) as Go. Contributors retain their copyright, so you need to fill out a short form before we can accept your contribution: [Google Individual Contributor License Agreement](https://developers.google.com/open-source/cla/individual).
