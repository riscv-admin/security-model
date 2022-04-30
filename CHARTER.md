# Security Model TG Charter

RISC-V is lacking documentation that provides security guidance for RISC-V designers and implementers. The Security Model TG will create a specification that outlines requirements and recommendations for RISC-V based platforms.

Proposed specification outline:

  - Introduction & guiding principles
  - A threat model, defining in-scope threats & mitigations
  - A security overview and platform security model for RISC-V
  - Platform security requirements & recommendations

The specification is expected to cover topics such as root-of-trust, secure boot, memory model security, attestation, secure (credential) storage, recommended cryptographic algorithms (including post-quantum readiness), key length/strength and life-cycle, entropy, (unclonable) unique identity, product life-cycle guidance (including returns and debug), side-channel mitigations, firmware updates & resiliency, tamper resistance, supply chain security, and other critical items. The TG will also prioritize, determine interdependencies, and provide mapping of the required and recommended security topics for each of the (future) RISC-V Platform specifications.

The Security Model TG&apos;s scope of work includes:

  - Create a Platform Security Specification (a non-ISA spec);
  - Collect feedback and seek advice from many groups within RVI, but specifically from the Security HC, Software HC, and SoC Infrastructure HC.

The Security Model TG&apos;s scope of work excludes:

  - Definition or development of formal models or software artifacts.

Current target for specification freeze is by the end of Q2 2023.
