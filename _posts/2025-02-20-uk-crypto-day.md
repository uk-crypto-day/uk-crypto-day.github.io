---
title: "UK Crypto Day"
subtitle: King's College London
redirect_from: /2025/02/20/
---

### Schedule

- 9:00 - 9:45 Arrival
- 9:45 - 10:00 Opening remarks
- 10:00 - 10:45 Kenny Paterson
- 10:45 - 11:00 Short break
- 11:00 - 11:45 Anamaria Costache
- 11:45 - 12:30 Danilo Francati
- 12:30 - 14:00 Lunch
- 14:00 - 14:45 Tom Gur
- 14:45 - 15:00 Short break
- 15:00 - 15:45 Elisabeth Oswald
- 15:45 - 16:15 Break
- 16:15 - 17:00 Behzad Abdolmaleki
- 17:00 - 17:30 Lightning talks
- 17:30 - 19:00 Reception

### Abstracts

Kenny Paterson

Title:

Oblivious Message Retrieval and Ciphertext Compression

Abstract:

In this talk, I’ll introduce the topic of Oblivious Message Retrieval (OMR).
OMR addresses the question: how can a receiver efficiently collect pertinent encrypted messages from a server without revealing to the server which messages it is collecting, and without just downloading all the messages and doing trial decryption of them all?
OMR has the potential to reduce metadata leakage in secure messaging systems.
I’ll also explain how Ciphertext Compression can be used as a technique in building OMR to reduce the amount of bandwidth consumed by the receiver during download, and how old ideas from coding theory (DFTs, linear complexity, Blahut’s theorem) come into play here.
Finally, I’ll illustrate how Paillier encryption enables a nice balance of performance and security in enabling Ciphertext Compression.
This talk is based on joint work with Laura Hetz and Moritz Teichner.

Bio:

