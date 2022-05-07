Welcome to our first tutorial worshop on fully homomorphic encrytion (FHE)-based privacy-preserving computing.

### Description

In a typical anything-as-a-service scheme, average clients are reluctant to send their personal data to untrusted servers. Moreover, recent law regulations limit the irresponsible use of private data as more and more financial values are discovered and harvested from the growing amount of data. Privacy-preserving computing becomes critical to enabling average clients to use untrusted servers. In particular, homomorphic encryption (HE) is one of the most promising cryptographic technologies to building privacy-preserving computing systems. Unfortunately, in most real-world applications, HE, especially fully homomorphic encryption (FHE), is notorious for its prohibitive amount of computational overheads. For instance, even on the latest fully-customized FHE hardware accelerator (i.e., F1 from MICRO'21), a FHE-based neural network inference on a small image still requires 0.24 seconds.

To better systematize the opportunities and challenges of FHE-based privacy-preserving computing, in this tutorial, we focus on providing with the audience a thorough introduction to FHE, as well as novel insights over the timely topic of cryptography, hardware, software, and machine learning co-design for the FHE-specific hardware acceleration. We make the observation that the main obstacle behind the design of such privacy-preserving computing systems is the multi-disciplinary nature of
real-world applications. Consequently, only a cross-layer design and optimization approach can make such FHE-based privacy-preserving computing systems practical. Therefore, we will organize the tutorial with the following components.

### Time 
Monday, July 11th, 10:30am - 12:00pm PDT

### Location:
The Moscone Center\
Administrative Office\
747 Howard Street\
San Francisco, CA 94103


### Presenters
* Lei Jiang, Indiana University, Bloomington
* Takashi Sato, Kyoto University
* Jiansong Zhang, Alibaba Group

### Organizers
* Song Bian, Kyoto University
* Yue Zhang, Nanyang Technological University


#### Topic 1: Cryptography and Applications

Dr. Lei Jiang will introduce the preliminary knowledge on the algebraic and algorithmic foundations of ring learning with errors (RLWE)-based FHE. They will also present their recent progresses over applying privacy-preserving neural network inference (ICRL'21, ICML'21) to visual recognition, text analysis, and other industrial real-world applications.

#### Topic 2: FHE Circuit Construction and Synthesis

Dr. Takashi Sato will present his recent work on a FHE standard cell library (WAHC'21), optimizations on FHE-based Boolean circuitry, and a FHE-based RISC-V CPU (Security'21). He will present how to build composite logic gates over FHE, e.g., 3-input gates and multi-output gates using FHE including Half Adder, Full Adder and AOI21. At last, he will introduce how to build a FHE-based five-stage pipelined RISC-V processor using customized FHE gates.

#### Topic 3: Hardware and Algorithm Co-design

Dr. Jiansong Zhang will introduce their latest results on hardware-accelerated privacy-preserving
machine learning. More specifically, they will introduce their recent work on privacy-preserving neural-network inference, where a new convolution protocol is proposed to aid the efficient design of accelerator architecture (TIFS'21, CVPR'20). Then, they will introduce the latest hardware architecture from industry to accelerate real-world deployment of FHE-based secure protocols.

