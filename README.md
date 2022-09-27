# Zenburn

![screenshot](example.png)

<!-- Plugin description -->

Zenburn is a low-contrast color scheme for Vim, ported to Intellij.
It's easy on the eyes and designed to keep you in the zone for long
programming sessions. Zenburn has been ported to many different editors
and environments. For more information and list of derivatives, visit
https://kippura.org/zenburnpage.

<!-- Plugin description end -->

## Installation

- Using IDE built-in plugin system:

  <kbd>Settings/Preferences</kbd> > <kbd>Plugins</kbd> > <kbd>Marketplace</kbd> > <kbd>Search for "Zenburn"</kbd> >
  <kbd>Install Plugin</kbd>

- Manually:

  Download the [latest release](https://github.com/smashedtoatoms/zenburn/releases/latest) and install it manually using
  <kbd>Settings/Preferences</kbd> > <kbd>Plugins</kbd> > <kbd>⚙️</kbd> > <kbd>Install plugin from disk...</kbd>

---

Plugin based on the [IntelliJ Platform Plugin Template][template].

[template]: https://github.com/JetBrains/intellij-platform-plugin-template

## How to dev

1. Make changes
2. Update Unreleased section of CHANGELOG.md to represent changes made
3. Increment gradle.properties
4. Test:
   ```sh
   ./gradlew test
   ```
5. Verify:
   ```sh
   ./gradlew verifyPlugin
   ```
6. Build:
   ```sh
   ./gradlew buildPlugin
   ```
7. Release:
   ```sh
   ./gradlew publishPlugin
   ```
