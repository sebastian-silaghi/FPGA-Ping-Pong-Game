# FPGA-Ping-Pong-Game

This project implements a simple Ping Pong game on an FPGA using the Basys 3 Artix-7 development board.  
The design was developed as part of the **Digital Integrated Circuits** laboratory project.

The game is displayed using the seven-segment display and board LED`s and controlled using the buttons on the Basys 3 board.

---

## Hardware

- Basys 3 Artix-7 FPGA Board
- Seven-segment display
- Push Buttons (player control)

---

## Tools

- Xilinx Vivado Design Suite
- Hardware Description Language: VHDL
- FPGA: Artix-7 (XC7A35T)

---

## Features

- Player paddle control
- Ball movement logic using board LED`s
- Collision detection
- Score system
- Real-time game implemented entirely in hardware

---

## How It Works

The game logic is implemented as a digital system inside the FPGA:

1. The **game engine** updates the ball and paddle positions.
2. **Collision logic** detects wall and paddle hits.
3. The **Score system** logic updates automatically and can also be reset.

All modules run synchronously using the FPGA clock.

---

## Running the Project

1. Open the project in **Vivado**.
2. Synthesize and implement the design.
3. Program the **Basys 3 FPGA board**.
4. Use the board buttons to control the paddle.


