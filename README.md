# EkosyzEng

![Status](https://img.shields.io/badge/status-beta-orange)
[![License](https://img.shields.io/badge/license-MIT-blue)](https://opensource.org/license/MIT)

**EkosyzEng** is a modular, cross-platform multimedia engine for developing games and graphical applications using the **C#** programming language.

The engine is designed to provide a simple entry point while remaining scalable and maintaining a controlled level of architectural complexity as projects grow. It is built on top of **MonoGame** and uses **Arch-PureECS** as its architectural foundation.

## Ecosystem

- **EkosyzEng.Core** — the central and minimal part of the engine, on which all other functionality is built.
- **Modules** (optional, can be added as needed):
  - **EkosyzEng.Render** — rendering functionality
  - **EkosyzEng.Audio** — audio processing
  - **EkosyzEng.Input** — user input handling (keyboard, mouse, gamepad)
  - *...and others*

## Development Status (Beta)

The project is currently in **beta testing**. This means:
- Core functionality is implemented and usable.
- Bugs may still be present despite testing before releases. If you encounter any issues, please report them.
- The API and module architecture may change in future versions without strict backward compatibility guarantees.

## Supported Platforms

- **Desktop PCs**
  - Windows 8.1 and up
  - Linux
  - macOS 10.15 and up
- **Mobile/Tablet Devices**
  - Android 6.0 and up
  - iPhone/iPad 10.0 and up
- **Consoles** (for registered developers)
  - PlayStation 4
  - PlayStation 5
  - Xbox One
  - Nintendo Switch
  
## License
  
This project is licensed under the MIT License. See the LICENSE.txt file for details. Third-party libraries are distributed under their own licenses. Please refer to those libraries for details on the license they use.
