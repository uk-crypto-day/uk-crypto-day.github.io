---
title: "UK Crypto Day"
subtitle: University of Sheffield
redirect_from: /2025/06/12/
---

### Schedule

- 9:00 - 9:45 Arrival
- 9:45 - 10:00 Opening remarks
- 10:00 - 10:45 Christophe Petit
- 10:45 - 11:00 Short break
- 11:00 - 11:45 Sidharth Jaggi
- 11:45 - 12:30 Cong Ling
- 12:30 - 14:00 Lunch
- 14:00 - 14:45 Feng Hao
- 14:45 - 15:00 Short break
- 15:00 - 15:45 Amir R. Asadi
- 15:45 - 16:15 Break
- 16:15 - 17:00 Benjamin Dowling
- 17:00 - 17:30 Lightning talks
- 17:30 - 19:00 Reception

### Abstracts of Talks:

PETIT Christophe (Université libre de Bruxelles (ULB) and University of Birmingham)

Title:
 Quantum Security of the Vectorization Problem with Shifted Inputs
 
Abstract:
Cryptographic group actions provide a basis for simple post-quantum generalizations of many cryptographic protocols based on the discrete logarithm problem (DLP). However, many advanced group action-based protocols do not solely rely on the core group action problem (the so-called vectorization problem), but also on variants of this problem, to either improve efficiency or enable new functionalities. In particular, the security of the CSI-SharK threshold signature protocol relies on the hardness of the Vectorization Problem with Shifted Inputs where (in DLP formalism) the adversary not only receives $g$ and $g^x$, but also $g^{x^c}$ for multiple known values of $c$. A natural open question is whether the extra data provided to the adversary in this variant allows them to solve the underlying problem more efficiently.
In this paper, we revisit the concrete quantum security of this problem. We start from a quantum multiple hidden shift algorithm of  Childs and van Dam, which to the best of our knowledge was never applied in cryptography before. We specify algorithms for its subroutines and we provide concrete complexity estimates for both these subroutines and the overall algorithm.
We apply our analysis to the CSI-SharK protocol. In prior analyses based on Kuperberg's algorithms, group action evaluations contributed to a significant part of the overall T-gate cost. For CSI-SharK suggested parameters, our new approach requires significantly fewer calls to the group action evaluation subroutine, leading to  significant complexity improvements overall. We describe two instances of our approach, one which lowers the T-gate complexity, and the other the QRAM requirements. We obtain significant speedups -- even in both metrics simultaneously -- and we quantify the degradation of the quantum security of the protocol when the number of curves in the public key increases.  This is based on joint work with Paul Frixons, Valerie Gilchrist, Péter Kutas and Simon Merz

Bio:
Christophe Petit is an Associate Professor at the University of Birmingam and the Free University of Brussels. His research interests are in cryptography, particularly cryptanalysis and mathematical aspects.




Sidharth Jaggi (University of Bristol)

Title:
 Communication in the presence of adversarial jamming: The curious case of the erasure channel
 
Abstract: 
Alice wishes to communicate with Bob, but the malicious jammer James wishes to stop this communication from occurring. What can she do? In this talk I'll explore recent discoveries/capacity-characterizations in a variety of settings (the role of causality in James' jamming, the role of myopicity in his observations, the interplay between these two, and the effect of rate-limited feedback). I'll focus on one of the simplest non-trivial jamming channels -- the case of a binary input channel, in which James may erase a constant fraction of transmissions -- even here, interesting phenomena occur. Time permitting, I may also briefly describe generalizations to other jamming channels/scenarios.

Bio: 
Sidharth (Sid) Jaggi (B.Tech. IIT Bombay 2000, M.S./Ph.D. CalTech 2006, all in electrical engineering, Post-Doctoral Associate MIT 2006). He joined The Chinese University of Hong Kong in 2007, and the School of Mathematics at the University of Bristol in 2020, where he is currently a Professor of Information and Coding Theory and Director of the EPSRC INFORMED-AI Hub. His research group (somewhat unwillingly) calls itself the CAN-DO-IT Team (Codes, Algorithms, Networks: Design and Optimization for Information Theory) — his research involves identifying fundamental limits of information-processing systems such as data storage, communication, estimation, classification etc (especially those where a potentially malicious adversary is aiming to subvert this information-processing task), and devising algorithms that approach these limits.




