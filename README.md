#  Quantum Artificial Intelligence with Qiskit

This project aims at teaching you the fundamentals of Quantum Artificial Intelligence with Qiskit. It contains the example code of my  CRC Press/Taylor & Francis book, Quantum Artificial Intelligence, Andreas Wichert, 2024 

http://web.tecnico.ulisboa.pt/andreas.wichert/


Qiskit is an open-source software development kit (SDK) for working with quantum computers at the level of circuits and algorithms,  IBM Quantum,   https://quantum-computing.ibm.com/.

You can find installation instruction for qiskit at the site:
 https://qiskit.org/documentation/getting_started.html

The notebooks use some basic commands and should be compatible with different qiskit versions, expect the notebook 23_HybridApproaches-VariationalClassification and 17_QuantumKernels. 

The symbol (+) after the name, like  “17_QuantumKernels(+).ipynb” indicates that the algorithm was ported to the newest qiskit version  (now qiskit 0.45.0 and 0.46.0 with warnings).

i) Instead of .bind_parameters() .assign_parameters() is used, see 

17_QuantumKernels(+), 23_HybridApproaches-VariationalClassification(+)

ii) Instead of qiskit.algorithms qiskit_algorithms is used,see

23_HybridApproaches-VariationalClassification(+)

The symbol (-) after the name, like  “23_HybridApproaches-VariationalClassification(-).ipynb” indicates that the algorithm uses older qiskit version then in the book.

For qiskit version 1.0 go to the directory https://github.com/andrzejwichert/qai_1

There are following changes in qiskit 1.0:
qiskit.tools.jupyter are deprecated, instead of from qiskit import Aer use from qiskit_aer import Aer, instead or execute() use run() - when using run() decompose() the circuit, for quasi probabilities instead of plot_histogram(counts) use plot_distribution(counts), instead of of bind 
use assign.




If you have any questions, pls email me <andreas.wichert@tecnico.ulisboa.pt>