Since 2019, Kenny has been a full professor of Computer Science at ETH Zurich, Switzerland, where he leads the Applied Cryptography Group (https://appliedcrypto.ethz.ch/).
Prior to that, he was a Professor of Information Security at Royal Holloway, University of London (2004-2019).
He was made a Fellow of the IACR in 2017, was the Editor-in-Chief of the Journal of Cryptology between 2017 and 2020, and was the programme chair of EUROCRYPT 2011. He was an invited speaker at ASIACRYPT 2014 and EUROCRYPT 2024, and will give the IACR Distinguished Lecture in 2025. His research has won several internationally competitive prizes, including an Applied Networking Research Prize from the Internet Research Task Force (2014), a PET award for outstanding research in Privacy Enhancing Technologies (2015), and best paper awards at NDSS 2012, ACM CCS 2016 and 2022, and IEEE S&P 2022 and 2023.
He is co-founder of the “Real World Cryptography” series of workshops, which provide a forum for industry and academia to come together to exchange ideas in this rapidly developing field.

Anamaria Costache

Title:

Revisiting the Security of Approximate FHE with Noise-Flooding Countermeasures

Abstract:

Approximate fully homomorphic encryption (FHE) schemes, such as the CKKS scheme (Cheon, Kim, Kim, Song, ASIACRYPT '17), are among the leading schemes in terms of efficiency and are particularly suitable for Machine Learning (ML) tasks.
Although efficient, approximate FHE schemes have some inherent risks: Li and Micciancio (EUROCRYPT '21) demonstrated that while these schemes achieved the standard notion of CPA-security, they failed against a variant, IND-CPA-D, in which the adversary is given limited access to the decryption oracle.
Subsequently, Li, Micciancio, Schultz, and Sorrell (CRYPTO '22) proved that with noise-flooding countermeasures which add Gaussian noise of sufficiently high variance before outputting the decrypted value, the CKKS scheme is secure.
However, the variance required for provable security is very high, inducing a large loss in message precision.
In this work, we consider a broad class of attacks on CKKS with noise-flooding countermeasures, which we call ``semi-honest'' attacks, in which an adversary may submit only correctly distributed ciphertexts to the decryption oracle.
The ciphertexts submitted for decryption can be fresh ciphertexts, or can be ciphertexts resulting from the homomorphic evaluation of some circuit on fresh and independent ciphertexts.
Our motivation is to model an internal threat scenario where an adversary can passively access the internal randomness of the system.
We analyze the concrete security of CKKS with various levels of noise-flooding in the face of such attacks.
The aim of this work is to outline and precisely quantify the various trade-offs between the number of allowed decryptions before refreshing the keys, noise-flooding levels, and the concrete security of the scheme after a number of decryptions have been observed by the adversary.
Due to the large dimension and modulus in typical FHE parameter sets, previous techniques even for \emph{estimating} the concrete runtime of such attacks -- such as those in (Dachman-Soled, Ducas, Gong, Rossi, CRYPTO '20) -- become computationally infeasible, since they involve high dimensional and high precision matrix multiplication and inversion.
We therefore develop new techniques that allow us to perform fast security estimation, even for FHE-size parameter sets.

Bio:

Anamaria Costache is an associate professor at NTNU. Previously, she was a part-time employee at Intel.
Before that, she was a postdoc at the ISG group at RHUL, working with Martin Albrecht and Rachel Player.
Before that, she worked as a Research Scientist at Intel AI Research in San Diego.
She completed her PhD at Bristol University, under the supervision of Nigel Smart.
She is interested in fully homomorphic encryption and more broadly, computing on encrypted data, lattice-based and post-quantum cryptography.

Danilo Francati

Title:

Watermarks in the Sand: Impossibility of Strong Watermarking for Generative Models
 
Abstract:

Watermarking generative models consists of planting a statistical signal (watermark) in a model's output so that it can be later verified that the output was generated by the given model.
A strong watermarking scheme satisfies the property that a computationally bounded attacker cannot erase the watermark without causing significant quality degradation.
In this talk, we prove that, under well-specified and natural assumptions, strong watermarking is impossible to achieve.
This holds even in the private detection algorithm setting, where the watermark insertion and detection algorithms share a secret key, unknown to the attacker.
To prove this result, we introduce a generic efficient watermark attack; the attacker is not required to know the private key of the scheme or even which scheme is used.
The impossibility is based on two assumptions: (1) The attacker has access to a "quality oracle" that can evaluate whether a candidate output is a high-quality response to a prompt, and (2) The attacker has access to a "perturbation oracle" which can modify an output with a nontrivial probability of maintaining quality, and which induces an efficiently mixing random walk on high-quality outputs.
Both assumptions can be satisfied in practice by an attacker with weaker computational capabilities than the watermarked model itself, to which the attacker has only black-box access.
Furthermore, these assumptions will likely only be easier to satisfy over time as models grow in capabilities and modalities.
 
Bio:

Danilo Francati is a Lecturer in the Department of Information Security at Royal Holloway, University of London.
Before joining Royal Holloway, he was a Postdoctoral Researcher at George Mason University (2024) and Aarhus University (2021–2024).
He earned his Ph.D. in September 2021 from Stevens Institute of Technology, where he conducted his research under the guidance of Giuseppe Ateniese.
His research focuses on theoretical and applied cryptography, particularly advanced public-key primitives, blockchain, space-based primitives, and security aspects of A.I.

Tom Gur

Title:

A Zero-Knowledge PCP Theorem

Abstract:

We show that for every polynomial q there exist polynomial-size, constant-query, non-adaptive PCPs for NP, which are perfect zero-knowledge against (adaptive) adversaries making at most q queries to the proof.
In addition, we construct exponential-size constant-query PCPs for NEXP with perfect zero knowledge against any polynomial-time adversary.
This improves upon both a recent construction of perfect zero-knowledge PCPs for #P (STOC 2024) and the seminal work of Kilian, Petrank and Tardos (STOC 1997).

Based on joint works with Jack O’Connor and Nicholas Spooner.

Elisabeth Oswald

Title:

Explainable Leakage Assessments

Abstract:

In this talk I will explain recent research that aims to capture the idea of “explainability” in a statistical manner and connect this with so-called non-specific leakage assessment methods.
Such methods are of interest when assessing composite cryptographic products; here the precise leakage characteristics of the underlying hardware are not knowing to the assessor, but they have access to the source of the cryptographic software.

Bio:

Elisabeth’s research focusses on implementation aspects of cryptography, in particular, statistical methods for evaluations.
She is currently a Professor for Applied Cryptography at the University of Birmingham, and still holds a part-time appointment at the University of Klagenfurt.

Behzad Abdolmaleki

Title:

Smooth Hash Proof Systems and its Applications

Abstract:

Smooth Projective Hash Functions (SPHFs) can be viewed as Honest-Verifier Zero-Knowledge (HVZK) arguments for membership in a specific language L.
Roughly speaking, to prove membership of a word x in a language L, the verifier generates a secret hashing key.
Using this key, the verifier can compute the hash value H for any word x  without knowledge of the witness w.
Additionally, the verifier can derive a projection key from the hashing key and send it to the prover.
By knowing a witness w  for the membership of x in L and having the projection key, the prover is able to efficiently compute the projective hash for the word x such that it matches the hash H computed by the verifier.
The smoothness property ensures that for an invalid word x, the hash value H cannot be guessed, and the output of the hash function remains indistinguishable.
SPHFs are a fundamental cryptographic primitive with applications spanning multiple areas, including Password-Authenticated Key Exchange (PAKE), Zero-Knowledge Proofs (ZKPs), and Oblivious Transfer (OT).
In our research, we investigate SPHF families in a malleable setting, where participants can adaptively modify cryptographic elements.
We define malleable variants of SPHF families, extending their utility by enabling controlled transformations while maintaining their core security guarantees.
Leveraging this construction, we utilise this new primitive to construct a PAKE protocol with stronger security guarantees.

Bio:

Behzad is a Lecturer in Computer Science at the University of Sheffield.
His research focuses on zero-knowledge proofs,  privacy-preserving constructions, quantum and post-quantum cryptography.

### Registration

Registration is free but required.
The registration closes one week before the event, or when we reach full capacity.
Please register [here](https://docs.google.com/forms/d/e/1FAIpQLSf3_6ZklVbQzbnxdFNFKSeLjzq1NauIR_3EX-fhLkJW9J9Abg/viewform?usp=dialog).

### Venue

Jean Hanson Room,
Henriette Raphael Building,
King's College London,
Great Maze Pond,
London SE1 1UL

[Google Maps](https://maps.app.goo.gl/ifs6dRzRiZjcBghc7)

### Contacts

For enquiries please email Khanh Nguyen ngoc_khanh.nguyen at kcl.ac.uk or Eamonn Postlethwaite eamonn.postlethwaite at kcl.ac.uk
