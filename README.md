# Gitpod Eclipse

![Gitpod](https://img.shields.io/badge/Gitpod-FFAE33?style=flat-square&logo=gitpod&logoColor=black)
![Eclipse](https://img.shields.io/badge/Eclipse-2C2255?style=flat-square&logo=eclipse&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=flat-square)

> **Note:** This repository is a **fork** of [JesterOrNot/Gitpod-Eclipse](https://github.com/JesterOrNot/Gitpod-Eclipse).

A Gitpod-compatible configuration that runs the Eclipse IDE in a cloud-based development environment using VNC for graphical display, enabling full Eclipse functionality directly in the browser.

## Overview

This project provides a Dockerfile and Gitpod configuration to launch the Eclipse IDE installer within a Gitpod workspace. It leverages Gitpod's full VNC workspace image to render the Eclipse graphical interface in a browser-accessible environment, eliminating the need for local installation.

## Features

- **Browser-Based Eclipse** -- Run the full Eclipse IDE directly in your browser via VNC
- **Zero Local Setup** -- No need to install Eclipse or Java locally
- **Gitpod Integration** -- One-click launch from any GitHub repository
- **Pre-Configured Environment** -- Includes JRE and all required dependencies out of the box

## Prerequisites

- A [Gitpod](https://gitpod.io) account (free tier available)
- A modern web browser

## Getting Started

### Installation

No local installation is required. Simply open this repository in Gitpod.

[![Open in Gitpod](https://gitpod.io/button/open-in-gitpod.svg)](https://gitpod.io/#https://github.com/danielcregg/Gitpod-Eclipse)

### Usage

1. Click the **Open in Gitpod** button above
2. Wait for the Docker image to build (first launch may take a few minutes)
3. The Eclipse installer will launch automatically in the VNC viewer
4. Access the VNC display through port `6080` which opens in a browser tab

## Tech Stack

| Technology | Purpose |
|---|---|
| Docker | Custom workspace image with Eclipse dependencies |
| Gitpod | Cloud-based development environment |
| VNC | Remote graphical display for the Eclipse GUI |
| Java (JRE) | Runtime environment for Eclipse |

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
