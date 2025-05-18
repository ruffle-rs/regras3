# regras3 - REGex in Rust for ActionScript 3

oh no why?! This is a fork of the [regress](https://github.com/ridiculousfish/regress) crate, but instead of just supporting the EcmaScript RegExp syntax,
it supports the following additional Flash ActionScript 3 (AS3) features:

- PCRE style comments `(?#comment)`
- The PCRE extended flag `//x`
- Named capture groups using `(?P<name>...)`

You should probably never use this unless you are implementing a Flash Player emulator like [Ruffle](https://github.com/ruffle-rs/ruffle/).
