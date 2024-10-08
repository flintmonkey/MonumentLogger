# Monument Logger Plugin

### Version: 1.0.7  
#### Author: FlintMonkey  
#### License: [MIT License](LICENSE)

---

## Overview

The **Monument Logger** plugin for Rust logs all monuments on a server and provides information such as the monument name, prefab path, and location. The plugin supports both the Oxide/uMod and Carbon frameworks. It allows server admins to generate a list of all monuments on current Rust server map in console via command.

This plugin is ideal for server admins who want to review the monuments present on their server, track monument counts, and see their coordinates.

---

## Features

- Logs monument details such as name, prefab path, and in-game location (X, Y, Z).
- Displays the total number of monuments on the server.
- Works across both Oxide/uMod and Carbon frameworks.
- Can be triggered via console command, allowing for flexibility and avoiding clutter on server initialization.

---

## Oxide Installation

1. Download the `MonumentLogger.cs` file and place it in the `oxide/plugins` or `carbon/plugins` directory on your Rust server.
2. Reload the plugin using the console command:

   ```bash
   oxide.reload MonumentLogger

---

## Carbon Installation

1. Download the `MonumentLogger.cs` file and place it in the `oxide/plugins` or `carbon/plugins` directory on your Rust server.
2. Reload the plugin using the console command:
   ```bash
   carbon.reload MonumentLogger

---


## Usage
**Console Command**

Use the `monument_list` console command to print a list of currently installed monuments in console; list includes monument name, prefab, and location.:

---

## License
This project is licensed under the MIT License. See the LICENSE file for details.

---

## Contributions
Feel free to contribute by submitting issues or pull requests. If you'd like to help improve the plugin, follow the contribution guidelines on the GitHub repository.

---

## Support
If you encounter any issues or have suggestions for improvements, please open an issue on the repository.

---

## Disclaimer
This plugin is provided as-is, with no warranty or guarantee. The author is not responsible for any issues caused by the use of this plugin.
