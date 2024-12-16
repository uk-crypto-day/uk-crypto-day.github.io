---
title: "UK Crypto Day: 4 March 2024"
subtitle: "University of Bristol"
redirect_from: /2024/03/04/
---

## Schedule

-  9:00 -  9:45:	Arrival
-  9:45 - 10:00:	Opening remarks	
- 10:00 - 10:45:	**Ngoc Khanh Nguyen**, *Polynomial Commitments from Lattices*
- 10:45 - 11:15:	Break	
- 11:15 - 12:00:	**Elisabeth Oswald**, *Explainable Leakage Assessments*
- 12:00 - 13:30:	Lunch	
- 13:30 - 14:15:	**Jan Bobolz**, *On the Impossibility of Surviving (Iterated) Deletion of Weakly Dominated Strategies in Rational MPC*
- 14:15 - 14:30:	Short break	
- 14:30 - 15:15:	**Luca de Feo**, *SQIsign: past, present and future*
- 15:15 - 15:45:	Break	
- 15:45 - 16:30:	**Yiannis Tselekounis**, *Optimal Single-Server Private Information Retrieval*
- 16:30 - 17:00:	Lightning talks	
- 17:00 - 19:00:	Reception	
- 19:00 - onward:   Dinner

## Registration

Registration is free but required. To register please click [here](https://forms.office.com/Pages/ResponsePage.aspx?id=MH_ksn3NTkql2rGM8aQVG_lsqBw7Z0VJqfKDlAYbPipURVcxM0E0OTRKTTZWMjBGWkU2VjJXNjQ5WS4u).


## Speakers/Talks

### [Elisabeth Oswald](https://research.birmingham.ac.uk/en/persons/elisabeth-oswald): Explainable Leakage Assessments

In this talk I will explain recent research that aims to capture the idea of "explainability" in a statistical manner and connect this with so-called non-specific leakage assessment methods. Such methods are of interest when assessing composite cryptographic  products; here the precise leakage characteristics of the underlying hardware are not knowing to the assessor, but they have access to the source of the cryptographic software. 

**Bio.** Elisabeth Oswald's research focuses on implementation aspects of cryptography, in particular, statistical methods for evaluations. She is currently a Professor for Applied Cryptography at the University of Birmingham, and still holds a part-time appointment at the University of Klagenfurt. 

### [Jan Bobolz](https://jan-bobolz.de/): On the Impossibility of Surviving (Iterated) Deletion of Weakly Dominated Strategies in Rational MPC 

Rational MPC provides a framework for analyzing MPC protocols through the lens of game theory. It is an exciting way of looking at MPC because it allows us to make statements about a setting where no participant is inherently honest (which usually precludes any cryptography), but all parties are rational. 
It is also challenging to model, as one has to marry the largely information-theoretical nature of game theory with cryptographic guarantees against computationally bounded adversaries. 

We discuss these challenges and point out (eprint 2022/1762) flaws in the modeling of iterated deletion of weakly dominated strategies, showing that, in contrast to claims in the literature, (essentially) no protocol is rationally secure under that notion. We invite future research into game-theoretic modeling of MPC.

**Bio.** Jan Bobolz is interested in all things provable security, with a focus on security modeling, privacy-preserving constructions, and zero-knowledge proofs. He is a research associate at the University of Edinburgh’s ZK Lab. He was previously a PhD student at Paderborn University.

### [Luca de Feo](https://defeo.lu/): SQIsign: past, present and future

SQIsign is a NIST-candidate post-quantum signature scheme with exceptional size and performance... but exceptions are not always a positive. In this talk I will explain the theory behind SQIsign, in as simple terms as possible. Then I will show the good and the bad sides of SQIsign. Finally, I will survey recent proposals to improve some aspects of it.

**Bio.** Luca De Feo is a researcher at IBM Research Europe working on quantum-safe cryptography. He graduated from École Polytechnique in 2010 with a thesis on isogeny computations; He has been computing them ever since.



### [Ngoc Khanh Nguyen](https://kclpure.kcl.ac.uk/portal/en/persons/ngoc_khanh.nguyen): Polynomial Commitments from Lattices: Post-Quantum Security, Fast Verification and Transparent Setup

Polynomial commitment scheme allows a prover to commit to a polynomial f over of degree L, and later prove that the committed function was correctly evaluated at a specified point x; in other words f(x)=u for public x,u. Most applications of polynomial commitments, e.g. succinct non-interactive arguments of knowledge (SNARKs), require that (i) both the commitment and evaluation proof are succinct (i.e., polylogarithmic in the degree L) - with the latter being efficiently verifiable, and (ii) no pre-processing step is allowed.

Surprisingly, as far as plausibly quantum-safe polynomial commitments are concerned, the currently most efficient constructions only rely on weak cryptographic assumptions, such as security of hash functions. Indeed, despite making use of the underlying algebraic structure, prior lattice-based polynomial commitments still seem to be much behind the hash-based ones. Moreover, security of the aforementioned lattice constructions against quantum adversaries was never formally discussed.

In this work, we bridge the gap and propose the first (asymptotically and concretely) efficient lattice-based polynomial commitment with transparent setup and post-quantum security. Our interactive variant relies on the standard (Module-)SIS problem, and can be made non-interactive in the random oracle model using Fiat-Shamir transformation. In addition, we equip the scheme with a knowledge soundness proof against quantum adversaries which can be of independent interest. In terms of concrete efficiency, for L=2^{20} our scheme yields proofs of size 2X smaller than the hash-based FRI commitment (Asiacrypt 2023), and 60X smaller than the very recent lattice-based construction by Albrecht, Fenzi, Lapiha and Nguyen (Eprint 2023/1469).

**Bio.** Ngoc Khanh Nguyen is a lecturer at King's College London. His current topics of interests are (but not limited to) efficient lattice-based constructions and efficient post-quantum zero-knowledge proofs.

Previously, Khanh was a postdoctoral researcher at EPFL, hosted by Prof. Alessandro Chiesa. He obtained his PhD degree at ETH Zurich and IBM Research Europe - Zurich, supervised by Dr Vadim Lyubashevsky and Prof. Dennis Hofheinz. Before that, he did his undergraduate and master studies at the University of Bristol, UK.

### [Yiannis Tselekounis](https://www.yiannistselekounis.com/): Optimal Single-Server Private Information Retrieval

Imagine that a server holds a large public database DB indexed by 0, 1, . . . , n−1, e.g., the repository of DNS entries or a collection of webpages. A client wants to fetch the i-th entry of the database. Although the database is public, the client wants to hide which entry it is interested in. Chor, Goldreich, Kushilevitz, and Sudan [CGKS95, CKGS98], first formulated this problem as Private Information Retrieval (PIR), and since then, a long line of works have focused on constructing efficient PIR schemes. 
 
We construct a single-server pre-processing Private Information Retrieval (PIR) scheme with optimal bandwidth and server computation (up to poly-logarithmic factors), assuming hardness of the Learning With Errors (LWE) problem. Our scheme achieves amortized O(n^(1/2)) server and client computation and O(1) bandwidth per query, completes in a single roundtrip, and requires O(n^(1/2)) client storage, matching the lower bound of Corrigan-Gibbs, Henzinger, and Kogan [Eurocrypt’22] (the “O” notation is hiding polylogarithmic factors). 

**Bio.** Yiannis Tselekounis is a Lecturer at the Department of Information Security at Royal Holloway, University of London. His research focuses on applied and theoretical aspects of cryptography, including the security of cryptographic protocols, leakage/tamper-resilient cryptography, and blockchains.

## Lightning Talks

There will be a lightning talk session at the end of the day to present new results and make announcements (open positions, upcoming events, etc.). If you would like to give a lightning talk (max 3 minutes), email [andrea.basso@bristol.ac.uk](mailto:andrea.basso@bristol.ac.uk) (possibly with slides).


## Venue

Viridor Theatre   
Great Western Dockyard  
Gas Ferry Road  
Bristol BS1 6TY\
[Google Maps](https://www.google.com/maps/place/Brunel's+SS+Great+Britain/@51.4491729,-2.6074661,18.72z/data=!4m14!1m7!3m6!1s0x48718dd2012bde19:0x40bd3ee1518221f1!2sHarbourside+Kitchen!8m2!3d51.4490424!4d-2.6073653!16s%2Fg%2F11b6z38jqb!3m5!1s0x48718dcdf73d3043:0x15fc8e91caed2d23!8m2!3d51.4491712!4d-2.6084058!16zL20vMG1nbGI?entry=ttu){:target="_blank"} &#124; [Apple Maps](https://maps.apple.com/?address=Bristol,%20England&auid=779860821186750947&ll=51.449077,-2.607136&lsp=9902&q=Brunel's%20SS%20Great%20Britain%20Terminal){:target="_blank"} &#124; [OpenStreetMap](https://www.openstreetmap.org/way/48859354){:target="_blank"}

**How to get there.** If you arrive between 9 and 10, there will be a member of staff waiting by the black gates (next to the Harbourside Café) who will guide you in. If you arrive after 10am, please reach out to a member of staff of the Harbourside Café. In case of any issue, email either [andrea.basso@bristol.ac.uk](mailto:andrea.basso@bristol.ac.uk) or [f.dupressoir@bristol.ac.uk](mailto:f.dupressoir@bristol.ac.uk).
