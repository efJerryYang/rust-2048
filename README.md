# Rust 2048

A 2048 clone with Piston game engine with AI added!

## How to play

Use arrow key to move tiles.

![alt tag](./rust-2048.png)

## Building Instructions

To build this repository, you need [Cargo](https://github.com/rust-lang/cargo).

You also need the `Freetype 6` and `SDL2` libs.
Look at [Piston-Tutorials - Installing Dependencies](https://github.com/PistonDevelopers/Piston-Tutorials/tree/master/getting-started#installing-dependencies) and [Rust-SDL2 - Requirements](https://github.com/AngryLawyer/rust-sdl2#sdl20--development-libraries) how to install them.

Clone this repository

```sh
git clone https://github.com/Coeuvre/rust-2048.git
```

Use Cargo to build

```sh
cargo build
```

Play!

```sh
cargo run
```

Run with AI

```sh
cargo run -- <executable params>
```
