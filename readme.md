# Löve2D Saturnus bindings

Make Löve2D games using the [Saturnus programming language](https://github.com/sigmasoldi3r/saturnus).

## Requisites

You need [Saturnus](https://github.com/sigmasoldi3r/saturnus) and
[Janus](https://github.com/sigmasoldi3r/Saturnus?tab=readme-ov-file#introducing-janus).

## Using this library

To use this library simply add this line to your `Janus.toml`
(aka Janusfile):

```toml
love2d = { git = "https://github.com/sigmasoldi3r/love2d-saturnus-bindings" }
```

> [!TIP]
> Remember that this line goes below the `[dependencies]` line.

## Development & contributing

To build the API bindings you must clone `love-api` repository,
which can be found on [github, Löve2D's community love-api](https://github.com/love2d-community/love-api).

```sh
git clone https://github.com/love2d-community/love-api
```

Then, run:

```sh
saturnus nictogen.saturn
```

Then you're set to go. After that, you can remove the `love-api` folder,
if you wish (Optional step).
