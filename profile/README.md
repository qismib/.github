<div align="center">
<img src="https://avatars.githubusercontent.com/u/74980247" width="200">

# QISMIB: Quantum Information Science Milano-Bicocca

</div>

<p align="justify"> The primary mission of the Quantum Information Science Milano-Bicocca (QISMIB) initiative at the University of Milano-Bicocca is to introduce undergraduate and master students to the main foundational concepts of quantum computing and quantum technologies, as well as to provide them with the necessary theoretical and experimental tools to pursue research in this field. Additionally, the initiative aims to promote the advancement of quantum technologies through cutting-edge research projects, by fostering collaboration and knowledge exchange within the academic community. Through the implementation of cutting-edge research projects, QISMIB aims to train a new generation of highly qualified professionals with a strong background in quantum information science, who will be able to contribute to the advancement of this field and to the development of new quantum technologies. </p>    
  
<p align="justify"> If you are interested in quantum computing and quantum technologies and would like to carry on your thesis with our group please contact us at the email address: <a href="mailto:andrea.giachero@mib.infn.it">andrea.giachero at mib.infn.it</a>
  
<p align="justify"> The key tenets of the proposed thesis are centered around the cutting-edge fields of Quantum Simulation, Quantum Machine Learning, Quantum Key Distribution, and the Design and Simulation of qubits. These areas of study represent the vanguard of quantum technology research, offering a wealth of opportunities for exploration and innovation. From the use of quantum systems to simulate complex physical phenomena, to the application of machine learning algorithms to optimize quantum algorithms, to the development of secure communication protocols using quantum key distribution, and the design and simulation of qubits that are crucial building blocks of quantum computing, the proposed thesis delves into the very forefront of this rapidly evolving field.  </p>

<p align="justify"> The proposed thesis project will employ a variety of cutting-edge tools and technologies to develop and analyze the research. The primary programming language used will be Python, in conjunction with open-source frameworks such as Qitip, Qiskit, Pennylane, Qiskit-metal and others. These frameworks provide a comprehensive set of tools for the design, simulation, and execution of quantum algorithms, making them ideal for the proposed research. Additionally, the thesis will also make use of Julia, a modern programming language that, along with packages like Yao, offers a highly efficient and optimized quantum computing library for performing detailed simulations and analyses for the proposed research activities.</p>   

