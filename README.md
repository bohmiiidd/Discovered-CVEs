# Discovered CVEs

A collection of vulnerabilities I've discovered, reported, and disclosed.
Each folder below contains a detailed writeup and proof-of-concept notes for one CVE.

## Index

| CVE ID | Title | Component | Severity | Type |
|---|---|---|---|---|
| [CVE-2025-56005](./CVE-2025-56005) | Undocumented RCE in PLY via unsafe pickle deserialization | PLY (Python Lex-Yacc) `yacc.py` | 9.8 (CRITICAL) | CWE-502 (Deserialization of Untrusted Data) |
| [CVE-2026-74285](./CVE-2026-74285) | Stale DMA mapping in netkit RX queue lease teardown | Linux kernel networking | 8.8 (HIGH) | Use-after-free / race condition |
| [CVE-2026-90691](./CVE-2026-90691) | Path traversal in HexStrike AI file sandbox allows arbitrary file write | HexStrike AI file operations manager | 8.3 (HIGH) | CWE-22 (Path Traversal) |
| [CVE-2026-116258](./CVE-2026-116258) | Heap overflow in AFC packet handling | libimobiledevice AFC | HIGH | CWE-122 (Heap-based Buffer Overflow) |
| [CVE-2026-116259](./CVE-2026-116259) | Memory corruption in afc_get_device_info_key | libimobiledevice AFC | MEDIUM | CWE-476 (NULL Pointer Dereference) |
| [CVE-2026-116260](./CVE-2026-116260) | Double free in service_receive error path | libimobiledevice service layer | CVSS 7.3 | CWE-415 (Double Free) |
| [CVE-2026-116261](./CVE-2026-116261) | Uninitialized heap read in afc_file_open | libimobiledevice AFC | MEDIUM | CWE-908 (Use of Uninitialized Resource) |
| [CVE-2026-116262](./CVE-2026-116262) | Heap overflow in webinspector_receive_with_timeout | libimobiledevice webinspector | MEDIUM | CWE-122 (Heap-based Buffer Overflow) |
| [CVE-2026-107734](./CVE-2026-107734) | SyncTeX argument injection enables arbitrary command execution via external editors | SumatraPDF SyncTeX inverse search | HIGH | CWE-88 (Argument Injection) |

## Structure

Each CVE folder generally includes:

- A description of the vulnerability and root cause
- Affected products/versions and fixed versions (where applicable)
- Impact analysis
- Proof-of-concept details or reproduction steps
- References (advisories, fix commits, CVE records)

## Disclosure Policy

Vulnerabilities listed here were reported through responsible/coordinated
disclosure where a vendor or upstream project existed, or represent
independently analyzed and published CVE records (e.g., upstream kernel
fixes) that I've documented for reference.

## Contact

- GitHub: [@bohmiiidd](https://github.com/bohmiiidd)
- CVE writeups: [bohmiiiidd.kyubisec.com](https://bohmiiiidd.kyubisec.com/#/cve)
