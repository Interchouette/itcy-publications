Post ID: POST-20261125-000329

When two versions of @microsoft's Agent Framework hit PyPI and instantly started siphoning secrets, it felt less like a release and more like a trap snapping shut in real time. 📜

Versions 1.26.1 and 1.26.2 arrived on November 17th carrying Python `.pth` hooks that executed the moment any interpreter launched, no import required, no warning given. Once active, these payloads reached for environment variables, local configs, and fresh tokens from Azure, GitHub Actions, AWS, Docker, and Hugging Face before compressing everything into base64 blobs for a webhook.site endpoint. 🦉

The irony is thick enough to build a pipeline on: a tool designed to streamline agent workflows was weaponized to harvest the very credentials needed to keep systems running. Developers who pulled the latest updates expected a refactor of logic, not a rewrite of their own access keys. The quarantine happened around 21:30 UTC that same day, but by then, the data had already left the building or been sitting in an attacker-controlled bucket waiting for a command. 🤖

If you've touched these versions on your machine or pushed them into a CI/CD flow, rebuilding isn't enough, you need to rotate every token and verify which scripts ran without explicit imports. The good news is version 1.26.0 remains clean, serving as the last known anchor before the supply chain was poisoned. 🦉

https://www.infoworld.com/article/4250167/attackers-hijack-microsofts-agent-framework-package-to-steal-azure-and-ci-credentials-2.html

Link: 1
0 = no link. /change_url DRAFT-20261125-000329 <0|1|2|3|4|5|url>
1. https://www.infoworld.com/article/4250167/attackers-hijack-microsofts-agent-framework-package-to-steal-azure-and-ci-credentials-2.html
2. https://us.resources.infoworld.com
3. https://www.techrepublic.com/article/news-microsoft-agent-framework-pypi-credential-theft
4. https://www.bleepingcomputer.com/news/security/microsofts-agent-framework-pypi-package-compromised-to-steal-credentials
5. https://www.msn.com/en-xl/news/other/microsoft-agent-framework-compromised-on-pypi-in-major-supply-chain-attack/ar-AA2hLyLH

Written by AI - ITCy - model ollama/qwen3.5:9b - tokens in:16495 out:340