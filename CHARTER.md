# Security Model TG Charter

RISC-V needs documentation that provides security guidance for RISC-V hardware and software designers and implementers. The Security Model TG will create a specification that outlines requirements and recommendations for RISC-V based platforms. 

Proposed specification outline:
- Introduction & guiding principles; 
- A threat model, defining in-scope threats & mitigations; 
- A security overview and platform security model for RISC-V;
- Platform security requirements & recommendations.

The specification is expected to cover topics such as root-of-trust, secure boot, memory model security, attestation, secure (credential) storage, recommended cryptographic algorithms (including post-quantum readiness), key length/strength and life-cycle, entropy, (unclonable) unique identity, product life-cycle guidance (including returns and debug), side-channel mitigations, firmware updates & resiliency, tamper resistance, supply chain security, and other critical items. The Security Model specification will - where applicable - reference other specifications (both RVI and non-RVI) for implementation details, mark a topic as Work In-Progress if it is under (active) development, or indicate that a topic may be addressed in the future.

The TG will also prioritize, determine interdependencies, and provide mapping of the required and recommended security topics for each of the (future) RISC-V Platform specifications.
 
The Security Model TG’s scope of work includes: 
- Create a Security Specification for RISC-V platforms (a non-ISA spec); 
- Collect feedback and seek advice from various groups within RVI, but specifically from the Security HC, Software HC, and SoC Infrastructure HC.

The Security Model TG’s scope of work excludes definition or development of formal models or software artifacts. 

Current target for specification freeze is by the end of Q2 2023.

