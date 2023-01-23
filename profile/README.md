<div align="center">
<img src="https://avatars.githubusercontent.com/u/74980247?s=400&u=a88078be8d5dd965e43c0e9b4acaddccae1ad431&v=4" width="200">

# QISMIB: Quatum Information Science Milano-Bicocca

</div>

The primary mission of the Quantum Information Science Milano-Bicocca (QISMIB) initiative at the University of Milano-Bicocca is to introduce undergraduate and master students to the main foundational concepts of quantum computing and quantum technologies.  


## Quantum Simulation

## Quantum Machine Learning

## Quantum Key Distribution

## Design and Simulation of qubits
One of the main problems that the quantum research community is facing at the moment is "how do we actually build an error resistant, multi-purpose quantum computer?". One way to do that is using superconducting qubits. 
Our group is working on superconducting qubit design for multiple applications: quantum sensors, quantum computers and other devices. The main challenges will be to improve current designs and find new ones in order to build better qubits for all applications. 
The qubit design process goes through different steps: ideation and parameter definition, design, electromagnetic simulation and quantum parameters extraction.
The first phase can be faced by simulating quantum systems using libraries such as Qutip ([https://qutip.org/](https://qutip.org/)) and Scqubits([https://scqubits.readthedocs.io/en/latest/](https://scqubits.readthedocs.io/en/latest/)). These libraries offer a simple framework to simulate numerically qubit and other quantum systems. In this way we can define our goals for the final system to be designed. 
Once our objectives are set, we design qubits using Qiskit-Metal (IBM, [https://qiskit.org/metal/](https://qiskit.org/metal/)) and the Qubit Simulation Module (QSM, developed at NIST). To evaluate the qubit parameters from the design we use different simulations: the Energy Participation Ratio (EPR, [[1]](https://www.nature.com/articles/s41534-021-00461-8)) and the Lumped Oscillator Model (LOM [[2]](https://arxiv.org/abs/2103.10344)). Both these analysis exploits ANSYS (HFSS and Q3D) to perform electromagnetic simulations. The results of the EM software are then used to quantize the system and extract all the interesting parameters. The design will be then modified until these parameters match the goals we set. With this workflow we tune each device to better suit its specific application.


### Members
**Prof. Andrea Giachero - Coordinator**  
*University of Milano-Bicocca, Milano, Italy*  
*INFN Unit of Milano-Bicocca, Milano, Italy*  
[andrea.giachero at mib.infn.it](mailto:andrea.giachero@mib.infn.it)

**Danilo Labranca - Ph.D. Student**  
*University of Milano-Bicocca, Milano, Italy*    
*INFN Unit of Milano-Bicocca, Milano, Italy*  
[danilo.labranca at mib.infn.it](mailto:danilo.labranca@mib.infn.it)

**Roberto Moretti - Ph.D. Student**    
*University of Milano-Bicocca, Milano, Italy*  
*INFN Unit of Milano-Bicocca, Milano, Italy*  
[roberto.moretti at mib.infn.it](mailto:roberto.moretti@mib.infn.it)

**Rodolfo Carobene - M.Sc. Student**   
*University of Milano-Bicocca, Milano, Italy*    
*INFN Unit of Milano-Bicocca, Milano, Italy*  
[rodolfo.carobene at mib.infn.it](mailto:rodolfo.carobene@mib.infn.it)

 