Cong Ling (Imperial College London)

Title:
 An Information Theory for Post-Quantum Cryptography: Learning With Quantization
 
Abstract: 
Information Theory and Cryptography share a common foundation in Shannon’s pioneering work. These fields are deeply interconnected and have the potential to mutually enhance one another. The advent of Post-Quantum Cryptography (PQC) offers a unique opportunity to reunite these disciplines. In this work, we uncover a novel connection between information theory and the Learning With Errors (LWE) problem. Specifically, we introduce Learning With Quantization (LWQ), a new problem closely related to LWE and Learning With Rounding (LWR). LWQ establishes a tight security reduction from LWE while enabling efficient ciphertext compression. Notably, we demonstrate that the compression rate is ultimately governed by the capacity of the “LWE channel,” thereby unifying the concepts of information-theoretic compression and computational security. Paper: https://eprint.iacr.org/2024/714
 
Bio:
Cong Ling is a Professor of Information Theory and Cryptography at Imperial College London. His research focuses on the study of lattices and their applications to coding and cryptography, as well as exploring their connections with number theory and quantum information.





Feng Hao (University of Warwick)

Title: 
Advances in password-authenticated key exchange
 
Abstract:
In this talk, I will first review three decades of research in the field of password-authenticated key exchange (PAKE), which is a foundational technique to establish secure communication. PAKE protocols can be categorized into two types: balanced and augmented schemes. I will share our experience of designing a balanced PAKE called J-PAKE in 2008 (joint work with Ryan) based on Ross Anderson and Roger Needham’s 6th robustness principle. Today, J-PAKE has been deployed in real-world applications at a large scale, e.g., Google Nest, ARM Mbed, Amazon Fire stick and Thread products. 
 Next, I will focus on augmented PAKE. Today, SRP-6a is the only augmented PAKE that has enjoyed wide use, e.g., in Apple's iCloud, 1Password and Proton mail. However, SRP-6a has known limitations, such as heuristic security, a lack of efficiency (due to the mandated use of a safe prime) and a lack of support for elliptic curve implementations. In 2018, IETF chose OPAQUE as a standard candidate for augmented PAKE, but there are open technical issues with OPAQUE. I will present Owl, a new augmented PAKE (joint work with Bag, Chen and van Oorshot) based on adapting J-PAKE to an augmented setting. Owl has systematic advantages over SRP-6a, including security, computation, communication, and cryptographic agility. Owl is also free from several security and implementation issues faced by OPAQUE.

Bio:
Feng Hao is a Professor of Security Engineering at the Department of Computer Science, University of Warwick. He received his PhD in 2007 in Computer Science from the University of Cambridge. He worked in the security industry for a few years before joining academia. With colleagues, he designed a few cryptographic protocols: AV-net, OV-net, J-PAKE, YAK, DRE-i, DRE-ip, SEAL, Owl and Camel. Among them, J-PAKE (with Peter Ryan) has been adopted by the Thread Group as a de facto standard to perform the IoT commissioning process (used in Google Nest, ARM mbed, Amazon Firestick and iPhone 16) and standardized in ISO/IEC 11770-4. DRE-ip (with Siamak Shahandashti) was successfully trialled in Gateshead during the UK local elections on 2 May 2019, and in New Town, India in October 2022. His 2006 paper (with Ross Anderson and John Daugman) on "combining crypto with biometrics effectively" (IEEE Trans. Computers) is ranked the top in Google Classic papers in the category of "cryptography & computer security". His work on "self-enforcing e-voting" has led to a €1.5m ERC starting grant and an ERC proof-of-concept grant. With Peter Ryan, he co-edited a book "Real-World Electronic Voting: Design, Analysis and Deployment" (CRC Press, 2017).





