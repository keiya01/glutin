# glutin -  OpenGL, UTilities and INput

A low-level library for OpenGL context creation.

[![](https://img.shields.io/crates/v/glutin.svg)](https://crates.io/crates/glutin)
[![Docs.rs](https://docs.rs/glutin/badge.svg)](https://docs.rs/glutin)

```toml
[dependencies]
glutin = "0.30.0-beta.2"
```

## [Documentation](https://docs.rs/glutin)

## Contact Us

Join us in any of these:

[![Matrix](https://img.shields.io/badge/Matrix-%23rust--windowing%3Amatrix.org-blueviolet.svg)](https://matrix.to/#/#rust-windowing:matrix.org)
[![Libera.Chat](https://img.shields.io/badge/libera.chat-%23winit-red.svg)](https://web.libera.chat/#winit)

## Usage Examples

**Warning:** these are examples for master. For the latest released version you can
find them [here](https://github.com/rust-windowing/glutin/releases/tag/v0.30.0-beta.2).

The examples use [gl_generator](https://crates.io/crates/gl_generator) to
generate OpenGL bindings.

### Try it!

```bash
git clone https://github.com/rust-windowing/glutin
cd glutin
cargo run --example window
```

### Usage

Glutin is an OpenGL context creation library and doesn't directly provide
OpenGL bindings for you.

For examples, please look [here.](https://github.com/rust-windowing/glutin/tree/master/glutin_examples)

Note that glutin aims at being a low-level brick in your rendering
infrastructure. You are encouraged to write another layer of abstraction
between glutin and your application.

The minimum rust version target by glutin is `1.60.0`.

## Platform-specific notes

### Android

To compile the examples for android, you have to use the `cargo apk` utility.

See [`cargo-apk` in the `android-ndk-rs` repository](https://github.com/rust-windowing/android-ndk-rs/tree/master/cargo-apk) for instructions.
