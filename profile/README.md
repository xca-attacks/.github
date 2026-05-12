<div align="center">

# XCA: Interconnect Corruption Attacks

[![Website](https://img.shields.io/badge/Website-xca--attacks.github.io-blue?style=for-the-badge)](https://xca-attacks.github.io)
[![Build Status](https://img.shields.io/github/actions/workflow/status/xca-attacks/xca-attacks.github.io/build-and-commit-gh-pages.yml?branch=main&style=for-the-badge)](https://github.com/xca-attacks/xca-attacks.github.io/actions)

<img src="https://xca-attacks.github.io/preview.png" width="800px" style="border-radius: 10px; margin: 20px 0;">

</div>

---

## 🔍 Overview

**XCA (Interconnect Corruption Attacks)** is a family of attacks that tampers with SoC interconnects to break Trusted Execution Environments (TEEs). 

---

## 🚀 The Attacks

<table align="center" border="0">
  <tr>
    <td align="center" width="50%" style="vertical-align: top;">
      <img src="https://xca-attacks.github.io/Fabricked-symbol.svg" width="220px"><br>
      <h3><b>Fabricked</b></h3>
      <p><i>Misconfiguring Infinity Fabric to Break AMD SEV-SNP</i></p>
      <p><b>USENIX Security 2026</b></p>
      <a href="https://xca-attacks.github.io/fabricked/fabricked_usenix26.pdf">📄 Paper</a> | <a href="https://github.com/fabricked-attack/">💻 Code</a>
    </td>
    <td align="center" width="50%" style="vertical-align: top;">
      <img src="https://xca-attacks.github.io/BreakFast-symbol.svg" width="220px"><br>
      <h3><b>BreakFAST</b></h3>
      <p><i>Confused Deputy Attack on Infinity Fabric to Break AMD SEV-SNP</i></p>
      <p><b>IEEE S&P 2026</b></p>
      <a href="https://xca-attacks.github.io/breakfast/breakfast_oakland26.pdf">📄 Paper</a>
    </td>
  </tr>
</table>

---

## 🛡️ Responsible Disclosure & CVEs

We have worked closely with AMD to address these vulnerabilities.

- **BreakFAST**: Assigned **CVE-2025-61971** and **CVE-2025-61972**. [AMD Advisory (AMD-SB-3030)](https://www.amd.com/en/resources/product-security/bulletin/amd-sb-3030.html)
- **Fabricked**: Assigned **CVE-2025-54510**. [AMD Advisory (AMD-SB-3034)](https://www.amd.com/en/resources/product-security/bulletin/amd-sb-3034.html)

---

## 🎓 Research Group

This research is conducted by the **Secure and Trustworthy Systems Group** at **ETH Zurich**.

For more technical details visit our project website:  
👉 [**xca-attacks.github.io**](https://xca-attacks.github.io)

### Citation

```bibtex
@inproceedings{schlueter2026fabricked,
  title={{Fabricked: Misconfiguring Infinity Fabric to Break AMD SEV-SNP}},
  author={Benedict Schlüter and Christoph Wech and Shweta Shinde},
  booktitle={35th USENIX Security Symposium (USENIX Security 26)},
  year={2026},
  month = aug,
  address = {Baltimore, MD},
  publisher = {USENIX Association},
}

@inproceedings{giersfeld2026breakfast,
  title={{BreakFAST: Confused Deputy Attack on Infinity Fabric to Break AMD SEV-SNP}},
  author={Philipp Giersfeld and Benedict Schl\"uter and Shweta Shinde},
  booktitle={47th IEEE Symposium on Security and Privacy (S\&P 26)},
  year={2026},
  month = may,
  address = {San Francisco, CA},
  publisher = {IEEE},
}
```
