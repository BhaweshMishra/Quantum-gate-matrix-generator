
# Quantum-gate-matrix-generator

This project uses a truth table to generate the gate matrix for a quantum circuit. The matrix generated can be used in various quantum computing libraries such as Cirq and Qiskit. The matrix can be used to make quantum gates as it will be easier for simulating circuits rather than using multiple universal gates.

## Quantum Gates
A quantum logic gate is a basic quantum circuit operating on a small number of qubits. Quantum logic gates are reversible. The matrix of the quantum gate needs to be unitary. This implies that the truth table must have unique outputs for each input value (i.e if the truth table is represented as a function, it will be a one-one function).

## Non-Universal Quantum Gate
This is a representation of a general quantum gate. The extra qubits help make the gate reversible. In this case, even though the initial truth table is not a one-one function, the gate matrix is reversible by due to the extra qubits.

![image](https://user-images.githubusercontent.com/77975276/228019710-f5151f90-cbca-4913-b1b5-82ab471f4474.png)


&nbsp; 
&nbsp; 
&nbsp;  
&nbsp; 



This Jupyter notebook shows the implementation of the XOR gate.
This is the general quantum circuit for the XOR gate:
![image](https://user-images.githubusercontent.com/77975276/228023303-7034935c-3972-419e-8f1f-0b7096d9c346.png)

The program outputs the generated quantum gate matrix for the xor gate as shown above (3 inputs and outputs).





## Installation

The Python program is written in a Jupyter Notebook for easier and cell wise implementation.
The program requires the NumPy module to run.

Incase Numpy module is not on your device, install it using

```bash
pip install numpy
```
Download the TT_to_QGM.ipynb file and run it.


    
## About the file
Download the Jupyter Notebook. The step wise working of the program is written in the comments.
