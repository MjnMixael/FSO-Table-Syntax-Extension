# FreespaceOpen Table Syntax

`fso-table-syntax` is a Visual Studio Code extension providing syntax highlighting and embedded Lua support for FreespaceOpen table (`.tbl`, `.tbm`) and mission files (`.fc2`, `.fs2`). This extension makes working with FreespaceOpen configurations and scripts easier and more efficient by offering clean, intuitive highlighting tailored to the format.

---

## Features

- **Custom Syntax Highlighting**:
  - Supports sections (`#`), parent flags (`$`), child flags (`+`), and special flags like `@Laser`.
  - Highlights constants, operators, strings, and comments.

- **Embedded Lua Support**:
  - Lua code inside `$<flag>: [...]` blocks is highlighted and can integrate with the Lua language server for full functionality.

- **File Icon Support**:
  - Provides a custom file icon for `.tbl`, `.tbm`, `.fc2`, and `.fs2` files in the Explorer.

---

## Requirements

- **Lua Language Server (Optional)**:
  To enable advanced Lua functionality (e.g., IntelliSense, Go to Definition, Peek), install the [Sumneko Lua](https://marketplace.visualstudio.com/items?itemName=sumneko.lua) extension in VS Code.

---

## Extension Settings

This extension doesn’t add custom settings but relies on your existing VS Code and Lua language server configurations. Ensure the Lua language server is set up for embedded Lua support.

---

## Known Issues

- **Lua Language Features**:
  Full Lua language server functionality inside embedded Lua blocks requires proper configuration. Refer to the "Requirements" section for details.

---

## Release Notes

### 1.0.0

- Initial release with:
  - Syntax highlighting for FreespaceOpen table and mission files.
  - Embedded Lua support.
  - Custom file icon integration.

---

## Contributing

Feedback and contributions are welcome! If you encounter any issues or have suggestions, feel free to open an issue on the [GitHub repository](https://github.com/MjnMixael/FSO-Table-Syntax-Extension).

---

## For More Information

- [FreespaceOpen Wiki](https://wiki.hard-light.net/)

**Enjoy using `fso-table-syntax` to simplify your FreespaceOpen workflows!**