Amir R. Asadi (University of Cambridge)

Title: 
Differential Privacy: A Stability-Based Perspective

Abstract: 
Differential privacy (DP) is a mathematically rigorous framework for quantifying privacy leakage, balancing utility and privacy, and obtaining formal guarantees. In this survey‐style talk, we will frame differential privacy through the lens of algorithmic stability. Beginning with a simple example, we will revisit epsilon-privacy and explain how mechanisms such as Laplace and Gaussian noise achieve stability guarantees. We will then cover group privacy and composition theorems, and explore Renyi DP as an information-theoretic relaxation of epsilon-privacy. Special attention will then be given to f-DP and Gaussian DP, which offer a statistical perspective and benefit from a tight composition theorem—a key strength of the f-DP framework. Finally, we will present applications including synthetic data generation and private machine learning.

Bio:
Amir R. Asadi is a Leverhulme Early Career Fellow at the Statistical Laboratory, part of the Department of Pure Mathematics and Mathematical Statistics at the University of Cambridge. He earned his M.A. and Ph.D. in Electrical and Computer Engineering from Princeton University in 2017 and 2021, respectively, after completing dual B.Sc. degrees in Mathematics and Electrical Engineering from Sharif University of Technology in 2015. His research interests include machine learning, differential privacy, and information theory.




Benjamin Dowling (King’s College London) 


Abstract: 
Space networking has become an increasing area of development with the advent of commercial satellite networks such as those hosted by Starlink and Kuiper, and increased satellite and space presence by governments around the world. Historically such network designs have not been made public, leading to limited formal analysis of their security. One of the few public protocols used in space networking is the Bundle Protocol, which is secured by Bundle Protocol Security (BPSec), an Internet Engineering Task Force (IETF) standard. BPSec allows members of satellite groups (that share the same secret keys) to process messages on behalf of the group, which we capture as an "intermediate processing" property. In this talk I describe the results of the first formal analysis of BPSec, introducing a model of the secure channel security goals stated in the IETF standard, and note issues therein with message loss detection. I then introduce a stronger construction that supports the Bundle Protocol's intermediate processing goals while also ensuring detection of maliciously dropped message components.

Bio:
Benjamin Dowling is a Senior Lecturer in the Department of Informatics at King’s College London since August 2024. Previously, Benjamin was a Lecturer of Cybersecurity in the Security of Advanced Systems research group at the University of Sheffield. Benjamin held postdoctoral research positions at the Applied Cryptography group at ETH Zurich, and at the Information Security Group at Royal Holloway, University of London under Kenny Paterson. He received his PhD at the Queensland University of Technology under the supervision of Douglas Stebila, which focused on the provable security of internet protocols. Benjamin is interested in the provable security of real-world cryptography, extending security frameworks to bridge the gap between theoretical cryptography and its usage in the real-world. His notable publications examine the security of secure communication protocols such as SSL/TLS, secure messaging protocols such as Signal and Matrix, and introducing post-quantum security in practical cryptographic protocols.



### Registration

Registration is free but required.
The registration closes on June 1st.
Please register [here](...).

### Venue

Diamond LT02,
Diamond  Building,
University of Sheffield,
32 Leavygreave Rd, Broomhall, 
Sheffield S3 7RD


[Google Maps](https://www.google.com/maps/place/The+Diamond/@53.3817443,-1.4819343,17z/data=!3m1!4b1!4m6!3m5!1s0x48797881e28b3e81:0x611c9522ca2169ed!8m2!3d53.3817443!4d-1.4819343!16s%2Fg%2F1yglpf1x8?entry=ttu&g_ep=EgoyMDI1MDUwNy4wIKXMDSoJLDEwMjExNDUzSAFQAw%3D%3D)

### Contacts

For enquiries please email Behzad Abdolmaleki,  behzad.abdolmaleki at sheffield.ac.uk
