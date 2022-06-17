# Practice with Elixir

## Setup
Following https://elixir-lang.org/getting-started/introduction.html#installation

to install, and get started

### Useful commands
`elixir --version` | For testing the installation worked

`elixir SCRIPT.exs` | Run an elixir script

`elixirc __.ex` | build an elixir file. Note .exs vs .ex is convention, but doesn't do anything

`iex` | interactive shell

`mix` | provides tasks for creating, compiling, testing your application, managing its dependencies and much more

`mix format` | format elixir code in a standardized way

`mix new path/to/new/project` | start a new project

`livebook server --home $(pwd)/notebooks --data-path $(pwd)/notebooks` | starts local livebook at this directory



### Useful elixir functions
`h` | displays the documentation for any function, eg. `h func/arity`

### Useful reference

Read you some erlang for great good | https://learnyousomeerlang.com/


Set mix config | https://hexdocs.pm/hex/Mix.Tasks.Hex.Config.html

introduction | https://elixir-lang.org/getting-started/introduction.html

Elizir docs | https://hexdocs.pm/elixir/api-reference.html

Naming conventions | https://hexdocs.pm/elixir/main/naming-conventions.html#trailing-question-mark-foo

railway programming | https://cbailey.co.uk/posts/elixirs_with_statement_and_railway_oriented_programming

Elixir questions | https://elixirforum.com/

OTP (Open Telecom Platform) | https://www.educative.io/edpresso/what-is-otp-in-elixir

Library guidelines | https://hexdocs.pm/elixir/library-guidelines.html

Meta-programming and DSLs (Domain Specific Languages) | https://elixir-lang.org/getting-started/meta/quote-and-unquote.html

## ide

### Vscode

#### Extensions
ElixirLS | https://thinkingelixir.com/elixir-in-vs-code/#Elixir_development_extensions

Livebook for VSCode | https://marketplace.visualstudio.com/items?itemName=josecfreittas.livebook

vscode-elixir | https://github.com/timmhirsens/vscode-elixir


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