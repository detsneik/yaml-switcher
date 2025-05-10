# YAML Switcher for Obsidian

This plugin for [Obsidian](https://obsidian.md) allows you to quickly modify YAML frontmatter properties in your notes using customizable keyboard shortcuts. Perfect for efficiently managing your notes' metadata.

## Features

* ✍️ **Quick YAML Modification**: Change frontmatter property values with simple keyboard shortcuts.
* ⚙️ **Flexible Configuration**: Add, edit, and remove shortcuts based on your workflow needs.
* 🛠️ **Fully Customizable**: Easily configure YAML properties, values, and keyboard shortcuts for each action.
* 📝 **Text & List Support**: Explicit support for both text and list properties in YAML.
* ⏩ **Automatic Shortcut Capture**: Press the desired keys to capture and assign a shortcut effortlessly.
* 🔄 **Robust Command System**: Seamless integration with Obsidian’s command system for persistent shortcut functionality.
* 🔢 **Automatic Shortcut Naming**: Automatically generates shortcut names based on YAML properties and their values.

## Usage

1. **Install** the plugin from the Obsidian plugin store or install it manually.
2. **Configure** your shortcuts in the plugin settings section.
3. **Use** the assigned keyboard shortcuts to modify YAML properties directly in your notes.

## Example Configuration

The plugin provides a default configuration for managing a "status" property with the following possible values: "todo", "doing", and "done". Each value has its own keyboard shortcut:

| YAML Property | Shortcut | Value | Shortcut Name |
| ------------- | -------- | ----- | ------------- |
| status        | alt+1    | todo  | Status: todo  |
| status        | alt+2    | doing | Status: doing |
| status        | alt+3    | done  | Status: done  |

## Use Cases

* 📝 **Task Management**: Quickly update the status of tasks (e.g., "to do", "in progress", "completed").
* 🏷️ **Note Tagging**: Assign tags or categories to your notes via keyboard shortcuts.
* 📅 **Custom Workflows**: Adapt the plugin to fit your personalized knowledge management system.

## Installation

### From Obsidian Community Plugins

1. Open **Settings** in Obsidian.
2. Go to **Community Plugins**.
3. Search for "**YAML Switcher**".
4. Click **Install**.

### Manual Installation

1. Download the `main.js`, `manifest.json`, and `styles.css` files.
2. Create a folder named `yaml-switcher` in your Obsidian vault's plugin folder: `<Vault>/.obsidian/plugins/`.
3. Place the downloaded files into this folder.
4. Enable the plugin from Obsidian’s settings.

## Configuration

1. Navigate to **Settings > Community Plugins > YAML Switcher**.
2. Add, edit, or remove shortcuts as needed.
3. For each shortcut, configure the following:

   * **YAML Property**: The property key you want to modify.
   * **Value**: The value to assign to the property.
   * **Name**: Automatically generated based on property and value (customizable).
   * **Keyboard Shortcut**: The key combination to activate the shortcut (you can type it or use the "Capture Shortcut" button).
   * **Property Type**: Choose "Text" (plain text) or "List" (YAML list format).
   * **Allow Multiple Values**: For list properties, choose whether to replace existing values or add to them.

## What's New in Version 0.1.0

* ✨ **Enhanced List Management**: Improved handling of list values.
* 🔢 **Property Types**: Now you can choose between "Text", "List (Single)", and "List (Multiple)" properties.
* ⚙️ **Better Control**: Lists can now either replace old values or allow multiple values.
* 🖥️ **Clearer Interface**: Improved UI to indicate whether list properties allow multiple values.

## Development

This plugin is developed using TypeScript and utilizes the [Obsidian API](https://github.com/obsidianmd/obsidian-api).

To contribute:

1. Clone the repository.
2. Run `npm install` to install dependencies.
3. Use `npm run dev` to compile the project in development mode.

## License

This project is licensed under the MIT license.

---

Have any questions or suggestions? Open an issue on the [GitHub repository](https://github.com/detsneik/yaml-switcher).

---

### 🔄 **Changelog**

* **Version 0.1.0**: Initial release with support for text and list properties in YAML.
