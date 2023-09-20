<!-- ===== HEADER (Badges) ===== -->

<h1 align="center">
  <a
    href="https://guipmdev-dt-money.vercel.app/"
    rel="noopener noreferrer"
    target="_blank"
    title="Go to the web application"
  >
    <img src="./src/assets/logo.svg" alt="DT Money logo" height="60px" />
  </a>
</h1>

<p align="center">
  <img
    src="https://img.shields.io/github/languages/count/guipmdev/dt-money?color=%2304D361&labelColor=202024"
    alt="Repository language count"
  />
  <img
    src="https://img.shields.io/github/repo-size/guipmdev/dt-money?labelColor=202024"
    alt="Repository size"
  />
  <img
    src="https://img.shields.io/github/commit-activity/m/guipmdev/dt-money?color=gray&labelColor=202024"
    alt="Commit activity"
  />
  <a
    href="https://github.com/guipmdev/dt-money/commits/main"
    rel="noopener noreferrer"
    target="_blank"
    title="View repository commits"
  >
    <img
      src="https://img.shields.io/github/last-commit/guipmdev/dt-money?labelColor=202024"
      alt="Last commit"
    />
  </a>
  <a
    href="./LICENSE"
    rel="noopener noreferrer"
    target="_blank"
    title="View project license"
  >
    <img
      src="https://img.shields.io/badge/license-MIT-brightgreen?labelColor=202024"
      alt="Project license"
    />
  </a>
  <a
    href="https://www.rocketseat.com.br/"
    rel="noopener noreferrer"
    target="_blank"
    title="Go to the Rocketseat website"
  >
    <img
      src="https://img.shields.io/badge/Layout_by-Rocketseat-8257e5?labelColor=202024"
      alt="Layout designer"
    />
  </a>
</p>

![Screenshot of the application initial page](./src/assets/images/cover.png)

<p align="center">
  <a
    href="https://guipmdev-dt-money.vercel.app/"
    rel="noopener noreferrer"
    target="_blank"
    >Go to the web application ↗</a
  >
</p>

<details>
  <summary>
    <h2>📒 Table of Contents</h2>
  </summary>

