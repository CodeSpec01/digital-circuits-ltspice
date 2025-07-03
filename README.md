# Digital Circuits Simulated in LTSpice

This project contains a collection of digital circuit simulations created and tested using LTSpice. Each schematic demonstrates the design and operation of fundamental digital logic circuits, useful for learning, teaching, or reference in digital electronics.

## Circuits Included

- **CMOS Gates**: Basic CMOS implementations of NOT, NAND, and NOR gates.
- **Encoder Decoder**: Priority encoder and decoder circuits.
- **Full Adder**: A 1-bit full adder circuit using CMOS logic.
- **Mux DeMux**: 2x1 multiplexer and 1x2 demultiplexer circuits.
- **Basic Memory Device**: SR latch and SR flip-flop (with enable) memory elements.

## File List

#### Schematics -

- `CMOS Gates.asc` — CMOS logic gates (NOT, NAND, NOR)
- `Encoder Decoder.asc` — Priority encoder and decoder
- `Full Adder.asc` — 1-bit full adder
- `Mux DeMux.asc` — Multiplexer and demultiplexer
- `Basic Memory Device.asc` — SR latch and SR flip-flop

#### Outputs -

- `CMOS Gates.jpg` — CMOS logic gates (NOT, NAND, NOR)
- `Decoder.jpg` — 2x4 Decoder
- `Full Adder.jpg` — 1-bit full adder
- `Multiplexer.jpg` — 2x1 Multiplexer
- `Demultiplexer.jpg` — 1x2 Demultiplexer
- `SR Latch.jpg` — SR latch
- `SR Flip Flop.jpg` — SR flip-flop

Example - 


![Output1](https://github.com/user-attachments/assets/eecf8072-0c44-4340-8b9d-d507027abd24)
![Output2](https://github.com/user-attachments/assets/9425cc0d-c99f-4c5d-b65c-1adba089c9f9)


## How to Use

1. **Open LTSpice** (IV, XVII, or later).
2. **Open any `.asc` file** from this repository.
3. **Run the simulation** to observe the circuit's behavior. [Transient Analysis has been configured already]
4. **Modify or extend** the circuits as needed for your learning or project requirements.

## Notes

- All circuits use standard CMOS logic (BSS84 for PMOS, BSP89 for NMOS).
- Voltage sources are configured for typical digital logic levels (0V/5V) and include pulse sources for clock and input signals.
- Each schematic includes comments and labels for clarity.

## License

This project is provided for educational and non-commercial use. Feel free to use, modify, and share with attribution.
