# Practice with Elixir

## Setup
Following https://elixir-lang.org/getting-started/introduction.html#installation

to install, and get started

### Useful commands
`elixir --version` | For testing the installation worked
`elixir SCRIPT.exs` | Run an elixir script
`elixirc __.ex` | build an elixir file. Not .exs vs .ex is convention, but doesn't do anything
`iex` | interactive shell
`mix` | provides tasks for creating, compiling, testing your application, managing its dependencies and much more
`livebook server --home $(pwd)/notebooks --data-path $(pwd)/notebooks` | starts local livebook at this directory



### Useful elixir functions
`h` | displays the documentation for any function, eg. `h func/arity`

### Useful reference


Set mix config | https://hexdocs.pm/hex/Mix.Tasks.Hex.Config.html

introduction | https://elixir-lang.org/getting-started/introduction.html

Elizir docs | https://hexdocs.pm/elixir/api-reference.html

Naming conventions | https://hexdocs.pm/elixir/main/naming-conventions.html#trailing-question-mark-foo

railway programming | https://cbailey.co.uk/posts/elixirs_with_statement_and_railway_oriented_programming


## ide

### Vscode

#### Extensions
ElixirLS - https://thinkingelixir.com/elixir-in-vs-code/#Elixir_development_extensions


### Livebook
https://github.com/livebook-dev/livebook

```
sudo apt install erlang-inets erlang-os-mon erlang-runtime-tools erlang-ssl erlang-xmerl erlang-dev erlang-parsetools

mix do local.rebar --force, local.hex --force


mix hex.config http_timeout 300

mix escript.install hex livebook

# Start the Livebook server
livebook server

# See all the configuration options
livebook server --help
```

Note you may need to add elixir scripts to your path