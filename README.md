# Triple-Output DC Power Supply

## Description
This project involves the design of a DC power supply featuring three outputs:

- **Output 1**: Adjustable 0-12V (max 2A)
- **Output 2**: Adjustable 0-(-12)V (max 2A)
- **Output 3**: Constant 5V (max 2A)

## Features
- **Three output channels**: 0-12V, 0-(-12)V, and a constant 5V output.
- **Adjustable voltage**: Both positive and negative voltage outputs can be adjusted to meet specific requirements.
- **Current limiting**: Each output can handle up to 2A, providing sufficient power for most low to medium current applications.
- **LTspice Simulation**: The design includes LTspice files for circuit simulation to verify performance before physical implementation.

## Circuit Design
- **Output 1 (0-12V)**: Powered by an adjustable regulator (e.g., LM317).
- **Output 2 (0-(-12)V)**: Powered by an adjustable negative regulator (e.g., LM337).
- **Output 3 (5V)**: A fixed voltage regulator for the constant 5V output.

## LTspice Files
This project includes LTspice files for simulating the power supply design. To ensure proper simulation, you will need to download the following component libraries:

- **LM317 Library**: Required for the positive adjustable regulator.
- **LM337 Library**: Required for the negative adjustable regulator.

I included the libraries for the parts I used. You can also download these libraries from the official manufacturer’s website or from trusted online sources.

- [LM317 Datasheet](https://www.ti.com/product/LM317)
- [LM337 Datasheet](https://www.ti.com/product/LM337)

## Requirements
- LTspice software (for simulation)
- Components for physical implementation (LM317, LM337, resistors, capacitors, etc.)

## License
This project is open-source and licensed under the [MIT License](LICENSE).

## Acknowledgments
- Special thanks to the creators of LTspice for their powerful simulation tools.
- Thank you to Texas Instruments for providing the LM317 and LM337 regulators, which are essential to this project.

Feel free to fork, modify, and improve upon this design!
