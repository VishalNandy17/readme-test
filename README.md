<a name="readme-top"></a>

<div align="center">
  <img src="icon.png" alt="BunnyAI Logo" width="150" height="150">
  <h1>BunnyAI</h1>
  <em>Unleash AI's potential directly in your editor – your intelligent coding companion.</em>
  <p>
    <a href="https://github.com/VishalNandy17/BunnyAI/stargazers"><img src="https://img.shields.io/github/stars/VishalNandy17/BunnyAI?style=for-the-badge&logo=github&logoColor=white&color=yellow" alt="GitHub Stars"></a>
    <a href="https://github.com/VishalNandy17/BunnyAI/network/members"><img src="https://img.shields.io/github/forks/VishalNandy17/BunnyAI?style=for-the-badge&logo=git&logoColor=white&color=blueviolet" alt="GitHub Forks"></a>
    <a href="https://github.com/VishalNandy17/BunnyAI/issues"><img src="https://img.shields.io/github/issues/VishalNandy17/BunnyAI?style=for-the-badge&logo=github&logoColor=white&color=red" alt="GitHub Issues"></a>
    <a href="https://github.com/VishalNandy17/BunnyAI/blob/main/LICENSE"><img src="https://img.shields.io/github/license/VishalNandy17/BunnyAI?style=for-the-badge&color=green" alt="License: MIT"></a>
    <img src="https://img.shields.io/github/last-commit/VishalNandy17/BunnyAI?style=for-the-badge&color=orange" alt="Last Commit">
    <img src="https://img.shields.io/github/languages/top/VishalNandy17/BunnyAI?style=for-the-badge&color=purple" alt="Top Language">
    <img src="https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript">
    <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript">
  </p>
</div>

---

## 📋 Table of Contents

