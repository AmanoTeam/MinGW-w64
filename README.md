# MinGW-w64

The official download page at <https://www.mingw-w64.org/downloads> lists several sources for prebuilt MinGW-w64 binaries for Linux. However, most of them are either outdated or tied to specific Linux distributions, making them non-portable.

After spending too much time searching for a toolchain that met my needs, I decided to build it myself. While I was at it, I also produced builds for **macOS**, **BSD**, **Haiku**, and **Android**.

## Releases

The current release is based on **GCC 15** and supports cross-compiling for the `x86` and `x86_64` targets. The toolchain includes support for the **C** and **C++** frontends.

You can download the prebuilt toolchains from the [releases](https://github.com/AmanoTeam/MinGW-w64/releases) page.
