# Tasks for Canvas Safari Extension

A Safari port of the popular Chrome extension [Tasks for Canvas](https://www.tasksforcanvas.info).

## Overview

This Safari extension provides the same functionality as the Chrome version of [Tasks for Canvas](https://www.tasksforcanvas.info) for Safari users on macOS. This Safari port maintains compatibility with the original extension's functionality while adapting it for the Safari platform.

## Compatibility

Compatibility as a whole is unknown. Here are the known devices that can run this safari extension:

- **macOS**: Safari 26.2 or later
- **iPadOS/iOS**: Unknown

## Installation

### From Source

1. Clone this repository:
   ```bash
   git clone https://github.com/rngkGit/Tasks-for-Canvas-Safari-Extension.git
   cd Tasks-for-Canvas-Safari-Extension
   ```

2. Open the Xcode project:
   ```bash
   open "Tasks for Canvas – now supporting Blackboard, D2L Brightspace.xcodeproj"
   ```

3. Select your target platform (macOS or iPadOS)

4. Build and run the project

5. Enable the extension:
   - **macOS**: Safari → Settings → Extensions → Enable "Tasks for Canvas"

### Building the Extension

1. Ensure you have Xcode installed (version 13.0 or later recommended)
2. Open the project in Xcode
3. Select your target device/simulator
4. Press `Cmd + R` to build and run

### Releases

Tasks For Canvas.app is avaiable in the releases section for macOS.

### Important Note

Ensure Safari Developer settings are enabled.
   - **macOS 26**: Safari → Settings → Advanced → Ensure "Show features for web developers" is checked → Developer → Allow unsigned extensions

## Issues

If you encounter any issues, please file them in the [Issues](https://github.com/rngkGit/Tasks-for-Canvas-Safari-Extension/issues) section of this repository.

## !!! Disclaimer !!!

This extension is not affiliated with or endorsed by Instructure (Canvas LMS), Blackboard, or D2L Brightspace. It is an independent tool created to enhance the user experience of these platforms.

In addition, this extension is not affiliated with [UseBetterCanvas](https://github.com/UseBetterCanvas) and is a community port.

## License

The original Chrome extension [Tasks for Canvas](https://www.tasksforcanvas.info) is licensed under the MIT License. As a port of that extension, this project respects and acknowledges the original work.

This repository is licensed under the MIT License. Please see `LICENSE.md` for more.
