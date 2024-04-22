# Surf 5 Project README

## Overview
Surf 5 is a versatile development board that supports a variety of DMA (Direct Memory Access) operations, simplifying data transfer tasks in embedded projects. This document outlines the setup and usage of the Surf 5 libraries within the VS Code environment.

## Getting Started
To use the Surf 5 libraries with your projects, follow these steps:

1. **Download the Libraries**: First, download the Surf 5 libraries from the GitHub repository at [Wiznet/W7500x-Surf5](https://github.com/Wiznet/W7500x-Surf5).

2. **Add Project Directory**: Next, add this project directory to `...\7500x-Surf5_Test\Projects\W7500x_StdPeriph_Examples`.

3. **Modify CMakeLists**: Open the file `...\7500x-Surf5_Test\Projects\W7500x_StdPeriph_Examples\CMakeLists.txt` and add the following line:


add_subdirectory(Surf5_DMA_library)

This will include the Surf 5 DMA library in your build configuration.

4. **Build in VS Code**: You can now build your project in VS Code. The setup should seamlessly integrate with the provided library and examples.

## VS Code Setup
If you encounter any difficulties while setting up or building your project in VS Code, refer to the following resources:

- [VS Code Installation Guide for Surf 5](https://docs.wiznet.io/Product/Open-Source-Hardware/surf5/getting-started/install-vscode-guide)
- [VS Code Environment Setup Guide for Surf 5](https://docs.wiznet.io/Product/Open-Source-Hardware/surf5/getting-started/fw-examples)

These guides will provide detailed instructions on configuring your development environment specifically for Surf 5.

## Features
This repository contains sample code demonstrating the use of the DMA functionality to perform memory-to-memory data transfers. These examples are designed to help developers understand how to utilize the DMA capabilities effectively in their applications.

## Disclaimer
Please note that the firmware provided is for guidance only and is intended to assist customers by providing coding information related to their products. Wiznet is not liable for any direct, indirect, or consequential damages arising from the use of the firmware and the coding information contained therein.

---
For further information or support, please refer to the documentation and resources provided on the [official Wiznet documentation site](https://docs.wiznet.io/).