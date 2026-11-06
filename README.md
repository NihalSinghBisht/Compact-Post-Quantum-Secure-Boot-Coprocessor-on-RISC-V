# Compact-Post-Quantum-Secure-Boot-Coprocessor-on-RISC-V

We propose to design, verify and take to GDSII a small post-quantum cryptography (PQC) coprocessor
tightly coupled to an open-source RISC-V core, targeting a 180 nm process. The first version focuses on
signature verification for secure boot (ML-DSA, the NIST-standardized lattice signature), plus a
fault-resilient hash (Keccak) unit that can detect both random faults (such as radiation upsets) and
deliberately injected faults. 

The goal is a complete RTL-to-GDSII flow, measurable area, power and timing
results, and a Research paper.
