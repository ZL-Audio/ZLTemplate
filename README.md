<!-- <p float="left">
  <img src="docs/compact_darkblue_flat.svg" width="33%" />
  <img src="docs/logo.svg" width="7.5%" />
</p> -->

# ZLTemplate
![pluginval](<https://github.com/ZL-Audio/ZLSplit/actions/workflows/cmake_full_test.yml/badge.svg?branch=main>)

ZLTemplate is a template for building JUCE plugins (derived from [pamplejuce](https://github.com/sudara/pamplejuce)).

<!-- <img src="Docs/screenshot.png" width=94%> -->
<!-- 
## Usage

See the wiki for details.

## Download

See the releases for the latest version. 

**Please NOTICE**:
- the installer has **NOT** been notarized/EV certificated on macOS/Windows
- the plugin has **NOT** been fully tested on DAWs
-->
## Build from Source

0. `git clone` this repo

1. [Download CMAKE](https://cmake.org/download/) if you do not have it.

2. Populate the latest JUCE by running `git submodule update --init` in your repository directory.

3. Follow the [JUCE CMake API](https://github.com/juce-framework/JUCE/blob/master/docs/CMake%20API.md) to build the source.

## License

ZLTemplate is licensed under GPLv3, as found in the [LICENSE.md](LICENSE.md) file.
