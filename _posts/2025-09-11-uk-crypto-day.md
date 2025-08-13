---
title: "UK Crypto Day: 11 September 2025"
subtitle: "The University of Manchester"
redirect_from: /2025/09/11/
---

### Schedule

-  9:00 -  9:45:	Arrival
-  9:45 - 10:00:	Opening remarks	
- 10:00 - 10:45:	**Martin Albrecht & Rikke Bjerg Jensen** (King's College London and Royal Holloway, University of London), *At-Compromise Security: The Case for Alert Blindness*
- 10:45 - 11:15:	Coffee Break	
- 11:15 - 12:00:	**Boris Fouotsa** (EPFL), *Isogeny-based cryptography: from attacks to prime time*
- 12:00 - 13:30:	Lunch
- 13:30 - 14:15:	**Zhipeng Wang** (University of Manchester), *DSKE: Digital Signatures with Key Extraction*
- 14:15 - 14:30:	Short break	
- 14:30 - 15:15:	**Fernando Virdia** (University of Surrey), *Practical Semi-Open Group Messaging*
- 15:15 - 15:45:	Coffee Break	
- 15:45 - 16:30:	**Rachel Player** (Royal Holloway, University of London), *On Algebraic Homomorphic Encryption and its Applications to Doubly-Efficient PIR*
- 16:30 - 18:00:	Closing remarks and networking	

### Registration

Registration is free but required. To register please click [here](https://forms.gle/DpWRhkBExB2uj5WNA). The registration closes one week before the event, or when we reach full capacity. Please, register early!


### Speakers/Talks

#### [Martin Albrecht](https://malb.io/) & [Rikke Bjerg Jensen](https://rikkebjerg.gitlab.io/me/): At-Compromise Security: The Case for Alert Blindness
We start from the observation (Blanchette'12) that cryptography broadly intuits security goals -- as modelled in games or ideal functionalities -- while claiming realism. This stands in contrast to cryptography's attentive approach towards examining assumptions and constructions through cryptanalysis and reductions. To close this gap, we introduce a technique for determining security goals. Given that games and ideal functionalities model specific social relations between various honest and adversarial parties, our approach is grounded in a careful social science methodology for studying social relations in their contexts: ethnography. As a first application of this technique, we study security at-compromise (neither pre- nor post-) and introduce the security goal of alert blindness. Specifically, as observed in our 2024/2025 ethnographic fieldwork with protesters in Kenya, alert blindness captures a security goal of abducted persons who were taken by Kenyan security forces for their presumed activism. It may have applications elsewhere.

*Joint work with Simone Colombo and Benjamin Dowling.*

**Bios.** 
Martin Albrecht is a Professor of Cryptography at King's College London. He works broadly across the field of cryptography but focuses on the analysis of deployed or soon-to-be deployed cryptographic solutions and on analysing the security of lattice-based cryptography against classical and quantum computers.

Rikke Bjerg Jensen is a Professor in the Information Security Group at Royal Holloway, University of London. Her work is ethnographic and grounded in explorations of information security practices and needs among groups of people living and working at the margins of societies.


#### [Boris Fouotsa](https://borisfouotsa.com/): Isogeny-based cryptography: from attacks to prime time
SIDH, one of the most popular isogeny-based schemes, was broken in summer 2022.  This attack had a huge echo within the cryptography community as SIKE, an SIDH based KEM, was in the 4th round of the NIST standardisation process. In this talk, we briefly discuss the reasons why the attacks only apply to SIDH/SIKE and not to other schemes such as SQIsign, CSIDH, and many more. Next, we discuss how the attacks are being used to revitalise the field. We mainly highlight the efficiency gains in SQIsign and in isogeny group action evaluation.

**Bio.** 
Boris is a postdoctoral researcher at the Security and Cryptography lab at EPFL. He enjoys designing and analysing isogeny-based protocols. He is the author of several isogeny-based key exchange, public key encryption and digital signature schemes. He is a contributor to SQIsign.  Besides doing research,  Boris is actively engaged in developing cryptology in Africa.


#### [Zhipeng Wang](https://zhipengwang.io/): DSKE: Digital Signatures with Key Extraction

This work introduces DSKE, digital signatures with key extraction. In a DSKE scheme, the private key can be extracted if more than a threshold number of signatures on different messages are ever created while, within the threshold, each signature continues to authenticate the signed message. We propose a formal definition of DSKE, as well as two provably secure constructions, one from hash-based digital signatures and one from polynomial commitments. We demonstrate that DSKE is useful for various applications, such as cryptographic deniability and spam prevention. First, we introduce the GroupForge signature scheme, leveraging DSKE to achieve deniability in digital communication. GroupForge integrates DSKE with a Merkle tree and timestamps to produce a forward-forgeable signature equipped with extractable sets, ensuring deniability under a fixed public key. We illustrate that GroupForge can serve as a viable alternative to Keyforge in the non-attributable email protocol of Specter, Park, and Green (USENIX Sec ’21), thereby eliminating the need for continuous disclosure of outdated private keys. GroupForge can also operate as a short-lived signature, providing deniability non-interactively and agnostic to time. Second, we leverage the inherent extraction property of DSKE to develop a Rate-Limiting Nullifier (RLN) scheme. RLN efficiently identifies and expels spammers once they exceed a predetermined action threshold, thereby jeopardizing their private keys.

**Bio.** 
Zhipeng Wang is a lecturer (equivalent to an assistant professor) in cybersecurity in the Department of Computer Science at the University of Manchester. He was a postdoctoral research associate at Imperial College London, where he also completed his PhD. His research interests lie in the domain of privacy and security within decentralized and distributed computing systems, with a particular focus on blockchain and decentralized AI systems, as well as the underlying cryptographic primitives and protocols that support and secure them.


#### [Fernando Virdia](https://fundamental.domains/): Practical Semi-Open Group Messaging
Chat groups in secure messaging applications are used for rapid and 
widespread dissemination of information to large groups of people, even 
in sensitive contexts. Manual administration of group membership can be 
burdensome and error-prone, with mistakes potentially exposing 
confidential communication to unintended people. We construct a 
practical privacy-preserving reputation system that automates the 
approval of new group members based on their reputation amongst the 
existing membership. Along the way we propose a security notion, prove 
the protocol secure, and benchmark a proof-of-concept implementation.

**Bio.** 
Fernando Virdia is a Lecturer in Cyber Security at the University of 
Surrey. Fernando's research focuses on developing new practical 
functionality for secure messaging and data storage. He is also active 
in cryptanalysis, with a special focus towards post-quantum 
cryptographic hardness assumptions.

#### [Rachel Player](https://rachelplayer.github.io/): On Algebraic Homomorphic Encryption and its Applications to Doubly-Efficient PIR
The Doubly-Efficient Private Information Retrieval (DEPIR) protocol of Lin, Mook, and Wichs (STOC'23) relies on a Homomorphic Encryption (HE) scheme that is algebraic, i.e., whose ciphertext space has a ring structure that matches the homomorphic operations. Modern HE schemes have introduced techniques for efficiency that destroy the algebraic property. In this work, we revisit algebraic HE and prove a lower bound for the ciphertext ring size of algebraic HE schemes, which demonstrates a gap between optimal algebraic HE and the existing schemes. As we are unable to bridge this gap directly, we instead slightly relax the notion to construct a practically more efficient ‘relaxed-algebraic’ HE scheme, which leads to a more efficient instantiation of DEPIR. We experimentally demonstrate run-time improvements of more than 4x and reduce memory queries by more than 8x compared to prior work. Our construction relies on a new variant of the Ring Learning with Errors (RLWE) problem that we call {0,1}-CRT RLWE, for which we give a formal security reduction to standard RLWE. This is a joint work with Hiroki Okada, Simon Pohmann, and Christian Weinert.

**Bio.** 
Rachel Player is a Senior Lecturer in the Department of Information Security at Royal Holloway, University of London. Her main research interests are in post-quantum cryptography and homomorphic encryption. She was awarded the 2019 Radiant Award for Advancing Internet Security by Internet Security Research Group. She is the co-author (with Sean Murphy) of Cryptography: A Very Short Introduction, 2nd edition (Oxford University Press, 2025).

### Venue

Information Technology Building, Room 407, Oxford Rd, Manchester M13 9PL.

[Google Maps](https://maps.app.goo.gl/moAyduGRbQxMsegS6){:target="_blank"} &#124; [Apple Maps](https://maps.apple.com/place?address=Hulme,%20Manchester,%20M13%209PL,%20England&coordinate=53.467926,-2.233143&name=Information%20Technology%20Building&place-id=I839096BD7E9CA557&map=explore){:target="_blank"} &#124; [OpenStreetMap](https://www.openstreetmap.org/?#map=19/53.467925/-2.233481){:target="_blank"}

### Contacts

For any inquiry related to the event, please send an email to the organizer Bernardo Magri at bernardo.magri at manchester.ac.uk.

The event is sponsored by the Computer Science department of The University of Manchester.

<img src="/static/manchester_logo.png" width="35%">


