---
title: "Cloud Computing"
sidebar: true # or false to display the sidebar
sidebarlogo: fresh-white-alt # From (static/images/logo/)
include_footer: true # or false to display the footer
---

### Increased computation

Secure delegated quantum computing allows a computationally weak client to outsource an arbitrary quantum computation to an untrusted quantum server in a privacy-preserving manner. 

### Security Schemes

We have developed several schemes using quantum communications between client and server to achieve information-theoretic security. 

### Post quantum computation

Recently we have also shown how the same functionality with a purely classical client can be also obtained but reducing the security to being post-quantum computationally secure. 

### Protocol Complexity

The assumptions are necessary as we provided strong evidence that such protocol could not provide informational-theoretic security without violating some widely accepted complexity assumptions. 

### Share the big news

Have you opened a new location, redesigned your shop, or added a new product or service? Don't keep it to yourself, let folks know.


### Quantum Channels

Our works revealed a previously unknown feature of quantum channel usage compared to a classical one in the setting of quantum cloud computing. We are developing other client-server-based protocols for distributed quantum computing.


# Cloud Computing Papers

### Security Limitations of Classical-Client Delegated Quantum Computing

#### Abstract

Secure delegated quantum computing allows a computationally weak client to outsource an arbitrary quantum computation to an untrusted quantum server in a privacy-preserving manner. One of the promising candidates to achieve classical delegation of quantum computation is classical-client remote state preparation (RSPCC), where a client remotely prepares a quantum state using a classical channel. However, the privacy loss incurred by employing RSPCC as a sub-module is unclear.
In this work, we investigate this question using the Constructive Cryptography framework by Maurer and Renner (ICS'11). We first identify the goal of RSPCC as the construction of ideal RSP resources from classical channels and then reveal the security limitations of using RSPCC. First, we uncover a fundamental relationship between constructing ideal RSP resources (from classical channels) and the task of cloning quantum states. Any classically constructed ideal RSP resource must leak to the server the full classical description (possibly in an encoded form) of the generated quantum state, even if we target computational security only. As a consequence, we find that the realization of common RSP resources, without weakening their guarantees drastically, is impossible due to the no-cloning theorem. Second, the above result does not rule out that a specific RSPCC protocol can replace the quantum channel at least in some contexts, such as the Universal Blind Quantum Computing (UBQC) protocol of Broadbent et al. (FOCS '09). However, we show that the resulting UBQC protocol cannot maintain its proven composable security as soon as RSPCC is used as a subroutine. Third, we show that replacing the quantum channel of the above UBQC protocol by the RSPCC protocol QFactory of Cojocaru et al. (Asiacrypt '19), preserves the weaker, game-based, security of UBQC.


**arXiv:** https://arxiv.org/abs/2007.01668


### QFactory: classically-instructed remote secret qubits preparation

#### Abstract

The functionality of classically-instructed remotely prepared random secret qubits was introduced in (Cojocaru et al 2018) as a way to enable classical parties to participate in secure quantum computation and communications protocols. The idea is that a classical party (client) instructs a quantum party (server) to generate a qubit to the server's side that is random, unknown to the server but known to the client. Such task is only possible under computational assumptions. In this contribution we define a simpler (basic) primitive consisting of only BB84 states, and give a protocol that realizes this primitive and that is secure against the strongest possible adversary (an arbitrarily deviating malicious server). The specific functions used, were constructed based on known trapdoor one-way functions, resulting to the security of our basic primitive being reduced to the hardness of the Learning With Errors problem. We then give a number of extensions, building on this basic module: extension to larger set of states (that includes non-Clifford states); proper consideration of the abort case; and verifiablity on the module level. The latter is based on "blind self-testing", a notion we introduced, proved in a limited setting and conjectured its validity for the most general case.

**arXiv:** https://arxiv.org/abs/1904.06303

### Complexity-theoretic limitations on blind delegated quantum computation

#### Abtract

Blind delegation protocols allow a client to delegate a computation to a server so that the server learns nothing about the input to the computation apart from its size. For the specific case of quantum computation we know that blind delegation protocols can achieve information-theoretic security. In this paper we prove, provided certain complexity-theoretic conjectures are true, that the power of information-theoretically secure blind delegation protocols for quantum computation (ITS-BQC protocols) is in a number of ways constrained. In the first part of our paper we provide some indication that ITS-BQC protocols for delegating BQP computations in which the client and the server interact only classically are unlikely to exist. We first show that having such a protocol with O(nd) bits of classical communication implies that BQP⊂MA/O(nd). We conjecture that this containment is unlikely by providing an oracle relative to which BQP⊄MA/O(nd). We then show that if an ITS-BQC protocol exists with polynomial classical communication and which allows the client to delegate quantum sampling problems, then there exist non-uniform circuits of size 2n−Ω(n/log(n)), making polynomially-sized queries to an NPNP oracle, for computing the permanent of an n×n matrix. The second part of our paper concerns ITS-BQC protocols in which the client and the server engage in one round of quantum communication and then exchange polynomially many classical messages. First, we provide a complexity-theoretic upper bound on the types of functions that could be delegated in such a protocol, namely QCMA/qpoly∩coQCMA/qpoly. Then, we show that having such a protocol for delegating NP-hard functions implies coNPNPNP⊆NPNPPromiseQMA.

**arXiv:** https://arxiv.org/abs/1704.08482

### The Quantum Cut-and-Choose Technique and Quantum Two-Party Computation

#### Abstract

The application and analysis of the Cut-and-Choose technique in protocols secure against quantum adversaries is not a straightforward transposition of the classical case, among other reasons due to the difficulty to use rewinding in the quantum realm. We introduce a Quantum Computation Cut-and-Choose (QC-CC) technique which is a generalisation of the classical Cut-and-Choose in order to build quantum protocols secure against quantum covert adversaries. Such adversaries can deviate arbitrarily provided that their deviation is not detected. As an application of the QC-CC we give a protocol for securely performing two-party quantum computation with classical input/output. As basis we use secure delegated quantum computing (Broadbent et al 2009), and in particular the garbled quantum computation of (Kashefi et al 2016) that is secure against only a weak specious adversaries, defined in (Dupuis et al 2010). A unique property of these protocols is the separation between classical and quantum communications and the asymmetry between client and server, which enables us to sidestep the quantum rewinding issues. This opens the prospect of using the QC-CC to other quantum protocols with this separation. In our proof of security we adapt and use (at different parts) two quantum rewinding techniques, namely Watrous' oblivious q-rewinding (Watrous 2009) and Unruh's special q-rewinding (Unruh 2012). Our protocol achieves the same functionality as in previous works (e.g. Dupuis et al 2012), however using the QC-CC technique on the protocol from (Kashefi et al 2016) leads to the following key improvements: (i) only one-way offline quantum communication is necessary , (ii) only one party (server) needs to have involved quantum technological abilities, (iii) only minimal extra cryptographic primitives are required, namely one oblivious transfer for each input bit and quantum-safe commitments.

**arXiv:** https://arxiv.org/abs/1703.03754
