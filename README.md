# Python-Numerical-Literal-Checker

This project implements a Python program that recognizes valid Python literals, including decimal, octal, hexadecimal integers, and floating-point numbers. The program takes user input as a string and determines whether it is a valid literal based on the lexical definitions specified in the Python language reference.

## Features

- Recognizes decimal, octal, and hexadecimal integer literals
- Recognizes floating-point literals
- Supports underscores for digit grouping in integer and floating-point literals
- Provides detailed explanations and NFA (Nondeterministic Finite Automaton) designs for each literal type

## Getting Started

To use the Python Literal Recognizer, follow these steps:

1. Clone the repository: 
   git clone https://github.com/your-username/python-literal-recognizer.git
2. Navigate to the project directory:
   cd python-literal-recognizer
3. Run the Python script:
   python literal_recognizer.py
5. Enter a string when prompted to check if it is a valid Python literal.

## File Structure

- `literal_recognizer.py`: The main Python script that contains the functions for recognizing Python literals.
- `README.md`: This file, providing an overview and instructions for the project.
- `nfa_designs/`: Directory containing the NFA designs for each literal type in JFLAP format (`.jff`) and image format (`.jpg`).

## NFA Designs

The project includes NFA designs for each literal type, created using the JFLAP tool. The NFA designs visually represent the lexical definitions and the structure of valid literals. You can find the NFA designs in the `nfa_designs/` directory.

- `integer_literal_nfa.jff`: NFA design for integer literals (decimal, octal, hexadecimal) in JFLAP format.
- `integer_literal_nfa.jpg`: Image representation of the integer literal NFA design.
- `floating_point_literal_nfa.jff`: NFA design for floating-point literals in JFLAP format.
- `floating_point_literal_nfa.jpg`: Image representation of the floating-point literal NFA design.

## Contributing

Contributions to the Python Literal Recognizer project are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request on the project's GitHub repository.

## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgements

- The Python language reference for providing the lexical definitions of literals.
- The JFLAP tool for creating visual representations of NFA designs.
