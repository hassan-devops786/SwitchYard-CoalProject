<h1 align="center">SwichYard</h1>
<p align="center">
  A game written entirely in assembly language.
</p>
<p align="center">
  <img src="docs/screenshot.png" alt="SwichYard gameplay screenshot" width="500">
</p>

![Language](https://img.shields.io/badge/language-x86%20Assembly-blue)
![Platform](https://img.shields.io/badge/platform-DOS%20%7C%20Linux%20%7C%20Windows-lightgrey)
![License](https://img.shields.io/badge/license-MIT-green)
---
## Table of Contents
- [About](#about)
- [Features](#features)
- [Requirements](#requirements)
- [Build and Run](#build-and-run)
- [How to Play](#how-to-play)
- [Controls](#controls)
- [Project Structure](#project-structure)
- [How It Works](#how-it-works)
- [Roadmap](#roadmap)
- [Credits](#credits)
  
## About
SwichYard is a Asssembly 8088 Console Based Gamepool that presents a yard of track of Railway with 2 Entrance and 4 Stations. The yard is managed by 4 Switches that maps the whole place and maintains the  Movements of tain spawned autmatically.
**Goal of the game:** A 2D Console Based GAme Written in Assembly aims to efficiently Deliver the concepts and core understandings of Assembly Language and Computer Organization including Interrupts, Video Memory,subroutines etc.

## Features
- Feature one (e.g. keyboard-driven gameplay)
- Feature two (e.g. text-mode or VGA graphics)
- Feature three (e.g. score tracking)
- Time Tracking (e.g. Estimate Time Elapsed)
- Written with no external libraries
  
## Requirements
| Tool         | Version | Purpose                   |
|--------------|---------|---------------------------|
| NASM         | 2.15+   | Assembler                 |
| DOSBox       | 0.74+   | Emulator (if DOS target)  |
## How to Play
## Controls
| Key          | Action        |
|--------------|---------------|
| Numeric Keys | Move          |
| Esc          | Termainte     |
| 1,2          | Mode Selection|
## Project Structure

## How It Works
Brief technical notes for readers curious about the code:
- **Architecture:** e.g. x86-64, 16-bit real mode, ARM
- **Game loop:** input → update → render
- **Rendering:** e.g. BIOS interrupt `INT 10h`, direct video memory at `0xB8000`
- **Input:** e.g. `INT 16h`
- **Memory layout:** where game state, the board, and the stack live
## Roadmap
 - [X] Basic game loop
 - [X] Keyboard input
 - [X] Score System
Please comment your assembly generously.
## Credits
- Author: [Your Name](https://github.com/yourname)
## Team
<pre>
Zain Ul Abidin   25L-3102
Hassan Ali       25L-3086</pre>
