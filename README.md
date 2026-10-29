# Edward Griggs

**Security Operations & Detection Engineering | AI Security Researcher**

Security+ certified analyst who defends a federal GovCon Microsoft 365 environment and builds the detections that catch attacks against it. I pair hands-on security operations (incident response, identity governance, NIST SP 800-171 compliance) with detection engineering in Microsoft Sentinel, and published AI security research on prompt injection and LLM defenses. I also build AI tools that keep a human in the loop and refuse to make things up.

Currently building out my detection portfolio and studying for SC-200.

### Detection engineering portfolio

Four repositories that cover the full lifecycle of a detection, from written rule to a closed case.

- **[detection-engineering](https://github.com/edwardjgriggs/detection-engineering)** Tuned KQL detections for Microsoft Sentinel and Defender, each mapped to MITRE ATT&CK with threat context, false-positive notes, and validation steps.
- **[soc-detection-lab](https://github.com/edwardjgriggs/soc-detection-lab)** The self-built Sentinel and Wazuh lab where every detection is validated against real telemetry before I trust it.
- **[detection-as-code](https://github.com/edwardjgriggs/detection-as-code)** Version-controlled Sigma rules with a CI pipeline that validates and converts them to KQL on every commit.
- **[soc-casebook](https://github.com/edwardjgriggs/soc-casebook)** AI first-pass triage with a human in the loop. The model recommends, a named analyst approves or rejects every containment action, and every alert ends in a written case file.

Write the detection, prove it in the lab, automate the delivery, own the decision. That is the loop.

### AI security research

**[Hijacking the Prompt: A Survey of Prompt Injection Attacks, Detection, and Defense in LLMs](https://digitalcommons.odu.edu/covacci-undergraduateresearch/2026spring/projects/9/)**
Published through ODU Digital Commons. Includes a Python/Flask proof-of-concept classifier matching 13 injection signatures to a six-category taxonomy, validated by 83 passing pytest tests. Survey, interactive demo, and conference presentation live in **[prompt-injection-research](https://github.com/edwardjgriggs/prompt-injection-research)**.

### Things I've built

**Security and compliance**
- **[widedoor](https://github.com/edwardjgriggs/widedoor)** Open source accessibility checker for websites and PDFs against Section 508 and WCAG 2.1 AA. Plain-language findings, and ACR output in OpenACR and the VPAT 2.5 Section 508 layout.
- **[ttb-label-checker](https://github.com/edwardjgriggs/ttb-label-checker)** Batch alcohol label review. GPT-4o vision reads the label, a deterministic TypeScript rules engine judges every TTB check. The AI reads; code judges.
- **[vault-7](https://github.com/edwardjgriggs/vault-7)** Team Lead and Lead Developer for a four-person, browser-based security training game with mission-style scenarios on phishing, passwords, and defensive decisions. Winning project in the COVA CCI Design Cohort.

**Human-in-the-loop AI**
- **[careerforge](https://github.com/edwardjgriggs/careerforge)** Local-first evidence engine that turns Git commits and AI coding sessions into resume bullets and STAR stories where every claim cites its source. Claims the evidence cannot carry are removed, not softened.
- **[flight-sentry](https://github.com/edwardjgriggs/flight-sentry)** Mission assurance for spacecraft telemetry using trusted context and IBM Granite, with a human making the final call.
- **[selvedge](https://github.com/edwardjgriggs/selvedge)** An AI that defends your voice instead of averaging it away. Built for the IBM SkillsBuild AI Builders Challenge, July 2026.

**AI developer tools**
- **[prompt-lathe](https://github.com/edwardjgriggs/prompt-lathe)** Shapes a raw prompt to a specific model, environment, and task. Desktop, CLI, and web share one local rules engine, with no telemetry.
- **[skill-forge](https://github.com/edwardjgriggs/skill-forge)** Create, validate, and publish agent skills for Claude, Grok, Cursor, and others.
- **[SayLine](https://github.com/edwardjgriggs/SayLine)** Private, offline voice dictation for Windows. Hold a shortcut, speak, and local Whisper transcription types into any app. No account, no API key.

**Apps and games**
- **[PromptLab](https://github.com/edwardjgriggs/PromptLab)** iOS app that teaches better prompting through guided questions, lessons, and a built-in coach.
- **[PacketGlide](https://github.com/edwardjgriggs/packetglide-showcase)** One-tap arcade game for iPhone, built with Godot. Free on the App Store.

### What I work on

**Security operations and compliance**
Incident and phishing response, Microsoft Defender, Entra ID, Intune, and Purview DLP across a 50+ user GovCon environment. Primary author behind a perfect 110/110 NIST SP 800-171 SPRS score, with the organization at CMMC Level 1 today and actively preparing for Level 2. Raised Microsoft Secure Score from 54.5% to 83.6% across 30+ endpoints.

**Security automation**
PowerShell, Python, Power Automate, and the Microsoft Graph API to automate identity lifecycle and IT operations, recovering 1,200+ staff-hours per year.

**AI governance**
Authoring enterprise AI use policies and advising on safe, accountable AI adoption.

### Core skills

`Security Operations` · `Detection Engineering` · `Microsoft Sentinel` · `KQL` · `Sigma` · `MITRE ATT&CK` · `Wazuh` · `Detection as Code` · `Incident Response` · `Microsoft Defender` · `Entra ID` · `Intune` · `Purview DLP` · `Conditional Access` · `NIST SP 800-171` · `CMMC (L1 today, L2 in prep)` · `Section 508 / WCAG 2.1` · `PowerShell` · `Python` · `TypeScript` · `C# / .NET` · `Swift` · `Microsoft Graph API` · `Prompt Injection Defense` · `LLM Security` · `Human-in-the-Loop AI`

### Certifications

- CompTIA Security+ (SY0-701), 2026
- Google Cybersecurity Professional Certificate (V2), 2025
- Google AI Professional Certificate, 2025
- IBM Generative AI Essentials for Cybersecurity, 2025
- Microsoft SC-200: Security Operations Analyst (in progress)

### Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-edward--griggs-0A66C2?style=flat&logo=linkedin)](https://linkedin.com/in/edward-griggs/)
[![Website](https://img.shields.io/badge/Website-edwardgriggs.com-111?style=flat&logo=safari)](https://edwardgriggs.com)
[![Email](https://img.shields.io/badge/Email-edwardjgriggs@gmail.com-EA4335?style=flat&logo=gmail)](mailto:edwardjgriggs@gmail.com)
