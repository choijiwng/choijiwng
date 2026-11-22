**English** | [한국어](https://github.com/choijiwng/choijiwng/blob/main/README.ko.md)

# Jiwoong Choi

Undergraduate in Information Security Engineering at Sangmyung University, preparing for offensive security work in 2027.

## Interests

- Vulnerability research and system security
- Penetration testing and red teaming
- Binary exploitation (pwnable) and CTF
- Security of AI agents and AI-assisted security tooling

## Affiliation

- **Sangmyung University**, Department of Information Security Engineering, 2022.03 – present
- **WhateverTakes**, CTF team

## Research

### InodeFence, 2026.10 – present

Research prototype that observes filesystem state before and after TAR extraction to check for security-boundary violations, such as an extracted file sharing an inode with a file outside the extraction directory. Team project.

- Reproduced the node-tar hardlink escape for two known CVEs, CVE-2026-23745 and CVE-2026-24842, in a controlled environment. A single outcome-based oracle (inode sharing with an external file) distinguishes affected from fixed releases for both. These are reproductions of known issues, not discoveries of mine, and I do not claim any new vulnerability.
- Commits in the team repository, implemented with Claude (AI assistant), include the reproduction script and raw-evidence records, a comparison of Python `tarfile` extraction policies (`fully_trusted` vs `data`) using the same oracle, a symlink-target confinement check, and a terminal summary for demo runs.
- Limits: results come from controlled fixtures in a disposable Linux environment. The fuzzer's effectiveness over random or baseline strategies is not established.

Repository: [TheWaitForAGI/InodeFence](https://github.com/TheWaitForAGI/InodeFence)

## Awards and Honors

- **Finalist**, `2026 KISIA Information Security Contest (Finals)` as *WhateverTakes* (2026.08), [certificate](https://github.com/choijiwng/choijiwng/blob/main/certificates/2026-kisia-finals-participation.pdf)
- **Excellence Award**, `2025 Chungnam IT Hackathon (Beginner Division)` as *SS통합* (2025.09), [certificate](https://github.com/choijiwng/choijiwng/blob/main/certificates/2025-chungnam-it-hackathon-excellence-award.pdf)
- **Completed**, `Web Vulnerability-Based Penetration Testing 2025`, Sangmyung University Cheonan Industry-Academic Cooperation Foundation (2025.09), [certificate](https://github.com/choijiwng/choijiwng/blob/main/certificates/2025-web-pentest-completion.pdf)
- **Completed**, `Introduction to Information Security (Web, Reversing, Forensics, Pwnable) 2025`, Sangmyung University Cheonan Industry-Academic Cooperation Foundation (2025.09), [certificate](https://github.com/choijiwng/choijiwng/blob/main/certificates/2025-infosec-intro-completion.pdf)

## Projects & Write-ups

- [InodeFence](https://github.com/TheWaitForAGI/InodeFence) (2026.10 – present): TAR extraction boundary-violation research prototype, described above.
- [CTF-OS](https://github.com/whatevertakes/CTF-OS) (2026.06 – 2026.08): Codex-based engine that works on one human-selected CTF challenge at a time inside a challenge-scoped Docker sandbox. Challenge selection and flag submission are done by a human. Main developer and team lead of WhateverTakes.
- [BBS](https://github.com/choijiwng/BBS) (2026.05 – 2026.06): bulletin board in Node.js, Express and PostgreSQL, with bcrypt password hashing, CSRF protection, Helmet and rate limiting.
- [cic-ids2017-visualization](https://github.com/choijiwng/cic-ids2017-visualization) (2026.04 – 2026.05): analysis and visualization of attack and benign traffic distributions in the CIC IDS 2017 dataset, in Python.
- [pwnable](https://github.com/choijiwng/pwnable) (2025.12 – 2026.02): study notes and exploit write-ups on buffer overflow, return-to-shellcode, return-to-libc, ROP, use-after-free and tcache poisoning.

## Contact

- GitHub: [choijiwng](https://github.com/choijiwng)
- Email: jiwoong729@gmail.com
