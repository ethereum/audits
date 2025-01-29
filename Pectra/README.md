# Pectra System Contracts Audits

This repository contains the audit reports for the Pectra System Contracts, covering multiple phases of security reviews and fixes.
---

## Overview

Each audit was performed sequentially in the order below and integrated fixes based on the previous reports, meaning that issues discovered by earlier auditors were typically resolved before the next audit commenced.

1. **[Blackthorn Audit](Blackthorn_Audit_2024_09_12_Final_Ethereum_Foundation_Blackthorn.pdf)**

2. **Dedaub Audits**  
   - [EIP2935](Dedaub%20-%20EIP2935.pdf)
   - [EIP7002](Dedaub%20-%20EIP7002.pdf)
   - [EIP7251](Dedaub%20-%20EIP7251.pdf)

3. **[PlainShift Audit](Plainshift%20EF%20Pectra%20Audit.pdf)**

4. **[Sigma Prime Audit](Sigma_Prime_Ethereum_Foundation_Pectra_System_Contracts_Bytecode.pdf)**

## Formal Verification

Formal verification was conducted independently and concurrently with the security audits to provide additional assurance that the compiled bytecode of the Pectra system contracts conforms to their EIP specifications.

1. **[a16z Halmos Formal Verification](https://github.com/daejunpark/sys-asm-halmos)**: The linked repository contains detailed information on the verification process. It also includes all verification artifacts, which can be reproduced and further extended by anyone. These artifacts are actively maintained and updated to reflect the latest version of the Pectra system contracts.

---
