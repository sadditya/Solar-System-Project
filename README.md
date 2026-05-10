# Solar-System-Project

## Overview

Solar-System-Project is a Java-based desktop simulation that visualizes a simple solar system model.
The application uses compiled class files stored in the `src/` folder and starts from the `Main` class.

This README includes:
- a clear description of what the program does
- the main components used in the project
- step-by-step instructions to run it
- a simple analysis of the program architecture

## What the program does

- Displays a solar system animation or interactive view
- Uses a graphical Java UI with separate panels for animation and controls
- Shows planetary movement using object-based planet data
- Demonstrates a basic event-driven desktop application in Java

## Technologies and components used

- Java SE (Java Runtime Environment / Java Development Kit)
- Compiled Java `.class` files located in `src/`
- Main application entry point: `Main`
- Core classes in the project:
  - `SolarSystem` — manages the simulation and planetary setup
  - `Planet` — stores each planet's properties and state
  - `AnimationPanel` — handles the animation rendering
  - `ControlPanel` — provides user controls or interaction

## Program analysis

The project is organized as a compact Java simulation:
1. `Main` launches the application window and starts the solar system simulation.
2. `SolarSystem` creates planet objects and updates animation states.
3. `Planet` defines planet behavior and position data for each body.
4. `AnimationPanel` draws planets and updates frames over time.
5. `ControlPanel` manages any buttons, sliders, or user controls for the view.

This structure separates logic, data, and UI, making the program easier to understand and extend.

## How to run

Follow these simple steps:

1. Install Java if it is not already installed.
2. Open PowerShell or a terminal window.
3. Go to the project folder:
   ```powershell
   cd "C:\Users\singh\OneDrive\Pictures\Solar-System-Project"
   ```
4. Run the project:
   ```powershell
   java -cp src Main
   ```

If the command succeeds, the solar system visualization should appear on your screen.

## Folder structure

- `README.md` — project documentation and instructions
- `src/` — compiled Java class files for the simulation
- `screenshots/` — image assets or example screenshots for the project

## Tips and troubleshooting

- If you see a "Java not recognized" error, install the JDK or JRE and add Java to your PATH.
- If you later replace `src/` with `.java` source files, compile them first with:
  ```powershell
  javac -d src src\*.java
  ```
- Make sure `Main.class` is present in the `src/` directory before running.

## Notes

- This README is designed to make the project easy to use and understand.
- The program is best viewed in a desktop environment that supports Java GUI windows.