More details on the available activities are illustrated in the below sections. Past and current projects are list at [this link](https://github.com/orgs/qismib/repositories)   

QISMIB initiative is supported by 
* Bicocca Quantum Technologies Centre (BiQuTe): [biqute.unimib.it](https://biqute.unimib.it/)
* National Quantum Science and Technology Institute (NQSTI): [www.nqsti.it](https://www.nqsti.it)
* National Research Centre for High Performance Computing, Big Data and Quantum Computing (ISCS): [www.supercomputing-icsc.it](https://www.supercomputing-icsc.it)

---

<details>
<summary> <h2>Quantum Simulations</h3> </summary>

<p align="justify"> The field of Quantum Simulations is one of the few where it's clear that it will be possible to reach a useful quantum advantage. The main idea is that to simulate a quantum system you have to use another quantum system and any classical simulation is nothing more than an approximation. Moreover, having a quantum system in a quantum circuit form allows to straightforwardly analyze the effect of modifications of the system itself. The applications of Quantum Simlations vary in a large range of areas: from the study of <a href="https://pubmed.ncbi.nlm.nih.gov/34736057/">medical problems</a> to the simulation of <a href="https://arxiv.org/abs/1503.02312">Lattice Gauge Theories</a>, from researches in material science to drug discovery. Most of these works are conducted, for now, just from a theoretical point of view since they need computational resources not yet available, but different algorithms exist that can already be tested on existing devices: for example the Variational Quantum Eigensolver (<a href="https://arxiv.org/abs/2111.05176">VQE</a>) allows to simulate molecular systems in a compuational efficient way (something not possible with classical simulators). Research on this topic also focuses on near-term shrewdness to make the most of these algorithms even with Noisy intermediate-scale quantum devices: it is possible, for example, to reduce the number of needed qubits by exploiting symmetries in the system (<a href="https://arxiv.org/abs/1701.08213">tapering</a>).

</p>

</details>

---

<details>
<summary> <h2>Quantum Machine Learning</h3> </summary>

<p align="justify"> Quantum Machine Learning (QML) is a field that combines the principles of quantum mechanics and machine learning to create new algorithms and models that can solve problems in a more efficient and powerful way than classical methods. In QML, quantum processors are used as a computational resource to perform tasks such as feature extraction, dimensionality reduction, and supervided/unsupervides learning. This is achieved by encoding classical data into quantum states and applying quantum operations to manipulate and process the data. One example of a QML algorithm is the Quantum Support Vector Machine (<a href="https://arxiv.org/pdf/1307.0471.pdf">QSVM</a>), which uses quantum states to represent data points and quantum gates to perform linear algebra operations. This algorithm has been shown to have exceptional speedup over its classical counterpart for certain datasets. Another <a href="https://arxiv.org/pdf/1307.0471.pdf">version</a> of QSVM, suited for noisy intermediate-scale quantum devices, explores quantum data encoding in exponentially large Hilbert spaces to achieve higher accuracies than classical benchmark models. Another example is Quantum Principal Component Analysis (<a href="https://www.nature.com/articles/nphys3029">QPCA</a>), which uses quantum algorithms to extract the principal components of a dataset in exponentially fewer operations than the classical method. Other examples involve Quantum Key Means Clustering and Quantum Neural Networks. QML is a young and rapidly growing field, with many open problems and opportunities for research, potentially driving data analysis in many fields such as physics, chemistry, finance and cryptography. Our activities on QML focus on the use of the <a href="https://qiskit.org/">Qiskit</a> package, developed by IBM, and the <a href="https://quantum-computing.ibm.com/?needs_refill=true">IBM Quantum</a> cloud access to real state-of-the-art Quantum Computers for testing our algorithms.


</p>

</details>

---

<details>
<summary> <h2>Quantum Key Distribution</h3> </summary>

<p align="justify"> Quantum key distribution (QKD) is a method for secure communication that uses the principles of quantum mechanics to establish a secret key between two parties. This key can then be used to encrypt and decrypt messages, ensuring that only the intended recipients can read them. The BB84 and E91 protocols are well-established examples of QKD protocols that have been proposed and implemented, while the Continuous-variable (CV-QKD) and Measurement-Device-Independent (CV-MDI) protocols are relatively newer but promising candidates that offer immunity to side-channel attacks. The security and performance of these protocols can be evaluated by analyzing the different types of attacks that can be performed by an eavesdropper. To further enhance the evaluation, numerical simulations can be conducted, taking into account different scenarios and noise models. Additionally, exploring novel techniques for error correction and the use of novel quantum states can be considered as potential avenues for future research.
</p>

</details>

---

<details>
<summary> <h2>Design and Simulation of qubits</h3> </summary>

<p align="justify"> One of the main problems that the quantum research community is facing at the moment is "how do we actually build an error resistant, multi-purpose quantum computer?". One way to do that is using superconducting qubits. 
Our group is working on superconducting qubit design for multiple applications: quantum sensors, quantum computers and other devices. The main challenges will be to improve current designs and find new ones in order to build better qubits for all applications. 
The qubit design process goes through different steps: ideation and parameter definition, design, electromagnetic simulation and quantum parameters extraction.
The first phase can be faced by simulating quantum systems using libraries such as <a href="https://qutip.org/">Qutip</a> and <a href="https://scqubits.readthedocs.io/en/latest/">Scqubits</a> . These libraries offer a simple framework to simulate numerically qubit and other quantum systems. In this way we can define our goals for the final system to be designed. 
Once our objectives are set, we design qubits using <a href="https://qiskit.org/metal/">Qiskit-Metal</a> (IBM) and the Qubit Simulation Module (QSM, developed at NIST). To evaluate the qubit parameters from the design we use different simulations: the Energy Participation Ratio (<a href="https://www.nature.com/articles/s41534-021-00461-8">EPR</a>) and the Lumped Oscillator Model (<a href="https://arxiv.org/abs/2103.10344">LOM</a>). Both these analyses exploits ANSYS (HFSS and Q3D) to perform electromagnetic simulations. The results of the EM software are then used to quantize the system and extract all the interesting parameters. The design will be then modified until these parameters match the goals we set. With this workflow we tune each device to better suit its specific application. </p>

</details>

---

<details>
<summary> <h2>Pubblications</h3> </summary>

* "**_Local fermion-to-qudit mappings_**",  
  R. Carobene, S. Barison, A. Giachero, and J. Nys, _in preparation_

* "**_Enhanced feature encoding and classification on distributed quantum hardware_**",  
  R. Moretti, A. Giachero, V. Radescu, M. Grossi,  <a href="https://arxiv.org/abs/2412.01664"> `2412.01664 [quant-ph]`  </a>

* "**_Assessment of few-hits machine learning classification algorithms for low energy physics in liquid argon detectors_**",  
  M. Biassoni _et al._, <a href="https://doi.org/10.1140/epjp/s13360-024-05287-9"> Eur. Phys. J. Plus 139 (2024) 8, 723 </a>,   <a href="https://arxiv.org/abs/2305.09744"> `2305.09744 [physics.ins-det]`  </a>

* "**_Sequence of penalties method to study excited states using VQE_**",  
  R. Carobene, S. Barison, A. Giachero,  <a href="https://doi.org/10.1088/2058-9565/acd1a9"> Quantum Sci. Technol. 8 (2023) 035014, </a>, <a href="https://arxiv.org/abs/2304.05262"> `2304.05262 [quant-ph]`  </a>
</details>

---

<details>
<summary> <h2>Members</h3> </summary>

### Internal collaborators
**Prof. Andrea Giachero - Associate Professor - Coordinator**  
*University of Milano-Bicocca, Milano, Italy*  
*INFN Unit of Milano-Bicocca, Milano, Italy*  
[andrea.giachero at mib.infn.it](mailto:andrea.giachero@mib.infn.it)  

**Prof. Angelo Nucciotti - Associate Professor - Director of the BiQuTe centre**  
*University of Milano-Bicocca, Milano, Italy*  
*INFN Unit of Milano-Bicocca, Milano, Italy*  
[angelo.nucciotti at mib.infn.it](mailto:angelo.nucciotti@mib.infn.it)  

**Prof. Pietro Govoni - Associate Professor**    
*University of Milano-Bicocca, Milano, Italy*    
*INFN Unit of Milano-Bicocca, Milano, Italy*    
[pietro.govoni at unimib.it](mailto:pietro.govoni@unimib.it)  


**Danilo Labranca - Ph.D. Student**  
*University of Milano-Bicocca, Milano, Italy*    
*INFN Unit of Milano-Bicocca, Milano, Italy*  
[danilo.labranca at mib.infn.it](mailto:danilo.labranca@mib.infn.it)

**Roberto Moretti - Ph.D. Student**    
*University of Milano-Bicocca, Milano, Italy*  
*INFN Unit of Milano-Bicocca, Milano, Italy*  
[roberto.moretti at mib.infn.it](mailto:roberto.moretti@mib.infn.it)

**Rodolfo Carobene - Ph.D. Student**   
*University of Milano-Bicocca, Milano, Italy*    
*INFN Unit of Milano-Bicocca, Milano, Italy*  
[rodolfo.carobene at mib.infn.it](mailto:rodolfo.carobene@mib.infn.it)

**Pietro Campana - Ph.D. Student**   
*University of Milano-Bicocca, Milano, Italy*    
*INFN Unit of Milano-Bicocca, Milano, Italy*  
[pietro.campana at mib.infn.it](mailto:pietro.campana@mib.infn.it)


### External collaborators
**Leonardo Banchi**  
*University of Florence*  
*INFN Unit of Florence*     
[leonardo.banchi at unifi.it](mailto:leonardo.banchi@unifi.it)

**Stefano Barison**  
*École polytechnique fédérale de Lausanne*  
[stefano.barison at epfl.ch](mailto:stefano.barison@epfl.ch)

**Stefano Carrazza**   
*University of Milano, Milano, Italy*      
*INFN Unit of Milano, Milano, Italy*  
*CERN Theory Group*  
[stefano.carrazza at unimi.it](mailto:stefano.carrazza@unimi.it)


**Michele Grossi**  
*CERN Quantum Technology Initiative*  
*CERN IT innovation*  
[michele.grossi at cern.ch](mailto:michele.grossi@cern.ch)

</details>

---


                                                                                                                                              
