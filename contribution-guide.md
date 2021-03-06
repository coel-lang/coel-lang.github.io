# Contribution Guide

## Prerequisites

Install Go 1.8+ and rake, and then dependnecies.

```shell
rake deps
```

## Building from source

In the repository's directory,

```
rake build
```

## Testing

- `rake unit_test` runs unit tests. It runs `go test` internally.
- `rake command_test` runs command tests written in
  [Gherkin](https://docs.cucumber.io/gherkin/reference/).
- `rake test` runs both.

## Other utilities

- `rake format` formats all files in Go and Ruby.
- `rake lint` lints all files in Go, Ruby and Markdown.
- `rake clean` cleans up all binaries and temporary files.

For more information, see `rakefile.rb`.
