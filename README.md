# Biome - IntelliJ Plugin

[![IntelliJ IDEA Ultimate Version](https://img.shields.io/badge/IntelliJ%20IDEA%20Ultimate-2023.2.2-374151.svg?labelcolor=000&logo=intellij-idea&labelColor=black)](https://www.jetbrains.com/idea/)
[![WebStorm Version](https://img.shields.io/badge/WebStorm-2023.2.2-1F3263.svg?labelcolor=000&logo=webstorm&labelColor=black)](https://www.jetbrains.com/webstorm/)
[![AppCode Version](https://img.shields.io/badge/AppCode-2023.2.2-2380B0.svg?labelcolor=000&logo=appcode&labelColor=black)](https://www.jetbrains.com/objc/)
[![PhpStorm Version](https://img.shields.io/badge/PhpStorm-2023.2.2-953D8C.svg?labelcolor=000&logo=phpstorm&labelColor=black)](https://www.jetbrains.com/phpstorm/)
[![RubyMine Version](https://img.shields.io/badge/RubyMine-2023.2.2-A11523.svg?labelcolor=000&logo=ruby&labelColor=black)](https://www.jetbrains.com/ruby/)

[Biome](https://biomejs.dev/) is a powerful tool designed to enhance your development experience. 
This plugin integrates seamlessly with many [JetBrains IDE's](#supported-ides) to provide the following capabilities.

- 💡 See lints while you type
- 👨‍💻 Apply code fixes
- 🚧 Reformat your code
- 💾 Automatically applying code fixes on save

## Installation

To install the Biome IntelliJ plugin, head over to the [official plugin page](https://plugins.jetbrains.com/plugin/22761-biome) or follow these steps:

### From JetBrains IDEs

1. Open IntelliJ IDEA.
2. Go to **Settings/Preferences**.
3. Select **Plugins** from the left-hand menu.
4. Click on the **Marketplace** tab.
5. Search for "Biome" and click **Install**.
6. Restart the IDE to activate the plugin.

### From disk

1. Download the plugin .zip from the *releases* tab.
2. Press <kbd>⌘Cmd + ,</kbd> to open the IDE settings and then select *Plugins*.
3. On the Plugins page, click the *Settings* button and then click *Install Plugin from Disk…*.

## Getting Started
### Biome Resolution

The plugin tries to use Biome from your project’s local dependencies (`node_modules/.bin/biome`). We recommend adding Biome as a project dependency to ensure that NPM scripts and the extension use the same Biome version.

You can also explicitly specify the `biome` binary the extension should use by configuring the `Biome CLI Path` in `Settings`->`Language & Frameworks`->`Biome Settings`.

### Plugin settings

#### `Biome CLI Path`

This setting overrides the Biome binary used by the plugin.

### Supported IDEs

This plugin is currently supported in the following IDEs:

- [![IntelliJ IDEA Ultimate Version](https://img.shields.io/badge/IntelliJ%20IDEA%20Ultimate-2023.2.2-374151.svg?labelcolor=000&logo=intellij-idea&labelColor=black)](https://www.jetbrains.com/idea/)
  
- [![WebStorm Version](https://img.shields.io/badge/WebStorm-2023.2.2-1F3263.svg?labelcolor=000&logo=webstorm&labelColor=black)](https://www.jetbrains.com/webstorm/)

- [![AppCode Version](https://img.shields.io/badge/AppCode-2023.2.2-2380B0.svg?labelcolor=000&logo=appcode&labelColor=black)](https://www.jetbrains.com/objc/)

- [![PhpStorm Version](https://img.shields.io/badge/PhpStorm-2023.2.2-953D8C.svg?labelcolor=000&logo=phpstorm&labelColor=black)](https://www.jetbrains.com/phpstorm/)

- [![RubyMine Version](https://img.shields.io/badge/RubyMine-2023.2.2-A11523.svg?labelcolor=000&logo=ruby&labelColor=black)](https://www.jetbrains.com/ruby/)

## Usage

Biome CLI comes with many commands and options, so you can use only what you need.

Apply code fixes by either hovering over the relevant section and selecting the suggested fix, pressing <kbd title="Option">⌥</kbd>+<kbd  title="Enter">⏎</kbd>(Option+Enter) or <kbd title="Alt">Alt</kbd>+<kbd title="Enter">Enter</kbd>.

To reformat your code, use the keyboard shortcut <kbd>⌥⇧</kbd>+<kbd title="Cmd">⌘</kbd>+<kbd  title="L">L</kbd> or <kbd title="Ctrl">Ctrl</kbd>+<kbd title="Alt">Alt</kbd>+<kbd  title="L">L</kbd>. Alternatively, you can configure your IDE to format [code automatically on save](https://www.jetbrains.com/help/webstorm/reformat-and-rearrange-code.html#reformat-on-save)  for a seamless coding experience.
