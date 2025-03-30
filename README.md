<div align="center">
  <img src="https://thedfirreport.com/wp-content/uploads/2020/04/cropped-dfir-v1-w.png" width="200" alt="DFIR Report Logo">
</div>

# DFIR Training Artifacts

## Overview
This repository serves as a platform for sharing simulated intrusion artifacts used in our analyst recruitment process. Unlike real-world intrusions that we analyze on a daily basis at the DFIR Report, these artifacts are specifically created for training and evaluation purposes.

### Repository Goals
- Provide the DFIR community with a glimpse into the types of artifacts we collect and analyze in real-world intrusions
- Offer a free resource for individuals to develop and enhance their digital forensics and incident response skills
- Give back to the community by sharing knowledge and practical examples
- Enable self-paced learning and skill development in a controlled environment

## Application Process
When a position has a green status indicator (🟢) and an active JotForm link, it indicates that we are actively seeking analyst candidates.

---

### Current Open Position 🟢

| | |
|:---:|:---|
| **Case** | Simulated-Case-1 |
| **Position** | Volunteer Analyst with Opportunities for Ad Hoc Paid Work |
| **Status** | 🟢 Currently Open |
| **Apply** | [Submit Your Analysis](https://form.jotform.com/250847594571266) |
| **Deadline** | Submissions close April 20, 2025 at 23:59 UTC |

### Requirements
We are looking for talented individuals who can:
- Analyze the provided artifacts thoroughly
- Submit a detailed report following our analysis style
- Demonstrate strong analytical and technical writing skills
- Show potential for growth within our team

> **Position Details:** This position starts as a volunteer role. Successful candidates may be offered opportunities for paid work on an ad hoc basis, depending on team needs and project availability. The transition to paid work is based on performance, reliability, and the specific needs of our ongoing investigations.

---

## Repository Organization
The artifacts for each simulated intrusion case are distributed through GitHub Releases. Each release contains:
- A set of parsed logs and artifacts ready for analysis
- Detailed release notes describing the included files
- Version information and any relevant updates

You can find all available cases in the [Releases](../../releases/tag/case-1) section of this repository.

## Accessing Artifacts
The repository provides two ways to access the artifacts:

1. **Parsed Documents**: Pre-processed artifacts are available in the [GitHub Releases](../../releases) section of this repository. These include:
   - Parsed Kape analysis logs
   - Kape system logs in CSV format
   - Windows Event Logs from all affected hosts in JSON format (exported from Elastic and ready for re-import)

2. **Complete Dataset**: For analysts who wish to work with all available data, we provide access through our MEGA repository. This includes all the above plus:
   + Full PCAP
   + Memory Dumps

| Simulated Case | Complete Dataset (MEGA) |
|----------------|-----------|
| Simulated-Case-1 | [Download](https://mega.nz/file/IJhl0QgD#uQwoeFjIiLHwL16AS_fxPCX3XZKN8oTso6qiH_K307M) |

### Available Artifacts

| Category | GitHub Release Contains | Complete Dataset (MEGA) Contains |
|----------|-------------|-------------|
| 🗂️ Logs | • Parsed Kape sandbox analysis logs<br>• Kape system logs (CSV format)<br>• Windows Event Logs (Elastic export in JSON format) from all affected hosts - ready for Elastic import | All GitHub Release logs plus:<br>• Raw system logs<br>• Additional parsed logs<br>• Complete log datasets |
| 💾 Memory | - | Memory dumps from affected systems |
| 📁 Files | - | Relevant malicious files |
| 🌐 Network | - | Network captures and sensor data |

> **Elastic Import Note:** The Windows Event Logs in the GitHub Release are provided in JSON format. This makes it easy to import them back into your own Elastic deployment for analysis using the same tools and visualizations you're familiar with.

| ⚠️ Password for All Compressed Files |
|:-----------------------------------:|
| **Password:** `infected` |
| **Note:** All password-related inquiries will be ignored |

## About the Artifacts
The artifacts in this repository have been pre-parsed and organized for easy access. They represent simulated intrusion scenarios that we use to evaluate potential analysts' capabilities in:
- Digital Forensics
- Incident Response
- Artifact Analysis
- Evidence Processing

These simulated cases are designed to provide a controlled environment for testing and demonstrating analytical skills without exposing sensitive real-world data. Whether you're an aspiring analyst, a student, or a professional looking to enhance your skills, these artifacts provide a valuable opportunity to practice and learn in a safe, controlled environment.

## ⚠️ Important Safety Notice

> **Warning:** While these artifacts are from simulated intrusions, they should be treated and analyzed with the same precautions as real malicious artifacts:
> - We are not responsible for any system compromise resulting from improper handling of these artifacts
> - Always analyze these artifacts in isolated, protected environments
> - Use dedicated analysis VMs or sandboxed environments
> - Treat all artifacts as potentially malicious, even though they are from simulated scenarios
> - Follow proper DFIR safety protocols and best practices when handling the artifacts

## 📜 License

This repository and its contents are Copyright © 2025 The DFIR Report. All Rights Reserved.

These artifacts are provided for educational and evaluation purposes only. Any use requires explicit written permission from The DFIR Report. See the [LICENSE](LICENSE) file for detailed terms.
