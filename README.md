<div align="center">
 <a href="https://github.com/Daswaget/EkosyzEng.Core">
   <img height="128" alt="EkosyzEng" src="https://raw.githubusercontent.com/Daswaget/EkosyzEng.Core/refs/heads/master/Images/Icon128.png">
 </a>
 <h1>EkosyzEng</h1>

 [![Nuget](https://img.shields.io/nuget/v/EkosyzEng.Core?style=for-the-badge)](https://www.nuget.org/packages/EkosyzEng.Core)
 [![Status](https://img.shields.io/badge/status-beta-orange?style=for-the-badge)](#development-status-beta)
 [![License](https://img.shields.io/badge/license-MIT-blue?style=for-the-badge)](https://opensource.org/license/MIT)
 [![C#](https://img.shields.io/badge/c%23-%23239120.svg?style=for-the-badge&logo=c-sharp&logoColor=white)](https://wikipedia.org/wiki/C_Sharp_(programming_language))

[Getting started](#getting-started) •
[Ecosystem](#ecosystem) •
[Supported Platforms](#supported-platforms) •
[License](#license)
</div>

## Overview

**EkosyzEng** is a modular, cross-platform multimedia engine for developing games and graphical applications using the **C#** programming language.

The engine is designed to provide a simple entry point while remaining scalable and maintaining a controlled level of architectural complexity as projects grow. It is built on top of **MonoGame** and uses **Arch-PureECS** as its architectural foundation.

## Getting started

Code is distributed as NuGet packages in the form of libraries (.dll files). You can easily install the NuGet packages into your existing MonoGame project using the NuGet Package Manager UI in Visual Studio or by using the command line interface (CLI) in a terminal.

```sh
dotnet add package EkosyzEng.Core --version 0.1.0
```

[View package on NuGet.org](https://www.nuget.org/packages/EkosyzEng.Core)

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
