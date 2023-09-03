# CVE-2023-22809

**CVE-2023-22809** is a critical vulnerability that affects the popular sudo software, specifically the `sudoedit` command. This vulnerability allows an attacker to gain root privileges on a targeted system by exploiting a flaw present in the `sudoedit` command.

Exploiting the **CVE-2023-22809** vulnerability involves passing a specially crafted argument to the `sudoedit` command. This triggers the creation of a new file with root privileges. The attacker can then manipulate the content of this file, providing them with the ability to gain elevated privileges.

Key information about the **CVE-2023-22809** vulnerability includes:

- Severity: Critical
- Affected Product: sudo
- Affected Versions: 1.8.0 through 1.9.12.p1
- Patched Version: 1.9.12.p2
- Exploitability: Remote
- CVSS Score: 9.8

To execute the script that takes advantage of this vulnerability, use the following command:

```
python3 CVE-2023-22809.py
```

It is important to note that exploiting vulnerabilities without proper authorization is both illegal and unethical. This description is provided for educational and general awareness purposes only.