- [📍 Overview](#-overview)
  - [⚠️ Disclaimer](#️-disclaimer)
- [✨ Features](#-features)
- [🤖 Demo](#-demo)
- [🎨 Layout](#-layout)
- [🛠 Technologies](#-technologies)
  - [Website](#website)
  - [Server](#server)
  - [Utils](#utils)
- [🚀 Getting Started](#-getting-started)
  - [✔️ Prerequisites](#️-prerequisites)
  - [📦 Installation](#-installation)
  - [⚙️ Using](#️-using)
- [📄 License](#-license)
- [👏 Acknowledgments](#-acknowledgments)
</details>

<!-- ===== PROJECT INFOS ===== -->

## 📍 Overview

The project is a web-based financial application built with React and TypeScript. It allows users to manage their transactions by creating, viewing, and searching for transactions. The core functionalities include displaying a summary of income, outcome, and overall balance, creating new transactions, and searching for transactions based on user input.

The purpose of the project is to provide an intuitive and user-friendly interface for managing personal finances, keeping track of transactions, and organizing financial data effectively. Its value proposition lies in its simplicity, efficiency, and the ability to provide important financial insights to users.

### ⚠️ Disclaimer

The back-end of this application is built with JSON Server and does not have a deployment, as the focus is primarily on the front-end. To fully test the application, you'll need to clone the repository, run the `dev:server` script, and then open the website.

## ✨ Features

| Feature                        | Description                                           |
| ------------------------------ | ----------------------------------------------------- |
| **➕ Transactions management** | Add your incomes and outcomes.                        |
| **🔎 Transactions search**     | Search your incomes and outcomes by name or category. |
| **📊 Financial Summary**       | View summary of income, outcome, and overall balance. |

## 🤖 Demo

<p align="center">
  <video src="./src/assets/videos/dt-money.mp4" width="75%" />
</p>

## 🎨 Layout

The layout of the application was designed by **Rocketseat** and is available on [Figma](<https://www.figma.com/file/fYmLz2A4boqht18Yjbri9i/DT-Money-(Community)>).

<p align="center">
  <img
    src="./src/assets/images/layout-cover.png"
    alt="Web application layout image cover"
    width="50%"
  />
</p>

## 🛠 Technologies

The following tools were used to build the project:

### Website

<p>
  <a href="https://vitejs.dev/" rel="noopener noreferrer" target="_blank">
    <img
      src="https://img.shields.io/badge/Vite-1e1e20.svg?logo=Vite"
      alt="Vite"
    />
  </a>
  <a href="https://react.dev/" rel="noopener noreferrer" target="_blank">
    <img
      src="https://img.shields.io/badge/React-23272f.svg?logo=React"
      alt="React"
    />
  </a>
  <a
    href="https://www.typescriptlang.org/"
    rel="noopener noreferrer"
    target="_blank"
  >
    <img
      src="https://img.shields.io/badge/TypeScript-white.svg?logo=TypeScript"
      alt="TypeScript"
    />
  </a>
  <a href="https://eslint.org/" rel="noopener noreferrer" target="_blank">
    <img
      src="https://img.shields.io/badge/ESLint-101828.svg?logo=ESLint"
      alt="ESLint"
    />
  </a>
  <a
    href="https://github.com/rocketseat/eslint-config-rocketseat"
    rel="noopener noreferrer"
    target="_blank"
  >
    <img
      src="https://img.shields.io/badge/Rocketseat_ESLint_config-gray"
      alt="Rocketseat ESLint config"
    />
  </a>
</p>

<p>
  <a href="https://axios-http.com/" rel="noopener noreferrer" target="_blank">
    <img
      src="https://img.shields.io/badge/Axios-373747.svg?logo=Axios"
      alt="Axios"
    />
  </a>
  <a
    href="https://react-hook-form.com/"
    rel="noopener noreferrer"
    target="_blank"
  >
    <img
      src="https://img.shields.io/badge/React_Hook_Form-060e21.svg?logo=react-hook-form"
      alt="React Hook Form"
    />
  </a>
  <a
    href="https://github.com/colinhacks/zod"
    rel="noopener noreferrer"
    target="_blank"
  >
    <img src="https://img.shields.io/badge/Zod-3068b7.svg?logo=zod" alt="Zod" />
  </a>
  <a
    href="https://github.com/dai-shi/use-context-selector"
    rel="noopener noreferrer"
    target="_blank"
  >
    <img
      src="https://img.shields.io/badge/use--context--selector-gray"
      alt="use-context-selector"
    />
  </a>
  <a
    href="https://www.npmjs.com/package/scheduler"
    rel="noopener noreferrer"
    target="_blank"
  >
    <img src="https://img.shields.io/badge/scheduler-gray" alt="scheduler" />
  </a>
</p>

<p>
  <a
    href="https://styled-components.com/"
    rel="noopener noreferrer"
    target="_blank"
  >
    <img
      src="https://img.shields.io/badge/styled--components-0c0d0f.svg?logo=styled-components"
      alt="styled-components"
    />
  </a>
  <a href="https://www.radix-ui.com/" rel="noopener noreferrer" target="_blank">
    <img
      src="https://img.shields.io/badge/Radix_UI-1a181c.svg?logo=radixui"
      alt="Radix UI"
    />
  </a>
  <a
    href="https://phosphoricons.com/"
    rel="noopener noreferrer"
    target="_blank"
  >
    <img
      src="https://img.shields.io/badge/Phosphor_Icons-eeeae3.svg?logo=data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iMzMiIGhlaWdodD0iNDQiIHZpZXdCb3g9IjAgMCAzMyA0NCIgZmlsbD0ibm9uZSIKICB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciPgogIDxwYXRoIGQ9Ik0xNy4xMDI2IDAuMDUwMjU3NUgxLjQ5NDM0QzEuMTk0NDYgMC4wNTAyNTc1IDAuOTA2ODU5IDAuMTY5MzggMC42OTQ4MTUgMC4zODE0MjVDMC40ODI3NyAwLjU5MzQ3IDAuMzYzNjQ3IDAuODgxMDU2IDAuMzYzNjQ3IDEuMTgwOTNWMjguOTE4OUMwLjM2NzQ2NCAzMi44OTQ4IDEuOTQ3OTMgMzYuNzA3IDQuNzU4NDUgMzkuNTE5M0M3LjU2ODk3IDQyLjMzMTYgMTEuMzgwMSA0My45MTQ1IDE1LjM1NjEgNDMuOTIwOUMxNS41MDQ1IDQzLjkyMDkgMTUuNjUxNiA0My44OTE3IDE1Ljc4ODcgNDMuODM0OEMxNS45MjU5IDQzLjc3OCAxNi4wNTA2IDQzLjY5NDcgMTYuMTU1NiA0My41ODk3QzE2LjI2MDYgNDMuNDg0NyAxNi4zNDM4IDQzLjM2MDEgMTYuNDAwNyA0My4yMjI5QzE2LjQ1NzUgNDMuMDg1NyAxNi40ODY3IDQyLjkzODcgMTYuNDg2NyA0Mi43OTAyVjMwLjA0OTVIMTcuMDkzQzE5LjA4NTQgMzAuMDg1MiAyMS4wNjQ5IDI5LjcyMzYgMjIuOTE2IDI4Ljk4NThDMjQuNzY3MSAyOC4yNDgxIDI2LjQ1MjYgMjcuMTQ4OSAyNy44NzQyIDI1Ljc1MjVDMjkuMjk1OSAyNC4zNTYxIDMwLjQyNSAyMi42OTA1IDMxLjE5NTkgMjAuODUyOUMzMS45NjY3IDE5LjAxNTMgMzIuMzYzNyAxNy4wNDI2IDMyLjM2MzcgMTUuMDQ5OUMzMi4zNjM3IDEzLjA1NzIgMzEuOTY2NyAxMS4wODQ1IDMxLjE5NTkgOS4yNDY4N0MzMC40MjUgNy40MDkyOCAyOS4yOTU5IDUuNzQzNjYgMjcuODc0MiA0LjM0NzI4QzI2LjQ1MjYgMi45NTA4OSAyNC43NjcxIDEuODUxNzMgMjIuOTE2IDEuMTEzOTVDMjEuMDY0OSAwLjM3NjE2OCAxOS4wODU0IDAuMDE0NTcyMyAxNy4wOTMgMC4wNTAyNTc1SDE3LjEwMjZaTTE0LjIxNTcgNDEuNjExNEMxMS4yNDQzIDQxLjM0MTIgOC40NjE1OSA0MC4wMzc4IDYuMzUxNzggMzcuOTI4QzQuMjQxOTcgMzUuODE4MSAyLjkzODU2IDMzLjAzNTQgMi42NjgzMiAzMC4wNjRIMTQuMjE1N1Y0MS42MTE0Wk0xNC4yMTU3IDI0LjEzMTVMMy4zMjc0OSAyLjMxMTYxSDE0LjIzNUwxNC4yMTU3IDI0LjEzMTVaTTE3LjEwMjYgMjcuNzg4MkgxNi40OTY0VjIuMzExNjFIMTcuMTAyNkMxOC43OTYyIDIuMjc4NjkgMjAuNDc5NCAyLjU4Mzg2IDIyLjA1MzcgMy4yMDkyM0MyMy42MjggMy44MzQ2IDI1LjA2MTggNC43Njc2MyAyNi4yNzEyIDUuOTUzNzVDMjcuNDgwNiA3LjEzOTg3IDI4LjQ0MTMgOC41NTUyNyAyOS4wOTcyIDEwLjExNzFDMjkuNzUzIDExLjY3OSAzMC4wOTA4IDEzLjM1NTkgMzAuMDkwOCAxNS4wNDk5QzMwLjA5MDggMTYuNzQzOSAyOS43NTMgMTguNDIwOCAyOS4wOTcyIDE5Ljk4MjdDMjguNDQxMyAyMS41NDQ1IDI3LjQ4MDYgMjIuOTU5OSAyNi4yNzEyIDI0LjE0NkMyNS4wNjE4IDI1LjMzMjEgMjMuNjI4IDI2LjI2NTIgMjIuMDUzNyAyNi44OTA2QzIwLjQ3OTQgMjcuNTE1OSAxOC43OTYyIDI3LjgyMTEgMTcuMTAyNiAyNy43ODgyWiIgZmlsbD0iY3VycmVudENvbG9yIi8+Cjwvc3ZnPgo="
      alt="Phosphor Icons"
    />
  </a>
</p>

### Server

<p>
  <a
    href="https://github.com/typicode/json-server"
    rel="noopener noreferrer"
    target="_blank"
  >
    <img
      src="https://img.shields.io/badge/JSON_Server-gray"
      alt="JSON Server"
    />
  </a>
</p>

_\* See the [<kbd>package.json</kbd>](./package.json) file_

### Utils

<p>
  <a href="https://figma.com/" rel="noopener noreferrer" target="_blank">
    <img
      src="https://img.shields.io/badge/Figma-white.svg?logo=figma"
      alt="Figma"
    />
  </a>
  <a href="https://fonts.google.com/" rel="noopener noreferrer" target="_blank">
    <img
      src="https://img.shields.io/badge/Google_Fonts-white.svg?logo=google-fonts"
      alt="Google Fonts"
    />
  </a>
  <a href="https://httpie.io/" rel="noopener noreferrer" target="_blank">
    <img
      src="https://img.shields.io/badge/HTTPie-1e1919.svg?logo=httpie"
      alt="HTTPie"
    />
  </a>
  <a
    href="https://code.visualstudio.com/"
    rel="noopener noreferrer"
    target="_blank"
  >
    <img
      src="https://img.shields.io/badge/VSCode-005293.svg?logo=visual-studio-code"
      alt="VSCode"
    />
  </a>
</p>

## 🚀 Getting Started

### ✔️ Prerequisites

Before you begin, ensure that you have the following tools installed on your machine: [Git](https://git-scm.com/downloads), [Node.js](https://nodejs.org/en/download). It's also good to have an editor to work with the code, such as [VSCode](https://code.visualstudio.com/Download).

### 📦 Installation

1. Clone the `dt-money` repository:

```sh
git clone https://github.com/guipmdev/dt-money/
```

2. Change to the project directory:

```sh
cd dt-money
```

3. Install the dependencies:

```sh
npm install
```

### ⚙️ Using

1. Start the JSON Server:

```sh
npm run dev:server
```

2. In another terminal, start the web application:

```sh
npm run dev
```

3. Access https://localhost:5173/ (or https://guipmdev-dt-money.vercel.app/) to view the application

## 📄 License

This project is licensed under the terms of the `MIT` license. See the
[LICENSE](./LICENSE) file for additional info.

## 👏 Acknowledgments

> - Many thanks to [Rocketseat](https://www.rocketseat.com.br/) for the layout and tips when putting this project together

<!-- ===== FOOTER ===== -->

---

<p align="center">
  Made with 💙 by
  <a href="https://www.guipm.dev/" rel="noopener noreferrer" target="_blank">
    @guipm.dev
  </a>
  - Feel free to
  <a href="mailto:guipm.dev@gmail.com" rel="noopener noreferrer" target="_blank"
    >contact me</a
  >!
</p>

<br />

<p align="center">
  <a href="#top">
    <b>↑&nbsp;&nbsp; Return to the top &nbsp;&nbsp;↑</b>
  </a>
</p>
