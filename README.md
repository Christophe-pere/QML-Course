# QML-Course
I developed a course on quantum machine learning for École de Technologie Supérieure (Montréal, QC, CA) with support from [Catalina Albornoz Anzola](https://www.linkedin.com/in/catalinaalbornoz/). She is the Quantum Community Manager at [Xanadu](https://xanadu.ai). 

The course is given to students at the end of their bachelor's degree or the beginning of their Master's degree. Prerequisites in linear algebra and introduction to quantum computing or quantum information are needed. The course gave an overview of the field in 2024 and the prerequisites for students interested in developing QML algorithms or applying them to real-world scenarios. 

The course is in French, so the slides are in French but can be translated. [PennyLane](https://pennylane.ai) is the primary library during the course. 

Winter session January to May 2024

## Resources 
Three books are used as primary resources for this first edition of the course (pre-alpha 2024). 
- [Schuld M. & Petruccione F., 2021, Machine Learning with quantum computers, 2nd edition](https://link.springer.com/book/10.1007/978-3-030-83098-4)
- [Hidary J. D., 2021, Quantum Computing: An Applied Approach, 2nd edition](https://link.springer.com/book/10.1007/978-3-030-83274-2)
- [Combarro E. F. & Gonzàlez-Castillo, 2023, A practical guide to quantum machine learning and Quantum optimization](https://www.packtpub.com/product/a-practical-guide-to-quantum-machine-learning-and-quantum-optimization/9781804613832)

Additional resource: [The Codebook by Xanadu](https://codebook.xanadu.ai/). The introduction is available in French. 

Research papers and YouTube videos used for the courses are cited where needed and placed in the References slides at the end of each lecture. 

## Content 

> Not all lectures are yet available. Lecture 6 will be given on February 8th and uploaded. Each lecture will be uploaded each week. 

- [Lecture 1: Introduction](https://github.com/Christophe-pere/QML-Course/blob/main/Lecture%201/Lecture%201.pdf)
  * Course content
  * Exam modalities
  * Introduction to QML
  * Talk by Catalina Albornoz 
- [Lecture 2: Classical Machine Learning](https://github.com/Christophe-pere/QML-Course/blob/main/Lecture%202/Lecture%202.pdf)
  * AI definition
  * Problem examples
  * Learning
  * The three main tools for ML
  * Risk minimization in supervised ML
  * Learning process for unsupervised techniques
  * ML models 
- [Lecture 3: Introduction to PennyLane](https://github.com/Christophe-pere/QML-Course/blob/main/Lecture%203/Lecture%203.pdf)
  * Introduction to PennyLane
  * 1 qubit gates
  * 2 qubit gates
  * Challenges
  * Simple classifier
  * How to read a paper 
- [Lecture 4: Data encodings](https://github.com/Christophe-pere/QML-Course/blob/main/Lecture%204/Lecture%204.pdf)
  * Embeddings/Encodings
  * Basis Encoding
  * Amplitude Encoding
  * Time-Evolution Encoding
  * Hamiltonian Encoding
  * Angle Encoding
  * Quantum Feature Maps
  * Quantum Metric Learning
  * [The English version was given during QSciTech QML 2024 Winter School](https://github.com/Christophe-pere/QML-Course/blob/main/Lecture%204/Data%20encoding%20and%20Kernels%20and%20SVM.pdf)
- [Lecture 5: Elementary blocks](https://github.com/Christophe-pere/QML-Course/blob/main/Lecture%205/Lecture%205.pdf)
  * Hilbert Space
  * Hamiltonian
  * Ansatz
  * Barren Plateaus 
- [Lecture 6: Quantum Optimization]() Release February 8
  * MaxCut & Ising Model
  * How to correctly formulate a problem
  * From Ising to QUBO
  * QUBO as a tool for the Optimization problem
  * QAOA
- [Lecture 7: Quantum Neural Networks]() Release February 22
- [Lecture 8: Quantum Kernel Methods]() Release February 29
- [Lecture 9: Variational Algorithms]() Release March 14
- [Lecture 10: Learning Algorithms on Annealing Processor]() Release March 21 
- [Lecture 11: Applications of Quantum Machine Learning]() Release March 28 
- [Lecture 12: The quest for useful applications: Don't be afraid to fail]() Release April 11 

**Extra Material**:
- [Differential Programming]()
- [QML advanced techniques]()
- [Quantum Graph Learning]()

**Complementary Material**:
- [Schuld M. & Killoran N., 2022, Is quantum advantage the right goal for quantum machine learning?](https://arxiv.org/abs/2203.01340)
- [Wiebe N., IPAM 2023, Quantum Machine Learning](https://www.youtube.com/watch?v=0fwsMdE8iVo)
- [Schuld M., IPAM 2023, How to rethink quantum machine learning](https://www.youtube.com/watch?v=VVY8xcps3N4&list=PLHyI3Fbmv0SckwZK0xfc7itiq9nLWJeUF&index=1&pp=iAQB)

## Exam Modalities 
- Mid-session exam: Scientific vulgarization presentation 10 minutes per student
- Homework: QML Research paper reproduction (team - 2 persons)
- Final exam: Presentation of the homework like a conference, 20 minutes for the team

### Mid-session subjects
Non-exhaustive list, students can choose their own 

- Tensor Networks
- Input problem
- Hamiltonian and QML
- Dequantization
- How can QML be used to simulate new materials? 
- Quantum Advantage
- Quantum Image Generation 

### Final exam papers 
Non-exhaustive list, students can choose their own 

- [Senokosov et al. 2023, Quantum machine learning for image classification](https://arxiv.org/pdf/2304.09224.pdf) 
- [Verdon et al., 2019, Graph Neural Networks](https://arxiv.org/pdf/1909.12264.pdf)
- [DiAdamo et al., 2022, Practical Quantum K-Means Clustering: Performance Analysis and Applications in Energy Grid Classification](https://arxiv.org/pdf/2112.08506.pdf) 
- [Huang et al., 2021, Experimental Quantum  Generative Adversarial Networks for Image Generation](https://arxiv.org/pdf/2010.06201v3.pdf)
- [Grossi et al., 2022, Mixed Quantum-Classical Method For Fraud Detection with Quantum Feature Selection](https://arxiv.org/pdf/2208.07963.pdf)
- [Wozniak et al., 2023, Quantum anomaly detection in the latent space of proton collision events at the LHC](https://arxiv.org/pdf/2301.10780.pdf)
- [Slabbert et al., 2023, Pulsar Classification: Comparing Quantum Convolutional Neural Networks and Quantum Support Vector Machines](https://arxiv.org/pdf/2309.15592.pdf)

