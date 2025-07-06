# 🧠 8-bit CPU in Logisim Evolution

This is my personal project to design a simple 8-bit CPU from scratch using [Logisim Evolution](https://github.com/logisim-evolution/logisim-evolution). The goal is to deeply understand CPU architecture, ALU design, registers, control logic, and instruction execution at the hardware level.

---

## 🔧 Features (so far)

- 🛠️ **In-progress 8-bit ALU** (partially wired)
  - [x] Designed **Adder/Subtractor**
  - [x] Designed **Logic Unit** (AND, OR, NOT)
  - [ ] Not fully functional yet (debugging stage)
- ✅ Basic **gates** and wiring
- 🧪 Initial **register** experiments
- 🔜 Program Counter, Instruction Decoder
- 🔜 RAM / ROM integration
- 🔜 Control Unit & microprogramming

---

## 🧪 Project Goals

- Build a fully working 8-bit CPU
- Create a custom instruction set (ISA)
- Run simple programs directly in hardware (or simulated)
- Learn low-level digital logic and CPU architecture
- Eventually write a small assembler and emulator

---

## 🛠 Tools Used

- [Logisim Evolution](https://github.com/logisim-evolution/logisim-evolution)
- Git & GitHub for version control
- Linux (Debian/Arch) as development environment

---

## 🚧 Project Status

Currently working on the ALU.

- ADD/SUB and logic gates are designed
- Wiring, flags (Zero, Carry, Overflow) and selector logic are **work-in-progress**
- Next steps:
  - Debug ALU logic and control signals
  - Connect to register file and test with example values
  - Design instruction fetch-execute loop

---

## 📚 Inspirations

- Ben Eater’s 8-bit CPU (breadboard)
- Code by Charles Petzold 📘 – A foundational book explaining how computers really work from the ground up
- Operating system internals & bootloaders
- My passion for low-level computing, CPU design, and security

---

## 🔗 License

MIT License © 2025 [Matúš Krivánik](https://github.com/cimbobimboontop)
