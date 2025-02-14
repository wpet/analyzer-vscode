# Analyzer VS Code Extension

The **Analyzer VS Code Extension** provides full language support for Analyzer files (.pro). This extension offers syntax highlighting, language configurations, and handy code snippets to boost your productivity when editing Analyzer scripts.

## Features

- **Syntax Highlighting:**  
  Uses a TextMate grammar (`analyzer.tmLanguage.json`) to provide rich syntax highlighting for Analyzer files.

- **Code Snippets:**  
  Quickly insert common code patterns using our pre-defined snippets from `analyzer.code-snippets.json`.

- **Language Configuration:**  
  Customized language settings including comment toggling, bracket matching, and more defined in the `language-configuration.json`.

## Installation

### Prerequisites

- [Visual Studio Code](https://code.visualstudio.com/)
- [Node.js and npm](https://nodejs.org/) (for development purposes)

### Install from VSIX

1. Download the latest `.vsix` package.
2. In VS Code, go to the **Extensions** view (press `Ctrl+Shift+X` or `Cmd+Shift+X` on macOS).
3. Click on the ellipsis (...) in the top-right corner and select **Install from VSIX...**.
4. Choose the downloaded file to install the extension.

### Install from the Marketplace

Alternatively, if published to the [VS Code Marketplace](https://marketplace.visualstudio.com/), search for `Analyzer` in the Extensions view and click **Install**.

## Usage

1. **Open an Analyzer File:**  
   Files with the extension `.analyzer` will automatically use the Analyzer language support.
2. **Syntax Highlighting:**  
   Enjoy improved readability with the dedicated syntax highlighting.
3. **Insert Snippets:**  
   Start typing a snippet prefix (as defined in `analyzer.code-snippets.json`) and press `Tab` to insert the code snippet.
4. **Language Features:**  
   Leverage language-specific configurations (comments, brackets, etc.) provided by the extension.

## Development

To create or modify the extension:

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/yourusername/your-analyzer-extension.git
   cd your-analyzer-extension
   ```

2. **Install Dependencies:**

   ```bash
   npm install
   ```

3. **Run the Extension in Debug Mode:**

   Press `F5` in VS Code to open a new Extension Development Host.

4. **Edit JSON Files:**

   - Place your grammar file (e.g., `analyzer.tmLanguage.json`) in the `syntaxes` folder.
   - Place your snippets file (e.g., `analyzer.code-snippets.json`) in the `snippets` folder.
   - Update the `package.json` under the `"contributes"` section to reference your JSON files.

## Contributing

Contributions to the Analyzer extension are welcome! If you have ideas, bug reports, or enhancements, please:

1. Fork the repository.
2. Create a new branch for your feature or fix.
3. Submit a pull request with a detailed description of your changes.

For any questions or issues, please open an issue on [GitHub](https://github.com/yourusername/your-analyzer-extension/issues).

## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgments

- [Visual Studio Code API](https://code.visualstudio.com/api)
- [VS Code Language Extensions](https://code.visualstudio.com/api/language-extensions/syntax-highlight-guide)
- Thanks to the community for support and contributions.
