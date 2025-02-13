# Sapphire Injector

**Sapphire Injector** is a lightweight DLL injector that automatically loads `main.dll` from the same folder and injects it into a target process.

## Features
- Lightweight and fast.
- Auto-loads `main.dll` from the same directory as the injector.
- Simple command line interface to inject into any running process.

## Usage
1. Place your `main.dll` in the same folder as `SapphireInjector.exe`.
2. Open Command Prompt and navigate to the folder containing `SapphireInjector.exe`.
3. Run the following command with the target process’s PID:

   ```bash
   SapphireInjector.exe <PID>
