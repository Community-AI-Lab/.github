# Security Policy

Community AI Lab is an early-stage, community-built AI research project. We take security reports seriously.

## Reporting a vulnerability

**Do not open a public GitHub issue with vulnerability details, credentials, private recordings, personal information or exploit instructions.**

Please use GitHub's **Report a vulnerability** feature from the relevant repository's **Security → Advisories** tab when private vulnerability reporting is enabled:

- [Contributor Platform security advisories](https://github.com/Community-AI-Lab/platform/security/advisories)
- [Speech-to-Speech Model security advisories](https://github.com/Community-AI-Lab/speech-to-speech/security/advisories)

If the **Report a vulnerability** option is not visible, private reporting has not yet been enabled. Please ask a repository maintainer to arrange a private contact method **without sharing sensitive details in public**. The organisation should enable private vulnerability reporting in both repositories before inviting general security reports.

Please include a concise description, affected component, how to reproduce the issue safely, and potential impact. Do not test against other users or expose their data.

## Supported releases

The repositories are at the research/prototype stage; there is no published supported release or security-fix service-level commitment yet. We will update this section when software is released.

## Basic precautions for contributors

- Never commit passwords, API keys, GitHub tokens or Hugging Face tokens. Use GitHub Actions secrets or a proper secret manager when needed.
- Never upload private customer audio, consent records, user-identifying information or confidential datasets to public repositories.
- Review third-party dependencies, model weights and datasets for security and licence risks.
- Treat downloaded model files, training scripts and contributions from unknown sources as untrusted.
- Use pull requests and review changes before merging.

Security-related reports should be investigated privately and coordinated with affected contributors or providers before disclosure.
