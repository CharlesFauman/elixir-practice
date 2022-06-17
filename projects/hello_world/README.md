# HelloWorld

## Setup
Following https://elixir-lang.org/getting-started/mix-otp/introduction-to-mix.html

This just follows part 1, and replaces `kv` with `hello_world`

See the `kv` project for the continuation


## Info
`.ex` should be compiled, `.exs` should be run uncompiled

`mix` source code:
https://github.com/elixir-lang/elixir/tree/main/lib/mix


## Useful functions
`mix new hello_world --module HelloWorld` | Creates the folder structure

`mix help compile.app` | to learn about elixir applications

`mix compile` | go to the project directory, and compile the project

`MIX_ENV=prod mix compile` | compile the project in prod mode

`iex -S mix` | run iex with the `mix.exs` script defined in this project

`mix test`  | runs the ExUnit tests

`mix format` | runs formatting

`mix help` | get all mix help pages

## iex functions
`recompile()` | recompile any changed files

## Installation

If [available in Hex](https://hex.pm/docs/publish), the package can be installed
by adding `hello_world` to your list of dependencies in `mix.exs`:

```elixir
def deps do
  [
    {:hello_world, "~> 0.1.0"}
  ]
end
```

Documentation can be generated with [ExDoc](https://github.com/elixir-lang/ex_doc)
and published on [HexDocs](https://hexdocs.pm). Once published, the docs can
be found at <https://hexdocs.pm/HelloWorld>.


## Project layout
`mix.exs`     - configures the project
`lib/`        - contains the source code
`test/`       - contains the test code
`_build_/`    - contains the compiled code
`.gitignore`  - indicate which files shouldn't be pushed to git
`.formatter.exs` - configures formatting for the project
