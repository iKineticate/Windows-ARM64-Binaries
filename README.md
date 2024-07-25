## Official yet to be built executable for windows arm64

## 1. [ruffle-nightly-2024-07-25](https://github.com/iKineticate/Windows-ARM64-Binaries/releases/download/ruffle/ruffle.7z)

A Flash Player emulator written in Rust.

Repository URL: https://github.com/ruffle-rs/ruffle

## 2. [diskonaut-0.11.0](https://github.com/iKineticate/Windows-ARM64-Binaries/releases/download/diskonaut/diskonaut.7z)

Terminal disk space navigator 🔭.

Repository URL: https://github.com/imsnif/diskonaut

## 3. [helix-24.07](https://github.com/iKineticate/Windows-ARM64-Binaries/releases/download/helix/hx.7z)
A post-modern modal text editor.

Repository URL: https://github.com/helix-editor/helix

```yml
# The build targets for the release CI are here
# helix/.github/workflows/release.yml

# Line 61: modify
build: [x86_64-linux, x86_64-macos, x86_64-windows, aarch64-windows] #, x86_64-win-gnu, win32-msvc

# Line 87: add
- build: aarch64-windows
    os: windows-latest
    rust: stable
    target: aarch64-pc-windows-msvc
    cross: false
```

## 4. [lapce-0.4.0](https://github.com/iKineticate/Windows-ARM64-Binaries/releases/download/lapce/lapce.7z)

Lightning-fast and Powerful Code Editor written in Rust

Repository URL: https://github.com/lapce/lapce

```toml
# Building the executable may require modifications to the
# lapce/lapce-core/Cargo.toml

# Line 7: modify
rust-version = "1.77.0"
```

## 5. [Typst-0.11.1](https://github.com/iKineticate/Windows-ARM64-Binaries/releases/download/Typst/typst.7z)

Typst is a new markup-based typesetting system that is designed to be as powerful as LaTeX while being much easier to learn and use.

Repository URL: https://github.com/typst/typst

## 6. [precord-0.7.12](https://github.com/iKineticate/Windows-ARM64-Binaries/releases/download/precord/precord.7z)

Command line tool for recording process or system performance data.

Repository URL: https://github.com/xiaopengli89/precord

## 7. [monolith](https://github.com/iKineticate/Windows-ARM64-Binaries/releases/download/monolith/monolith.7z)

CLI tool for saving complete web pages as a single HTML file

Repository URL: https://github.com/Y2Z/monolith