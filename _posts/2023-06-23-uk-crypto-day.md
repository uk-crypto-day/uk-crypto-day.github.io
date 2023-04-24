---
title:  "UK Crypto Day: 23 June 2023"
redirect_from: /2023/06/23/
---

## Schedule

-  9:00 -  9:45	Arrival
-  9:45 - 10:00	Opening remarks	
- 10:00 - 10:45	Jonathan Bootle
- 10:45 - 11:00	Short break	
- 11:00 - 11:45	Bernardo Magri
- 11:45 - 12:30	Sunoo Park
- 12:30 - 14:00	Lunch	
- 14:00 - 14:45	Michele Ciampi
- 14:45 - 15:00	Short break	
- 15:00 - 15:45	François Dupressoir 
- 15:45 - 16:15	Break	
- 16:15 - 17:00	Yixin Shen
- 17:00 - 17:30	Lightning talks	
- 17:30 - 19:00	Reception	

## Registration


## Speakers/Talks

### [Bernardo Magri](https://bernardomagri.eu/): YOSO – You Only Speak Once

Imagine a setting where whenever a party in a protocol sends a message, its IP address becomes known, and it gets immediately killed by the adversary in a DoS attack. This implies that in any given protocol a party can only send a single message at a random point in time. Can we do secure multiparty computation in this setting? In this talk we introduce the YOSO MPC model that is based around the notion of roles, which are randomly assigned stateless parties that can send a single message for the entire duration of the protocol. We will show how one we can leverage the infrastructure of public blockchains to securely YOSO-compute any function with private inputs.

**Bio.** Bernardo Magri is a Senior Lecturer at the CS department at University of Machester. His research interests are on the theoretical and practical aspects of cryptography and distributed ledgers.

### [Michele Ciampi](https://www.research.ed.ac.uk/en/persons/michele-ciampi): On the round-complexity of secure multi-party computation

In multi-party computation (MPC), multiple entities, each having some inputs want to jointly compute a function of these inputs with the guarantee that nothing aside from the output of the function will be leaked. In this talk, we are going to investigate how many messages the parties of an MPC need to exchange to securely realise any functionality with simulation-based security in the case where there is no setup and the majority of the parties can be corrupted. We will then consider a relaxation of the standard simulation-based paradigm, and discuss whether this lead to more efficient MPC protocols which still realize non-trivial functionalities which meaningful security.

**Bio.** Michele Ciampi is a Chancellor's Fellow at the School of Informatics at the University of Edinburgh. His work focuses on theoretical aspects of cryptography, including multi-party computation protocols, zero-knowledge proofs, and blockchain.

### [François Dupressoir](): Revisiting machine-checked AKE security — Reports from a possibly active trench

Machine-checked cryptographic proofs, as supported by tools such as EasyCrypt, CryptHOL or SSProve, aim at increasing trust in cryptographic algorithms by producing machine-checkable evidence that their security follows from relatively (sometimes) standard hardness assumptions. With only a few exceptions, their application has unfortunately been limited to small, typically non-interactive, constructions. A significant exception is a Eurocrypt 2015 paper applying EasyCrypt to a family of Authenticated Key Exchange protocols, whose massive proof has unfortunately been lost to time (and some obnoxious IT practices). This talk will report on an ongoing (or perhaps, hopefully, not) attempt at understanding better the interplay between EasyCrypt, interactive protocols, and a few competing pen-and-paper definition and proof methodologies. By doing so, I hope to provoke discussions around the goal and value of security proof and their machine-checked variants, and about what "traditional" cryptographers might expect or want from proof tools.

**Bio.** François Dupressoir is a Senior Lecturer at the University of Bristol, where he heads the Cryptography Research Group. His research revolves around bringing formal methods and formal reasoning techniques to cryptographic security of algorithms, protocols and their implementations.


### [Yixin Shen](https://www.irif.fr/~yixin.shen/): Finding Many Collisions via Reusable Quantum Walks — Application to Lattice Sieving

Given a random function $f$ with domain $[2^n]$ and codomain $[2^m]$, with $m \geq n$, a collision of $f$ is a pair of distinct inputs with the same image. Collision finding is a ubiquitous problem in cryptanalysis, and it has been well-studied using both classical and quantum algorithms. Indeed, the quantum query complexity of the problem is well known to be $\Theta(2^{m/3})$, and matching algorithms are known for any value of $m$. The situation becomes different when one is looking for multiple collision pairs. Here, for $2^k$ collisions, a query lower bound of $\Theta(2^{(2k+m)/3})$ was shown by Liu and Zhandry (EUROCRYPT~2019). A matching algorithm is known, but only for relatively small values of $m$, when many collisions exist.

In this paper, we improve the algorithms for this problem and, in particular, extend the range of admissible parameters where the lower bound is met. Our new method relies on a chained quantum walk algorithm, which might be of independent interest. It allows to extract multiple solutions of an MNRS-style quantum walk, without having to recompute it entirely: after finding and outputting a solution, the current state is reused as the initial state of another walk. As an application, we improve the quantum sieving algorithms for the Shortest Vector Problem (SVP), with a complexity of $2^{0.2563d + o(d)}$ instead of the previous $2^{0.2570d + o(d)}$.

**Bio.** Yixin Shen is a research fellow at Royal Holloway, University of London. Her work focuses on quantum algorithms and their application in lattice-based cryptanalysis. She completed her PhD at Université Paris Cité in 2021. After that, she worked as a postdoctoral researcher at Royal Holloway. In 2022, she obtained a five-year EPSRC Quantum Technology Career Development Fellowship.

## Venue

King's College London  
Room: MB4.2  
Macadam Building, Strand Campus  
Strand, London WC2R 2LS  
London
