# Sapphire Injector

**Sapphire Injector** is a lightweight DLL injector that injects `main.dll` into a target process. The injector automatically loads the DLL from the same folder as the executable.

## Features
- Lightweight and fast.
- Auto-loads `main.dll` from the same directory as the injector.
- Simple command line interface to inject into any running process.

## Prerequisites
- Visual Studio or any C++ compiler.
- A running process to inject the DLL into.

## Setup
1. Clone or download the repository.
2. Open the project in Visual Studio.
3. Build the project (this will create `SapphireInjector.exe`).

## Usage
1. Place your `main.dll` in the same folder as `SapphireInjector.exe`.
2. Open Command Prompt and navigate to the folder containing the injector.
3. Run the following command with the target process’s PID:

   ```bash
   SapphireInjector.exe <PID>