*   [🌟 Description](#-description)
*   [✨ Features](#-features)
*   [🛠️ Tech Stack](#️-tech-stack)
*   [🚀 Getting Started](#-getting-started)
    *   [Prerequisites](#prerequisites)
    *   [Installation](#installation)
    *   [Running the Extension](#running-the-extension)
*   [📦 Project Structure](#-project-structure)
*   [💡 Usage & Examples](#-usage--examples)
*   [🤝 Contributing](#-contributing)
*   [📄 License](#-license)
*   [🙏 Acknowledgments](#-acknowledgments)

---

## 🌟 Description

BunnyAI is an innovative VS Code extension designed to integrate powerful AI capabilities directly into your development workflow. While specific features are under active development, the project aims to provide intelligent assistance, code generation, analysis, and enhanced developer experience through a seamless AI integration. Built with TypeScript, it's crafted to be highly extensible and performant, empowering developers with cutting-edge tools right where they code.

> **Note:** BunnyAI is currently in its early stages of development. The `sample-server.ts` and `bunnyai.example.json` files hint at a client-server architecture, potentially allowing interaction with local or remote AI models.

---

## ✨ Features

*   **Intelligent Code Assistance**: Leverage AI for smarter auto-completions, suggestions, and context-aware help.
*   **AI-Powered Code Generation**: Generate boilerplate code, functions, or even entire components based on natural language prompts.
*   **Refactoring & Optimization Suggestions**: Receive AI-driven recommendations to improve code quality, performance, and maintainability.
*   **Customizable AI Configuration**: Tailor AI behavior and integrate with various models using a flexible configuration (`bunnyai.example.json`).
*   **Seamless VS Code Integration**: Experience AI capabilities without leaving your favorite editor.
*   **Extensible Architecture**: Designed for future expansion, allowing easy integration of new AI models and features.
*   **Local/Remote AI Server Support**: Potential to connect to local AI services or external APIs via the included `sample-server.ts`.

---

## 🛠️ Tech Stack

BunnyAI is built using a robust and modern tech stack, ensuring high performance, maintainability, and a great developer experience.

| Technology | Purpose                                | Version     | Badge                                                                                                                              |
| :--------- | :------------------------------------- | :---------- | :--------------------------------------------------------------------------------------------------------------------------------- |
| TypeScript | Primary development language           | `^5.x`      | ![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)                  |
| Node.js    | Runtime for extension and sample server | `^18.x`     | ![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white)                           |
| VS Code API| Extension development framework        | `^1.x`      | ![VS Code](https://img.shields.io/badge/VS%20Code-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white)                 |
| Webpack    | Module bundler for extension           | `^5.x`      | ![Webpack](https://img.shields.io/badge/Webpack-8DD6F9?style=for-the-badge&logo=webpack&logoColor=black)                           |
| npm        | Package manager                        | `^9.x`      | ![npm](https://img.shields.io/badge/npm-CB3837?style=for-the-badge&logo=npm&logoColor=white)                                       |
| ESLint     | Code linting                           | `^8.x`      | ![ESLint](https://img.shields.io/badge/ESLint-4B32C3?style=for-the-badge&logo=eslint&logoColor=white)                             |
| Mocha      | Testing framework (for `test` folder)  | `^10.x`     | ![Mocha](https://img.shields.io/badge/Mocha-8D6748?style=for-the-badge&logo=mocha&logoColor=white)                                |

---

## 🚀 Getting Started

To get BunnyAI up and running, follow these steps. This guide covers setting up the development environment for the VS Code extension.

### Prerequisites

Before you begin, ensure you have the following installed on your system:

*   **Node.js**: Version 18.x or higher.
    ```bash
    node -v
    # Expected output: v18.x.x or higher
    ```
*   **npm**: Node.js package manager (comes with Node.js).
    ```bash
    npm -v
    # Expected output: 9.x.x or higher
    ```
*   **Visual Studio Code**: The editor itself.
    [Download VS Code](https://code.visualstudio.com/)
*   **Git**: For cloning the repository.
    ```bash
    git --version
    # Expected output: git version 2.x.x or higher
    ```

### Installation

1.  **Clone the repository**:
    ```bash
    git clone https://github.com/VishalNandy17/BunnyAI.git
    cd BunnyAI
    ```

2.  **Install dependencies**:
    ```bash
    npm install
    ```
    This command will install all the necessary packages defined in `package.json`.

### Running the Extension

There are a few ways to run and test BunnyAI:

<details>
<summary>⚡️ **Option 1: Run in VS Code Development Host (Recommended for Development)**</summary>

This is the easiest way to debug and develop the extension.

1.  **Open the project in VS Code**:
    ```bash
    code .
    ```
2.  **Start Debugging**:
    *   Press `F5` (or go to `Run` > `Start Debugging`).
    *   A new VS Code window (Extension Development Host) will open. This window has the BunnyAI extension loaded.
3.  **Test the extension**:
    *   Any changes you make to the source code will require restarting the Extension Development Host window (`Ctrl+R` or `Cmd+R` in the host window, or `F5` again in the original window).

</details>

<details>
<summary>📦 **Option 2: Package and Install VSIX (For Testing the Packaged Extension)**</summary>

To test the extension as a distributable `.vsix` package:

1.  **Install `vsce`**: The Visual Studio Code Extension Manager.
    ```bash
    npm install -g vsce
    ```
2.  **Package the extension**:
    ```bash
    vsce package
    ```
    This will create a `.vsix` file (e.g., `bunnyai-0.0.1.vsix`) in the project root.
3.  **Install the VSIX**:
    *   Open VS Code.
    *   Go to the Extensions view (`Ctrl+Shift+X` or `Cmd+Shift+X`).
    *   Click on the `...` (More Actions) menu at the top of the Extensions sidebar.
    *   Select `Install from VSIX...` and choose the `.vsix` file you just created.
    *   Refer to `INSTALL_VSIX.md` for detailed instructions.

</details>

<details>
<summary>⚙️ **Option 3: Running the Sample Server (If Applicable)**</summary>

If BunnyAI requires a backend service (as hinted by `sample-server.ts`), you might need to run it separately.

1.  **Compile the sample server (if TypeScript)**:
    ```bash
    npm run build-server # Or similar command if defined in package.json
    ```
    (Currently, there's `sample-server.ts` and `sample-server.js`, so it might be directly runnable or needs compilation if `ts-node` is not used).

2.  **Run the server**:
    ```bash
    node sample-server.js
    ```
    or
    ```bash
    ts-node sample-server.ts # If ts-node is installed
    ```
    Check `HOW_TO_RUN.md` for specific instructions on running the sample server and connecting the extension to it.

</details>

---

## 📦 Project Structure

The repository is organized to facilitate development, testing, and deployment of the BunnyAI VS Code extension.

<details>
<summary>📂 **Expand to view detailed project structure**</summary>

```
BunnyAI/
├── .eslintrc.json           # ESLint configuration for code quality
├── .gitignore               # Specifies intentionally untracked files to ignore
├── .vscode/                 # VS Code specific settings and launch configurations
│   └── (e.g., launch.json, settings.json)
├── .vscodeignore            # Specifies files to exclude when packaging the extension
├── ARCHITECTURE.md          # Documentation on the project's architectural design
├── CONTRIBUTING.md          # Guidelines for contributing to the project
├── HOW_TO_RUN.md            # Detailed instructions on running various parts of the project
├── IMPLEMENTATION_SUMMARY.md# High-level overview of implementation details
├── INSTALL_VSIX.md          # Guide for installing the packaged .vsix extension
├── LICENSE                  # Project's MIT License
├── PRODUCTION_READY_SUMMARY.md# Summary of steps for production readiness
├── README.MD                # This README file
├── TESTING_GUIDE.md         # Guide for running and writing tests
├── bunnyai.example.json     # Example configuration file for BunnyAI settings
├── icon.png                 # Project icon
├── media/                   # Directory for screenshots, GIFs, or other media
│   └── (e.g., screenshot.png)
├── package-lock.json        # Records the exact dependency tree
├── package.json             # Project metadata, scripts, and dependencies
├── resources/               # Directory for additional static resources
│   └── (e.g., templates, assets)
├── sample-server.js         # JavaScript version of a sample backend server
├── sample-server.ts         # TypeScript source for a sample backend server (potential AI service)
├── src/                     # Source code for the VS Code extension
│   ├── extension.ts         # Main extension entry point
│   └── (other source files for commands, providers, etc.)
├── test/                    # Unit and integration tests for the extension
│   ├── runTest.ts           # Test runner setup
│   └── extension.test.ts    # Example test file
├── tsconfig.json            # TypeScript compiler configuration for the main project
├── tsconfig.test.json       # TypeScript compiler configuration specifically for tests
└── webpack.config.js        # Webpack configuration for bundling the extension
```
</details>

---

## 💡 Usage & Examples

Once BunnyAI is installed and running in your VS Code environment, you can start leveraging its AI capabilities.

> **Tip:** Make sure the `sample-server` (if configured to be used) is running in the background for full functionality.

### ⚙️ Configuration

BunnyAI uses a configuration file (similar to `bunnyai.example.json`) to customize AI models, endpoints, and behaviors. You might find a `bunnyai.json` or similar in your workspace root, or configure it via VS Code settings.

**Example `bunnyai.json` (Hypothetical):**

```json
{
  "bunnyai.enabled": true,
  "bunnyai.defaultModel": "gpt-4o-mini",
  "bunnyai.serverUrl": "http://localhost:3000/api/ai",
  "bunnyai.features": {
    "codeCompletion": true,
    "codeGeneration": {
      "enabled": true,
      "shortcut": "alt+shift+g"
    },
    "refactoringSuggestions": true
  },
  "bunnyai.ignoredFiles": [
    "**/node_modules/**",
    "**/*.min.js"
  ]
}
```

### 🧑‍💻 Code Generation Example

You can trigger AI-powered code generation through specific commands or keyboard shortcuts.

1.  **Open a TypeScript/JavaScript file** in your editor.
2.  **Add a comment** describing what you want the AI to generate:
    ```typescript
    // bunnyai: Generate a function that calculates the factorial of a number
    // and handles non-integer inputs.
    ```
3.  **Trigger the command**:
    *   Place your cursor on the line below the comment.
    *   Open the Command Palette (`Ctrl+Shift+P` or `Cmd+Shift+P`).
    *   Search for "BunnyAI: Generate Code" and select it (or use the configured shortcut, e.g., `Alt+Shift+G`).

4.  **AI Output (Example):**
    ```typescript
    // bunnyai: Generate a function that calculates the factorial of a number
    // and handles non-integer inputs.
    function factorial(n: number): number | string {
      if (n < 0) {
        return "Factorial is not defined for negative numbers.";
      }
      if (!Number.isInteger(n)) {
        return "Factorial is only defined for integers.";
      }
      if (n === 0) {
        return 1;
      }
      let result = 1;
      for (let i = 1; i <= n; i++) {
        result *= i;
      }
      return result;
    }

    console.log(factorial(5));  // Output: 120
    console.log(factorial(0));  // Output: 1
    console.log(factorial(-3)); // Output: Factorial is not defined for negative numbers.
    console.log(factorial(3.5)); // Output: Factorial is only defined for integers.
    ```
    The AI will insert the generated code directly into your editor.

### 🔍 Refactoring Suggestions

BunnyAI can analyze your code and suggest improvements.

1.  **Select a block of code** you wish to refactor.
2.  **Right-click** on the selection.
3.  Select "BunnyAI: Get Refactoring Suggestions".
4.  A quick pick or a dedicated view will show potential improvements.

---

## 🤝 Contributing

We welcome contributions to BunnyAI! Whether it's reporting a bug, suggesting a feature, or submitting a pull request, your help is invaluable.

Please refer to the [CONTRIBUTING.md](CONTRIBUTING.md) file for detailed guidelines on how to contribute to this project.

### Contributors

A huge thanks to all who have contributed to BunnyAI!

<a href="https://github.com/VishalNandy17/BunnyAI/graphs/contributors"><img src="https://contrib.rocks/image?repo=VishalNandy17/BunnyAI" /></a>

---

## 📄 License

BunnyAI is released under the [MIT License](LICENSE). You are free to use, modify, and distribute this software under the terms of this license.

---

## 🙏 Acknowledgments

*   The VS Code team for providing an excellent platform and comprehensive API for extension development.
*   The open-source community for countless tools and libraries that make projects like BunnyAI possible.
*   All contributors and users who provide feedback and support.

---

<p align="right">(<a href="#readme-top">back to top</a>)</p>

Made with ❤️
