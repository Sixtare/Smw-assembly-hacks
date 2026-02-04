# ASM

This directory contains **Assembly code for Super Mario World (SMW)**, targeting the **SNES 65c816 CPU**.  
It is part of the **Smw-assembly-hacks** repository and serves as a collection of low-level hacks, routines, and experiments for SMW ROM hacking.

The goal is to keep the ASM code organized, reusable, and easy to understand, both for practical use in ROM hacks and as learning material for people interested in SMW Assembly.

## Contents

Inside this folder you may find:

- `.asm` files with gameplay or engine modifications  
- Custom routines and reusable code snippets  
- Helper macros  
- Experimental or learning-focused ASM code  

The exact contents may grow over time as new hacks and ideas are added.

## About SMW Assembly

Assembly programming for Super Mario World allows direct interaction with the game’s internal logic, enabling modifications that are not possible using level editors alone, such as Lunar Magic.

Typical use cases include:

- Adding new gameplay mechanics  
- Modifying player or enemy behavior  
- Creating custom effects or logic  
- Overriding or extending the original game engine  

All code here is written for the **SNES 65c816 architecture**.

## Requirements

To work with these files, you will usually need:

- A SNES-compatible assembler, such as **Asar**  
- A clean Super Mario World ROM (typically USA version)  
- Basic knowledge of 65c816 Assembly, or willingness to learn  

## Basic Usage (Example)

1. Clone this repository.  
2. Place a clean SMW ROM in your working directory.  
3. Use **Asar** or **UberASM** to apply the `.asm` files as patches or integrate them into your project.  
4. Test the resulting ROM in a SNES emulator.
