<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="./assets/hero-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="./assets/hero-light.svg">
  <img alt="Calistus Christian, Security & AI Safety Leader" src="./assets/hero-dark.svg" width="100%">
</picture>

<br><br>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=0B0F17)](https://linkedin.com/in/calistuschristian)
[![n8n](https://img.shields.io/badge/n8n-Workflows-EA4B71?style=for-the-badge&logo=n8n&logoColor=white&labelColor=0B0F17)](https://n8n.io/creators/ca7ai/)

</div>

<br>

I lead security in regulated industries, from fintech and finance to big law: cloud security, AI governance, and incident response.

I build the tools below to pressure-test AI systems before they reach production, and to decide which controls are worth asking a team to adopt.

<img src="./assets/divider.svg" width="100%" alt="">

## How I Lead

**Measure before you mandate.** A control without a false-positive rate is a guess. My tools publish their miss rates, and I hold team proposals to the same bar.

**Prototype the control, then write the policy.** Standards land better when engineers have already seen the guardrail work on real traffic.

**Contain, don't just detect.** AI agents act faster than humans can triage. The default should be a blast radius, not an alert.

<img src="./assets/divider.svg" width="100%" alt="">

## Featured Work

<table>
<tr>
<td colspan="2"><sub><code>01 · AGENTIC CONTAINMENT</code></sub></td>
</tr>
<tr>
<td colspan="2" valign="top">

### [glasswall-sandbox](https://github.com/ca7ai/glasswall-sandbox)

Local-first sandbox for AI agents running untrusted terminal commands. Wraps each action in macOS `sandbox-exec` profiles or Docker, blocks data exfiltration, and logs every command and workspace change to a SQLite audit trail.

![Go](https://img.shields.io/badge/Go-0B0F17?style=flat-square&logo=go&logoColor=00ADD8)
![macOS](https://img.shields.io/badge/macOS-0B0F17?style=flat-square&logo=apple&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-0B0F17?style=flat-square&logo=docker&logoColor=2496ED)
![SQLite](https://img.shields.io/badge/SQLite-0B0F17?style=flat-square&logo=sqlite&logoColor=4FA3D1)

</td>
</tr>
<tr>
<td colspan="2"><sub><code>02 · AI RED TEAMING</code></sub></td>
</tr>
<tr>
<td width="50%" valign="top">

### [LLM-Vulnerability-Scanner](https://github.com/ca7ai/LLM-Vulnerability-Scanner)

Serverless red-teaming engine for AWS Bedrock. Scans hosted and fine-tuned models for vulnerabilities with no provisioned infrastructure.

![Python](https://img.shields.io/badge/Python-0B0F17?style=flat-square&logo=python&logoColor=FFD43B)
![AWS](https://img.shields.io/badge/AWS-0B0F17?style=flat-square&logo=amazonaws&logoColor=FF9900)

</td>
<td width="50%" valign="top">

### [RedTeam-Agent](https://github.com/ca7ai/RedTeam-Agent)

Autonomous multi-model red teaming. Attacker agents probe victim models to find safety failures before release.

![Python](https://img.shields.io/badge/Python-0B0F17?style=flat-square&logo=python&logoColor=FFD43B)

</td>
</tr>
<tr>
<td colspan="2"><sub><code>03 · AI DEFENSE</code></sub></td>
</tr>
<tr>
<td width="50%" valign="top">

### [jev-prompt-sentry](https://github.com/ca7ai/jev-prompt-sentry)

Ingress firewall for LLM APIs. Screens each request for jailbreaks, indirect injection, and exfiltration before the expensive model runs.

<sub>**0** false positives on 1,590 public-dataset rows · **9.1%** miss rate, published · **~$0.03** per 1K requests · **263 ms** p95</sub>

![Python](https://img.shields.io/badge/Python-0B0F17?style=flat-square&logo=python&logoColor=FFD43B)

</td>
<td width="50%" valign="top">

### [mcp-sec-scanner](https://github.com/ca7ai/mcp-sec-scanner)

Security scanner for Model Context Protocol servers. Static analysis, live probing for prompt injection in tool descriptions and path traversal, and DNSSEC-based server verification.

![Python](https://img.shields.io/badge/Python-0B0F17?style=flat-square&logo=python&logoColor=FFD43B)

</td>
</tr>
<tr>
<td colspan="2"><sub><code>04 · DECEPTION & THREAT INTEL</code></sub></td>
</tr>
<tr>
<td colspan="2" valign="top">

### [Mirage-HoneyPot](https://github.com/ca7ai/Mirage-HoneyPot)

Deception engine that turns token budgets against LLM-driven scrapers: it burns their context while fingerprinting each session. Captured telemetry feeds [Mirage-Sight](https://github.com/ca7ai/Mirage-Sight), which publishes daily and monthly threat-intel reports with ASN enrichment and structured IoCs.

![Python](https://img.shields.io/badge/Python-0B0F17?style=flat-square&logo=python&logoColor=FFD43B)
![AWS](https://img.shields.io/badge/AWS-0B0F17?style=flat-square&logo=amazonaws&logoColor=FF9900)

</td>
</tr>
</table>

<sub>More: [openclaw-audit](https://github.com/ca7ai/openclaw-audit) · [ImageWarden](https://github.com/ca7ai/ImageWarden) · [pp-virustotal](https://github.com/ca7ai/pp-virustotal) · [pp-shodan](https://github.com/ca7ai/pp-shodan)</sub>

<img src="./assets/divider.svg" width="100%" alt="">

## Scope

<table>
<tr>
<td width="50%" valign="top">

**👥 Leadership**

<sub>Building and growing security teams<br>Incident command<br>Security strategy and risk</sub>

</td>
<td width="50%" valign="top">

**🛡️ AI Security**

<sub>Model red teaming<br>Prompt injection defense<br>AI governance frameworks</sub>

</td>
</tr>
<tr>
<td width="50%" valign="top">

**☁️ Cloud Security**

<sub>AWS (Bedrock, Lambda, S3)<br>Infrastructure compliance<br>Serverless architectures</sub>

</td>
<td width="50%" valign="top">

**⚙️ Security Automation**

<sub>Python and Go tooling<br>Step Functions pipelines<br>n8n orchestration</sub>

</td>
</tr>
</table>
