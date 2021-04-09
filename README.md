# Identicon

 <p align="center">
 <img src='/README/example.png'>
 </p>

## Whats an Identicon?

An Identicon is the pixelated icon Github assigns to your account if no image is provided. This Elixir app generates one for you.

## How is an Identicon made?

Identicons are not randomly generated. It is generated based on a string (username) so each identicon is unique.

## Installation

```sh
$ git clone https://github.com/hector4213/identicon.git
$ cd identicon
$ iex -S mix
```

## Create an identicon

###### Start Elixir's Interactive Shell

```sh
$ iex -S mix
```

###### Then type:

```sh

iex(1)> Identicon.main("myghusername")

```

**An Identicon will be generated in the root folder.**

If [available in Hex](https://hex.pm/docs/publish), the package can be installed
by adding `identicon` to your list of dependencies in `mix.exs`:

```elixir
def deps do
  [
    {:identicon, "~> 0.1.0"}
  ]
end
```

Documentation can be generated with [ExDoc](https://github.com/elixir-lang/ex_doc)
and published on [HexDocs](https://hexdocs.pm). Once published, the docs can
be found at [https://hexdocs.pm/identicon](https://hexdocs.pm/identicon).
