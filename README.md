# QML-Course
I developed a course on quantum machine learning for École de Technologie Supérieure (Montréal, QC, CA) with support from [Catalina Albornoz Anzola](https://www.linkedin.com/in/catalinaalbornoz/). She is the Quantum Community Manager at [Xanadu](https://xanadu.ai). 

The course is given to students at the end of their bachelor's degree or the beginning of their Master's degree. Prerequisites in linear algebra and introduction to quantum computing or quantum information are needed. The course gave an overview of the field in 2024 and the prerequisites for students interested in developing QML algorithms or applying them to real-world scenarios. 

The course is in French, so the slides are in French but can be translated. [PennyLane](https://pennylane.ai) is the primary library during the course. 

> Notebooks are provided in html format. They are built on demos from [PennyLane](https://pennylane.ai)

Winter session January to May 2024. 

## Resources 
Three books are used as primary resources for this first edition of the course (pre-alpha 2024). 
- [Schuld M. & Petruccione F., 2021, Machine Learning with quantum computers, 2nd edition](https://link.springer.com/book/10.1007/978-3-030-83098-4)
- [Hidary J. D., 2021, Quantum Computing: An Applied Approach, 2nd edition](https://link.springer.com/book/10.1007/978-3-030-83274-2)
- [Combarro E. F. & Gonzàlez-Castillo, 2023, A practical guide to quantum machine learning and Quantum optimization](https://www.packtpub.com/product/a-practical-guide-to-quantum-machine-learning-and-quantum-optimization/9781804613832)

Additional resource: [The Codebook by Xanadu](https://codebook.xanadu.ai/). The introduction is available in French. 

Research papers and YouTube videos used for the courses are cited where needed and placed in the References slides at the end of each lecture. 

## Content 

> Not all lectures are yet available. Lecture 9 will be given on March 14 and uploaded. Each lecture will be uploaded each week. 

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
  * [Hamiltonian](https://github.com/Christophe-pere/QML-Course/blob/main/Lecture%205/Hamiltonian.pdf) by [Antoine Lemelin](https://www.linkedin.com/in/antoine-lemelin-6b9929238/)
  * Ansatz
  * Barren Plateaus 
- [Lecture 6: Quantum Optimization](https://github.com/Christophe-pere/QML-Course/blob/main/Lecture%206/Lecture%206.pdf) 
  * MaxCut & Ising Model
  * How to correctly formulate a problem
  * From Ising to QUBO
  * QUBO as a tool for the Optimization problem
- [Lecture 7: Variational Quantum Algorithms](https://github.com/Christophe-pere/QML-Course/blob/main/Lecture%207/Lecture%207.pdf) 
  * QAOA
  * VQA
  * VQE - We weren't able to reach this point after 2h45. This part will be given on February 29
  * VQC 
- [Lecture 8: Quantum Kernel Methods](https://github.com/Christophe-pere/QML-Course/blob/main/Lecture%208/Lecture%208.pdf) 
  * SVM
  * QSVM and kernels 
- [Lecture 9: Quantum Neural Networks](https://github.com/Christophe-pere/QML-Course/blob/main/Lecture%209/Lecture%209.pdf) 
  * Classical Neural Networks 
  * Quantum Neural Networks
- [Lecture 10: Learning Algorithms on Annealing Processor](https://github.com/Christophe-pere/QML-Course/blob/main/Lecture%2010/Lecture%2010.pdf) 
  * Adiabatic vs Digital
  * Quantum Annealing
  * Quantum Analog
  * Neutral Atoms
  * [Introduction to Optimization using an Analog Quantum Computer](https://github.com/Christophe-pere/QML-Course/blob/main/Lecture%2010/ETS-part1-qubo.pdf), presentation by [Victor Drouin-Touchette](https://www.linkedin.com/in/victor-drouin-touchette-165030124/?originalSubdomain=ca)
  * [Graph Machine learning using Pasqal's neutral atom quantum computer](https://github.com/Christophe-pere/QML-Course/blob/main/Lecture%2010/ETS-part2-qek.pdf), presentation by [Victor Drouin-Touchette](https://www.linkedin.com/in/victor-drouin-touchette-165030124/?originalSubdomain=ca)
- [Lecture 11: Applications of Quantum Machine Learning](https://github.com/Christophe-pere/QML-Course/blob/main/Lecture%2011/Lecture%2011.pdf) 
  * This course was an application to solve a challenge by applying all the concepts learned during the course. Students had to build a quantum classifier on a dataset containing molecules. The data was provided by the [SherHack23](https://www.youtube.com/watch?v=aOXiLqPVMpE). They had the choice between Kernel, VQC and QNN. The objective was to test different architectures, feature maps, and preprocessing to improve performance.
  * Pictures of the leaderboard: 
[[https://github.com/Christophe-pere/QML-Course/blob/main/Lecture%2011/IMG_6372.jpeg]]
 
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

## Feedbacks 

Currently, the feedbacks I have on the course are: 
- Add Learning theory on a quantum system (PAC learning)
- Add information extraction from a circuit (swap and Hadamard tests)
- Add Reinforcement Learning in Course 2
- Prepare a pdf on how to install the libraries for course 3 
- Course 4 on data encoding needs to be more detailed and add examples and why this is important for the algorithms 

