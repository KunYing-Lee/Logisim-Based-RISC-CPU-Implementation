# Logisim Based RISC CPU Implementation

This repository contains a Logisim-based implementation of a 32-bit single-cycle RISC CPU with no pipelining. The project uses fully open-source tools and is designed for educational and experimental purposes in computer architecture.

## 🚀 Project Overview

- **Architecture**: 32-bit RISC (inspired by RISC-V base instructions)
- **Cycle Model**: Single-cycle, no pipelining
- **Tool Used**: [Logisim Evolution](https://github.com/reds-heig/logisim-evolution) (open-source EDA software)
- **Design Paradigm**: Modular, component-based design

## ✅ Supported Instruction Types

- **R-type**: Arithmetic and logical operations
  - `ADD`, `SUB`, `AND`, `OR`, `XOR` ...
- **I-type**: Immediate arithmetic, load, and simple control
  - `ADDI`, `LW`, `JALR`, `SLLI`, etc.

(Instruction support may vary depending on your Logisim circuit file. See `instruction_set.md` for details.)

## 🧩 Implemented Components

- `ALU`: Arithmetic Logic Unit for computation
- `Decode`: Instruction decoder to parse and identify instruction fields
- `PC`: Program Counter module to track instruction addresses
- `RegFile`: 32-register file with two read ports and one write port

## 🛠 How to Run

1. Install **Logisim Evolution** (recommended version: ≥ 3.8.0).
2. Open `main.circ` with Logisim Evolution.

## 📜 License

This project is licensed under the MIT License. See [LICENSE](LICENSE) for details.

---

Feel free to fork, extend, and share!


