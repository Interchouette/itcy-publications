Post ID: POST-20261017-000229

📜 AhsayCBS, the server-side backbone of Ahsay’s backup suite, is under siege via two critical vulnerabilities, CVE-2026-105133 and CVE-2026-105134. These flaws, now actively exploited in the wild, allow attackers to bypass authentication and inject OS commands, leading to unauthenticated remote code execution with SYSTEM privileges. 🦉

The chain of exploitation is both sophisticated and dangerous: threat actors deploy webshells and disguise malicious payloads as Microsoft Edge, leveraging the compromised backup server to mine Monero. 🦀

Ahsay initially released v10.3.4.0 as a fix, but independent analysis revealed it was still vulnerable. The real solution came with v10.3.4.45 (October 10) and v9.15.2.70 (October 12). These patches close the loopholes, but the lesson is clear: even with updates, exposure to the internet can turn a server into a target. 🔧

Organizations must act swiftly, apply the hotfixes and restrict access to the management interface. The cost of inaction is not just data loss but the risk of being part of a global attack vector. Stay sharp, stay secure, and never underestimate the power of a backup server. 🚀

https://www.bitdefender.com/en-us/blog/businessinsights/technical-advisory-ahsaycbs-exploitation-chain-cve-2026-105133-cve-2026-105134

Link: 1
0 = no link. /change_url DRAFT-20261017-000229 <0|1|2|3|4|5|url>
1. https://www.bitdefender.com/en-us/blog/businessinsights/technical-advisory-ahsaycbs-exploitation-chain-cve-2026-105133-cve-2026-105134
2. https://securityarsenal.com/blog/cve-2026-105133-and-cve-2026-105134-unpatched-ahsaycbs-auth-bypass-and-command-injection-under-active-exploitation-defensive-playbook
3. https://windowsforum.com/news/ahsaycbs-cve-2026-105133-and-cve-2026-105134-exploited-version-10-3-4-still-vulnerable.447783
4. https://www.huntress.com/blog/ahsaycbs-flaws-exploit
5. https://www.anthonybahn.com/news/ahsaycbs-cve-2026-105133-105134-exploited-backup-server-rce

Written by AI - ITCy - model ollama/qwen3:8b - tokens in:6146 out:312