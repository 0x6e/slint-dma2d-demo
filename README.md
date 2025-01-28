# Slint DMA2D Demo for STM32H747I-DISCO boards

This repository serves as a playground for getting an async rendering API for [Slint](https://slint.dev) working with DMA2D
on the [STM32H747I-DISCO Discovery kit](https://www.st.com/en/evaluation-tools/stm32h747i-disco.html).

## About

This demo is very much a work in progress. The goal is to produce an API similar to that requested in
[issue #5774](https://github.com/slint-ui/slint/issues/5774).

## Prerequisites

In order to use this template and build a C++ application, you need to install a few tools:

  * **[cmake](https://cmake.org/download/)** (3.21 or newer)
  * **[STM32CubeCLT](https://www.st.com/en/development-tools/stm32cubeclt.html)**
  * **[Visual Studio Code](https://code.visualstudio.com)**
  * **[Slint extension](https://marketplace.visualstudio.com/items?itemName=Slint.slint)**
  * **[STM32 VS Code Extension](https://marketplace.visualstudio.com/items?itemName=stmicroelectronics.stm32-vscode-extension)**
  * **[CMake Tools](https://marketplace.visualstudio.com/items?itemName=ms-vscode.cmake-tools)**

## Usage

1. Open this folder with VS code.
2. Configure the project either via "CMake: Select Configure Preset" from the command palette or the CMake extension panel.
3. Build, Flash to Device, and debug by hitting `F5` or running the `CMake: Debug` command from the command palette.
