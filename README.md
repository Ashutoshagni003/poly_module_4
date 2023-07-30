# poly_module_4

# Readme for Pragma Circom Multiplication Check Circuit

This repository contains the code for a circuit template implemented in Pragma Circom 2.0.0. The circuit checks whether the value of `c` is the result of the multiplication of `a` and `b`. The circuit consists of basic logic gates like AND, NOT, and OR, and is built using custom templates.

## Requirements

To use this code, you will need the following:

1. Pragma Circom 2.0.0: Ensure you have the latest version of Pragma Circom installed on your system.

## Circuit Description

The circuit is designed to check if the value of `c` is the product of `a` and `b`. The main template `Ashutosh` implements this functionality using the following steps:

1. **AND Gate**: The input signals `a` and `b` are connected to an AND gate, which calculates the logical AND between them. The output is stored in a signal `x`.

2. **NOT Gate**: The signal `b` is connected to a NOT gate, which computes the logical NOT of `b`. The output is stored in a signal `y`.

3. **OR Gate**: The signals `x` and `y` are connected to an OR gate, which performs a logical OR operation between them. The final output of the circuit is stored in a signal `q`.

## Templates

The circuit uses three custom templates for the basic logic gates:

1. **AND**: This template defines an AND gate that multiplies its two input signals `a` and `b` and outputs the result in `out`.

2. **NOT**: This template defines a NOT gate that computes the logical NOT of its input signal `in` and outputs the result in `out`.

3. **OR**: This template defines an OR gate that performs a logical OR operation between its input signals `a` and `b` and outputs the result in `out`.

## Usage

1. Make sure you have Pragma Circom 2.0.0 installed on your system.
2. 
3. Replace `/*...*/` sections with your desired input and output signal names and connections.

4. Compile the circuit using Pragma Circom to generate the circuit file.

5. Depending on your use case, you can now use the generated circuit file in other projects or systems that support Pragma Circom circuits.

## Contribution

Contributions to this repository are welcome. If you find any issues or want to enhance the circuit, feel free to create a pull request.
