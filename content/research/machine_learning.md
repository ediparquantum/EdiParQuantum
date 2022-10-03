---
title: "Machine Learning"
sidebar: true # or false to display the sidebar
sidebarlogo: atom # From (static/images/logo/)
include_footer: true # or false to display the footer
---
<div class="notification has-background-primary is-light is-light has-text-grey-darker	">
  <button class="delete"></button>
  <p>
  We are hiring several researchers (junior and senior) at either locations of Edinburgh or Paris to work on 
  <ul>
    <li>Quantum Cryptography,</li>
    <li>Quantum Verification and/or</li>
    <li>Quantum Machine Learning</li>
  </ul>
  in collaboration with key industries in the UK and France 
    <ul>
    <li>Rigetti,</li>
    <li>Riverlane,</li>
    <li>NPL,</li>
    <li>VeriQloud and </li>
    <li>Pasqal.</li>
  </ul>
  </p>
  
<p>The project will be tailor made depending on the expertise and interest of the candidate as long as it fits to our general mission of finding useful applications for quantum computing and communication.</p>

<p>Interested candidates can get in touch with Prof. Elham Kashefi.
<ul>
  <li><a href = "mailto: ekashefi@gmail.com">ekashefi@gmail.com</a></li>
</ul>
</p>

<p>A complete job description can be found
<ul>
<li><a href="https://elxw.fa.em3.oraclecloud.com/hcmUI/CandidateExperience/en/sites/CX_1001/job/5321/?utm_medium=jobshare">Senior Researcher, University of Edinburgh, School of Informatics</a></li>
</ul>
</p>
</div>

### Near Term

The search for an application of near-term quantum devices is widespread. 

### Quantum Learning

Quantum Machine Learning is touted as a potential utilisation of such devices, particularly those which are out of the reach of the simulation capabilities of classical computers. 

### Generative Models

We explore generative Quantum Learning that cannot, in the worst case, and up to suitable notions of error, be simulated efficiently by a classical device. 

### Applications

We also develop specific use cases in Finance, Cryptanalysis, and Optimal Compiling for such models and compare the capabilities of quantum versus classical models for such tasks.

# Machine Learning Papers

## Quantum versus Classical Generative Modelling in Finance

### Abstract

Finding a concrete use case for quantum computers in the near term is still an open question, with machine learning typically touted as one of the first fields which will be impacted by quantum technologies. In this work, we investigate and compare the capabilities of quantum versus classical models for the task of generative modelling in machine learning. We use a real world financial dataset consisting of correlated currency pairs and compare two models in their ability to learn the resulting distribution - a restricted Boltzmann machine, and a quantum circuit Born machine. We provide extensive numerical results indicating that the simulated Born machine always at least matches the performance of the Boltzmann machine in this task, and demonstrates superior performance as the model scales. We perform experiments on both simulated and physical quantum chips using the Rigetti forest platform, and also are able to partially train the largest instance to date of a quantum circuit Born machine on quantum hardware. Finally, by studying the entanglement capacity of the training Born machines, we find that entanglement typically plays a role in the problem instances which demonstrate an advantage over the Boltzmann machine.

**arXiv:** https://arxiv.org/abs/2008.00691


## The Born Supremacy: Quantum Advantage and Training of an Ising Born Machine

### Abstract

The search for an application of near-term quantum devices is widespread. Quantum Machine Learning is touted as a potential utilisation of such devices, particularly those which are out of the reach of the simulation capabilities of classical computers. In this work, we propose a generative Quantum Machine Learning Model, called the Ising Born Machine (IBM), which we show cannot, in the worst case, and up to suitable notions of error, be simulated efficiently by a classical device. We also show this holds for all the circuit families encountered during training. In particular, we explore quantum circuit learning using non-universal circuits derived from Ising Model Hamiltonians, which are implementable on near term quantum devices.
We propose two novel training methods for the IBM by utilising the Stein Discrepancy and the Sinkhorn Divergence cost functions. We show numerically, both using a simulator within Rigetti's Forest platform and on the Aspen-1 16Q chip, that the cost functions we suggest outperform the more commonly used Maximum Mean Discrepancy (MMD) for differentiable training. We also propose an improvement to the MMD by proposing a novel utilisation of quantum kernels which we demonstrate provides improvements over its classical counterpart. We discuss the potential of these methods to learn 'hard' quantum distributions, a feat which would demonstrate the advantage of quantum over classical computers, and provide the first formal definitions for what we call 'Quantum Learning Supremacy'. Finally, we propose a novel view on the area of quantum circuit compilation by using the IBM to 'mimic' target quantum circuits using classical output data only.

**arXiv:** https://arxiv.org/abs/1904.02214

## Quantum Physical Unclonable Functions: Possibilities and Impossibilities

### Abstract

A Physical Unclonable Function (PUF) is a device with unique behaviour that is hard to clone hence providing a secure fingerprint. A variety of PUF structures and PUF-based applications have been explored theoretically as well as being implemented in practical settings. Recently, the inherent unclonability of quantum states has been exploited to derive the quantum analogue of PUF as well as new proposals for the implementation of PUF. We present the first comprehensive study of quantum Physical Unclonable Functions (qPUFs) with quantum cryptographic tools. We formally define qPUFs, encapsulating all requirements of classical PUFs as well as introducing a new testability feature inherent to the quantum setting only. We use a quantum game-based framework to define different levels of security for qPUFs: quantum exponential unforgeability, quantum existential unforgeability and quantum selective unforgeability. We introduce a new quantum attack technique based on the universal quantum emulator algorithm of Marvin and Lloyd to prove no qPUF can provide quantum existential unforgeability. On the other hand, we prove that a large family of qPUFs (called unitary PUFs) can provide quantum selective unforgeability which is the desired level of security for most PUF-based applications.

**arXiv:** https://arxiv.org/abs/1910.02126


