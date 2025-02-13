# Sapphire Injector

**Sapphire Injector** is a lightweight DLL injector for injecting DLLs into running processes. It’s designed to be simple, fast, and easy to use.

## Features
- Lightweight and fast.
- Auto-loads `main.dll` from the same folder as the injector.
- Easy-to-use command line interface.

## Prerequisites
- Visual Studio or any C++ compiler.
- A running process to inject the DLL into.

## Setup
1. Clone or download the repository.
2. Open the project in Visual Studio.
3. Build the project (outputs `SapphireInjector.exe`).

## Usage
1. Place your `main.dll` in the same folder as `SapphireInjector.exe`.
2. Open Command Prompt and navigate to the project folder.
3. Run the injector with the target process's PID:

   ```bash
   SapphireInjector.exe <PID>
