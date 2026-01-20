<div align="right">
  <a href="README.pt.md">
    <img src="https://img.shields.io/badge/Ler%20em-Portugu%C3%AAs-green?style=for-the-badge" alt="pt-br">
  </a>
</div>

# LMU Tools - Le Mans Ultimate Tool

LMU Tools is a multifunctional desktop application designed for the *Le Mans Ultimate* racing simulator. It helps drivers optimize car setups and race strategies quickly and intuitively.

> 🚧 **Work In Progress:** The full source code will be released soon. Currently finalizing the beta version.

## Key Features

- **Setup Generator**: Create base setups for any car and track with just a few clicks. Choose from various driving styles (Qualy, Race, Endurance, etc.) to get a competitive starting point.
- **Fuel Calculator**: Uses real-time telemetry to automatically calculate fuel consumption per lap, tank autonomy, and the ideal pit stop strategy.
- **Setup Editor & Comparator**: Open and edit existing setup files (`.svm`) with a user-friendly interface, or compare two setups side-by-side to analyze differences.
- **Multi-Language Support**: Interface available in English and Portuguese.
- **Themes**: Dark and Light modes available.

## Installation (Coming Soon)

1.  **Download**: Navigate to the [Releases](https://github.com/uwaazy/LMU-Tools/releases) section and download the latest version (`LMU_Tool_Setup.exe`).
2.  **Run**: Follow the on-screen instructions.
3.  **First Run**: The tool will ask for your *Le Mans Ultimate* installation folder to manage setups and install the telemetry plugin.

### Telemetry Plugin

The tool automatically installs and enables the `rFactor2SharedMemoryMapPlugin64.dll` plugin in your game folder, which is essential for the real-time fuel calculator.

## How to Use

### Setup Generator

1.  Open the app and go to the **"Setup Generator"** tab.
2.  Select your **Car**.
3.  Choose the **Setup Style** (e.g., "Race", "Qualy").
4.  Select a **Specific Track** or check **"Generate for all tracks"**.
5.  Click **"Generate Setup"**. The `.svm` files will be created directly in your game's userdata folder.

### Fuel Calculator

1.  Go to the **"Fuel Calculator"** tab.
2.  Enter the track in Le Mans Ultimate. The tool detects the car/track automatically.
3.  Complete at least one valid lap. The tool captures your lap time and fuel usage.
4.  Enter the **Race Duration** (in minutes).
5.  Click **"Calculate Strategy"** to view required fuel and pit stop stints.

## Contributing

Contributions will be welcome once the source code is public! Feel free to open an *issue* for feature suggestions in the meantime.

## Developed by

- **uWaazy**