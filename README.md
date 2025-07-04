# HoSam

A cross-platform **(if you need)** .NET host application for keyboard event handling and automation, leveraging SharpHook and Serilog for logging and event management.

## Features

- Global keyboard event capture
- Reactive event handling
- Configurable logging (console and file)
- Extensible architecture for automation tasks

## Requirements

- .NET 9.0 SDK or later
- MacOS

## Installation

1. Clone the repository:

   ```sh
   git clone https://github.com/samurai-os/hosam.git
   cd hosam
   ```

## Build

To build the project:

```sh
make
```

## Usage

Run the host application:

```sh
make run
```

## Project Structure

- `hosam/` — Main application source code
- `KeyPressHandler.cs` — Keyboard event handling logic
- `Program.cs` — Application entry point
- `LogConfiguration.cs` - Serilog configuration for logging
