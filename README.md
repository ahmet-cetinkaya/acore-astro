# ![ACore Astro logo](https://github.com/user-attachments/assets/230a4c30-dc62-41d6-9cd5-c701709e6022) `acore-astro` ![GitHub stars](https://img.shields.io/github/stars/ahmet-cetinkaya/acore-astro?style=social) ![GitHub forks](https://img.shields.io/github/forks/ahmet-cetinkaya/acore-astro?style=social) [![Buy Me A Coffee](https://img.shields.io/badge/Buy%20Me%20a%20Coffee-ffdd00?&logo=buy-me-a-coffee&logoColor=black)](https://ahmetcetinkaya.me/donate)

This repository serves as a core package written in TypeScript, containing various implementations and helper code snippets specifically for Astro. It aims to provide optimized and reusable solutions for different areas of software development, tailored for Astro applications.

## 💻 Technologies Used

This project is built using the following technologies:

[![Astro](https://img.shields.io/badge/Astro-FF5D01?style=for-the-badge&logo=astro&logoColor=white)](https://astro.build/)
[![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)](https://www.typescriptlang.org/)
[![Bun](https://img.shields.io/badge/Bun-000000?style=for-the-badge&logo=bun&logoColor=white)](https://bun.sh/)

### Minimal Package Usage

This project minimizes the use of external packages. When necessary, implementations are written using core packages to ensure better control and optimization of the codebase.

### Astro Specific Implementations

`acore-astro` contains Astro-specific code and helper functions, providing optimized and reusable solutions tailored for Astro applications.

## ⚡ Getting Started

This section explains how to get your project up and running.

### 📋 Requirements

- bun

### 🛠️ Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/ahmet-cetinkaya/acore-astro.git
   ```

2. Navigate into the project directory:

   ```bash
   cd acore-astro
   ```

3. Install the dependencies:

   ```bash
   bun install
   ```

## 📦 Adding as a Submodule

To add this repository as a submodule to another project, follow these steps:

1. Navigate to your project directory:

   ```bash
   cd your-project-directory
   ```

2. Add the submodule:

   ```bash
   git submodule add https://github.com/ahmet-cetinkaya/acore-astro.git path/to/submodule
   ```

3. Initialize and update the submodule:

   ```bash
   git submodule update --init --recursive
   ```

4. Navigate into the submodule directory and install dependencies:

   ```bash
   cd path/to/submodule
   bun install
   ```

## 🤝 Contributing

If you'd like to contribute, please follow these steps:

1. Fork the repository
2. Create a new branch (`git checkout -b feat/feature-branch`)
3. Make your changes
4. Commit your changes (`git commit -m 'feat: add new feature'`)
5. Push to the branch (`git push origin feat/feature-branch`)
6. Open a Pull Request
