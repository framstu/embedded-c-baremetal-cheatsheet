
# Embedded C – Bare‑Metal Cheat Sheet

This cheat sheet was created as a personal reference while learning embedded systems programming.
I’m not a professional firmware engineer — just an enthusiast collecting the explanations and examples I wish I had when I started.
It currently focuses on core bare‑metal concepts, and may later be expanded with topics such as interrupts (IRQ).

Note: GitHub may not preview these PDF files, but they can be downloaded and viewed normally.

## Overview
This document summarizes some of the most commonly used patterns, keywords, and techniques in bare‑metal Embedded C.
It is designed to be quick to read, easy to navigate, and practical for everyday development.

## What’s Included
 - Commonly used C headers for embedded systems
 - Fixed‑width integer types and why they matter
 - Bitwise operators and helper macros
 - Register access and bit manipulation
 - Structs, enums, and pointers for hardware interaction
 - Super‑loop architecture
 - Memory‑mapped I/O and register mapping

## Purpose
The goal of this cheat sheet is to provide a fast, reliable reference when writing firmware without an operating system.

It helps reinforce best practices for:
 - Writing predictable, deterministic code
 - Interacting with hardware registers safely
 - Organizing embedded applications
 - Avoiding common pitfalls in low‑level C

## Typical Use Cases
 - Configuring pins
 - Reading sensors and peripherals
 - Implementing state machines
 - Managing timers and interrupts
 - Building simple real‑time loops

## Usage
Feel free to use, modify, or extend this cheat sheet in your own projects.
It is intentionally minimal so you can adapt it to your specific microcontroller or coding style.

## License
MIT; This project is free to use and distribute.

13 June 2026, Matias Back
