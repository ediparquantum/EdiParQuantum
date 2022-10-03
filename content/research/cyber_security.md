---
title: "Cyber Security"
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
### Future Communication

Future information and communication networks will certainly consist of both classical and quantum devices, some of which are expected to be dishonest, with various degrees of functionality, ranging from simple routers to servers executing quantum algorithms. 

### Foreseeable Futures

In a hybrid quantum and classical approach, we consider three plausible scenarios, from the closest to the furthest foreseeable future, and try to study them thoroughly by elaborating adversarial models and designing or analysing concrete protocols with formal security proofs, in order to get ready as soon as one of these scenarios becomes the new reality. 

### Resistant Classical Cryptography

The first scenario considers post-quantum cryptography as in the NIST’s standardization, i.e. classical cryptography resistant to a potential quantum adversary, without giving any quantum resource to the honest people. 


### Quantum Enhanced Classical Cryptography

In the second scenario, we assume that quantum communication is accessible to anybody and we try to take advantage of it in what we call quantum-enhanced classical cryptography. 

### Completely Quantum

Finally, in the third scenario, we go one step further, assume a completely quantum world and investigate the consequences on the security of cryptography. 

### Assessments

In each case, we need to assess the powers of the attacker and find the most relevant security models.


# Cyber Security Papers

## Certified Randomness From Steering Using Sequential Measurements

### Abstract

The generation of certifiable randomness is one of the most promising applications of quantum technologies. Furthermore, the intrinsic non-locality of quantum correlations allow us to certify randomness in a device-independent way, i.e. one need not make assumptions about the devices used. Due to the work of Curchod et. al., a single entangled two-qubit pure state can be used to produce arbitrary amounts of certified randomness. However, the obtaining of this randomness is experimentally challenging as it requires a large number of measurements, both projective and general. Motivated by these difficulties in the device-independent setting, we instead consider the scenario of one-sided device independence where certain devices are trusted, and others not; a scenario motivated by asymmetric experimental set-ups such as ion-photon networks. We show how certain aspects of previous work can be adapted to this scenario and provide theoretical bounds on the amount of randomness which can be certified. Furthermore, we give a protocol for unbounded randomness certification in this scenario, and provide numerical results demonstrating the protocol in the ideal case. Finally, we numerically test the possibility of implementing this scheme on near-term quantum technologies, by considering the performance of the protocol on several physical platforms.

**arXiv:** https://arxiv.org/abs/2008.00705

## Dispelling Myths on Superposition Attacks: Formal Security Model and Attack Analyses

### Abstract

It is of folkloric belief that the security of classical cryptographic protocols is automatically broken if the Adversary is allowed to perform superposition queries and the honest players forced to perform actions coherently on quantum states. Another widely held intuition is that enforcing measurements on the exchanged messages is enough to protect protocols from these attacks.
However, the reality is much more complex. Security models dealing with superposition attacks only consider unconditional security. Conversely, security models considering computational security assume that all supposedly classical messages are measured, which forbids by construction the analysis of superposition attacks. Boneh and Zhandry have started to study the quantum computational security for classical primitives in their seminal work at Crypto'13, but only in the single-party setting. To the best of our knowledge, an equivalent model in the multiparty setting is still missing.
In this work, we propose the first computational security model considering superposition attacks for multiparty protocols. We show that our new security model is satisfiable by proving the security of the well-known One-Time-Pad protocol and give an attack on a variant of the equally reputable Yao Protocol for Secure Two-Party Computations. The post-mortem of this attack reveals the precise points of failure, yielding highly counter-intuitive results: Adding extra classical communication, which is harmless for classical security, can make the protocol become subject to superposition attacks. We use this newly imparted knowledge to construct the first concrete protocol for Secure Two-Party Computation that is resistant to superposition attacks. Our results show that there is no straightforward answer to provide for either the vulnerabilities of classical protocols to superposition attacks or the adapted countermeasures.

**arXiv:**  https://arxiv.org/abs/2007.00677

## Client-Server Identification Protocols with Quantum PUF

### Abstract

Recently, major progress has been made towards the realisation of quantum internet to enable a broad range of classically intractable applications. These applications such as delegated quantum computation require running a secure identification protocol between a low-resource and a high-resource party to provide secure communication. In this work, we propose two identification protocols based on the emerging hardware secure solutions, the quantum Physical Unclonable Functions (qPUFs). The first protocol allows a low-resource party to prove its identity to a high-resource party and in the second protocol, it is vice-versa. Unlike existing identification protocols based on Quantum Read-out PUFs which rely on the security against a specific family of attacks, our protocols provide provable exponential security against any Quantum Polynomial-Time adversary with resource-efficient parties. We provide a comprehensive comparison between the two proposed protocols in terms of resources such as quantum memory and computing ability required in both parties as well as the communication overhead between them.

**arXiv:** https://arxiv.org/abs/2006.04522

## Definitions and Analysis of Quantum E-voting Protocols

### Abstract

Recent advances indicate that quantum computers will soon be reality. Motivated by this ever more realistic threat for existing classical cryptographic protocols, researchers have developed several schemes to resist "quantum attacks". In particular, for electronic voting, several e-voting schemes relying on properties of quantum mechanics have been proposed. However, each of these proposals comes with a different and often not well-articulated corruption model, has different objectives, and is accompanied by security claims which are never formalized and are at best justified only against specific attacks. To address this, we propose the first formal security definitions for quantum e-voting protocols. With these at hand, we systematize and evaluate the security of previously-proposed quantum e-voting protocols; we examine the claims of these works concerning privacy, correctness and verifiability, and if they are correctly attributed to the proposed protocols. In all non-trivial cases, we identify specific quantum attacks that violate these properties. We argue that the cause of these failures lies in the absence of formal security models and references to the existing cryptographic literature.

**arXiv:** https://arxiv.org/abs/1810.05083