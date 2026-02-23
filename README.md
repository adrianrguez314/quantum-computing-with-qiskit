# Quantum Computing Algorithms: Theoretical Foundations and Qiskit Implementations

This repository serves as a comprehensive collection of Jupyter Notebooks dedicated to the implementation and analysis of quantum algorithms. The project encompasses a selection of algorithms developed during the introductory quantum computing curriculum at the **University of La Laguna (ULL)**, supplemented by independent research and advanced algorithmic practices.

The repository is under active development, with additional implementations and theoretical modules being integrated periodically.

---

## Methodology and Structure

Each notebook is engineered to function as both a technical implementation and a theoretical reference. The content is structured into three primary pillars:

* **Mathematical Formalism**: A rigorous explanation of the quantum mechanical principles and the computational logic underlying the algorithm.
* **Algorithmic Synthesis**: A step-by-step guide on translating theoretical gates into functional circuits using the Qiskit framework.
* **Data Visualization and Analysis**: Execution of the algorithm on simulators with subsequent analysis of probability distributions and state vectors.

---

## Current Repository Status

The following table details the algorithms currently available in the repository:

| File Name | Algorithm | Description |
| :--- | :--- | :--- |
| `01_Bernstein_Vazirani.ipynb` | **Bernstein-Vazirani** | Determination of a hidden bitstring in a single query. Includes full theoretical derivation. |
| `02_Deutsch_Jozsa.ipynb` | **Deutsch-Jozsa** | Evaluation of function properties (constant vs. balanced). Features updated technical explanations. |
| `03_quantum_teleportation.ipynb` | **Quantum Teleportation** | Implementation of the protocol for state transfer via entanglement and classical communication. |
| `04_Shors_algorithms.ipynb` | Shor’s Algorithm | Determination of the factorization of N. In this case, N = 15. |

---

## Technical Stack and Dependencies

The implementations are developed using the latest stable releases of the following libraries to ensure compatibility and performance:

### Quantum Frameworks
* **Qiskit (IBM)**: Main software development kit for quantum circuit design.
* **Aer (IBM)**: High-performance provider for simulating quantum computing elements.

### Mathematical and Data Tools
* **NumPy**: Essential library for linear algebra and multi-dimensional array processing.
* **Pandas**: Utilized for the structured management of measurement results and data frame representation to enhance readability.
* **Matplotlib**: Employed for the high-fidelity rendering of quantum circuits and histogram analysis.

---

## References and Bibliography

The theoretical and technical development of these notebooks is supported by the following academic resources:

### Institutional and Course Materials
* **University of La Laguna (ULL)**: Lecture notes and official documentation from the *Microcredencial en Introducción a la Computación Cuántica* (1st Edition, 2026).
* **University of La Laguna (ULL)**: Lecture notes and official documentation from the *Microcredencial en Criptografía e Información Cuántica* (3th Edition, 2026).
* **IBM Quantum Learning**: Official Qiskit documentation and IBM introductory quantum computing courses.

### Academic Textbooks
* **Cohen-Tannoudji, C., Diu, B., & Laloë, F.**: *Quantum Mechanics*. Used for the rigorous derivation of quantum states, operators, and foundational postulates.
* **Lay, D. C., Lay, S. R., & McDonald, J. J.**: *Linear Algebra and Its Applications*. Reference for the vector space formalism, unitary transformations, and spectral theory utilized throughout the implementations.

---

## Intellectual Property and Usage

The contents of this repository are provided as an open-access resource. Users are permitted to download, execute, and modify the source code for educational, research, or developmental purposes. No prior authorization is required for the academic use of these materials.
