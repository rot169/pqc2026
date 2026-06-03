# Post-Quantum Cryptography Workshop @ Infosec Europe 2026
This repo contains resources for Andy Smith's PQC workshop held at Infosec Europe 2026, in partnership with SANS. 

Access the lab script below:

* [Lab: Explore the current state of quantum-resistant cryptography on the public internet](lab1.md)

## Got feeback?

Find me on LinkedIn: https://linkedin.com/andysmith-uk

## Links and resources referenced in the class:

Bold (overblown!) PQC claims in the news:
* https://www.bbc.co.uk/news/articles/c791ng0zvl3o
* https://www.bankinfosecurity.com/blogs/researcher-claims-to-crack-rsa-2048-quantum-computer-p-3536
* https://www.csoonline.com/article/3562701/chinese-researchers-break-rsa-encryption-with-a-quantum-computer.html
* https://www.bbc.co.uk/news/articles/cj4p7gyvp52o

Royalty-free industry-wide PQC crypto - standards at: https://www.nist.gov/pqcrypto

Run your own PQC benchmark (assuming you have Docker installed):
`docker run -it alpine/openssl:latest speed -kem-algorithms`

An excellent walktrough of the maths behind lattice crypto (e.g., ML-KEM, ML-DSA): https://www.youtube.com/watch?v=K026C5YaB3A

PQC plans/roadmaps:
* NSA: https://media.defense.gov/2022/Sep/07/2003071834/-1/-1/0/CSA_CNSA_2.0_ALGORITHMS_.PDF
* Google: https://blog.google/innovation-and-ai/technology/safety-security/cryptography-migration-timeline

Sam Jaques' fantastic analysis of the evolution of current quantum capabilities vs what's needed to break crypto: https://sam-jaques.appspot.com/quantum_landscape

Migration guidelines:
* From NIST: https://nvlpubs.nist.gov/nistpubs/ir/2024/NIST.IR.8547.ipd.pdf
* From NCSC: https://www.ncsc.gov.uk/guidance/pqc-migration-timelines

What is "state-of-the-art"? https://www.enisa.europa.eu/news/enisa-news/what-is-state-of-the-art-in-it-security

Further reading:
* https://globalriskinstitute.org/publication/quantum-threat-timeline-2025
* https://blog.cloudflare.com/pq-2025
