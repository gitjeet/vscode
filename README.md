# VS Code with Cline Integration

This repository contains a custom build of Visual Studio Code with [Cline](https://github.com/cline/cline) integrated by default.

---

## Features

- Cline is pre-installed and fully integrated.
- Cline does **not** appear in the Extensions panel or Marketplace.
- All standard VS Code features and Cline features work seamlessly.
- The build is based on official VS Code sources with modular patching for easy future updates.

---

## Releases

You can find the Windows and macOS builds in the `release` folder as ZIP archives.

---

## Windows

### Installation and Running

1. Download the ZIP archive for Windows (`vscode-win32-x64.zip`).
2. Extract the contents anywhere you prefer.
3. Inside the extracted folder, open the `bin` directory.
4. Run `Code.exe` to launch the customized VS Code with Cline integrated.

---

## macOS

### Installation and Running

1. Download the ZIP archive for macOS (`vscode-darwin-x64.zip`).
2. Extract the ZIP archive.
3. You will get a `.app` bundle folder named like `Visual Studio Code.app` or `Code - OSS.app`.
4. To launch the app, you can either:
   - Double-click the `.app` in Finder to open normally.
   - Or open Terminal and run the executable inside the bundle:

    ```bash
    cd /path/to/Visual\ Studio\ Code.app/Contents/MacOS
    ./Electron
    ```
