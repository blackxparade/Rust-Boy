# Rust Boy [![Build Status](https://travis-ci.org/blackxparade/Rust-Boy.svg?branch=master)](https://travis-ci.org/blackxparade/Rust-Boy)

![Current stage](/Emulator/doc/logo.gif)

This is project **Rust Boy**, which is my thesis for the master's degree.

**Rust Boy** is a Nintendo Game Boy emulator, which will be cycle-accurate in theory. This repository will serve as a source backup and version contolling for the project, and when the time comes, the writing part of the essay will be uploaded here - as is progresses - too.

*The project's deadline is somewhere in February, 2018.*

In the initial commit, I already made the project structure (which may be change in the future - I'm not sure yet) and some opcodes. On the bottom of this page there is a TODO part, which indicates the current tasks and/or problems, future updates.

## Current TODOs

- [ ] Code cleaning.
- [x] ~~Implement and test the CPU instructions.~~
  - [x] ~~**CRITICAL**: Correct the Stack implementation.~~
  - [x] Implementation.
- [x] ~~Initial commit.~~
- [x] ~~Combine the emulator with the debugger/tester I wrote for debugging the instructions.~~
  - [x] Collecting data from the CPU side.
  - [x] Recieve and store data on the debugger/tester side.
  - [x] Testing.
  - [x] Keypress-to-stop-CPU mechanism so I can check out the listed instructions.
- [x] ~~Check _every_ flag set / unset~~
- [x] ~~Implement the rendering.~~
  - [x] Tile rendering.
  - [x] Sprite rendering.
- [x] ~~Implement the CPU timing / interrupts.~~
- [x] ~~Research and implement the GPU timing.~~
