<div align="center">
  <img src="https://thedfirreport.com/wp-content/uploads/2020/04/cropped-dfir-v1-w.png" width="200" alt="DFIR Report Logo">
</div>

# DFIR Training Artifacts

## Overview
This repository serves as a platform for sharing simulated intrusion artifacts used in our analyst recruitment process. Unlike real-world intrusions that we analyze on a daily basis at the DFIR Report, these artifacts are specifically created for training and evaluation purposes.

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
We are looking for passionate individuals who can:
- Analyze the provided artifacts thoroughly
- Submit a detailed report following our analysis style
- Demonstrate strong analytical and technical writing skills
- Show potential for growth within our team

> **Position Details:** This position starts as a volunteer role. Successful candidates may be offered opportunities for paid work on an ad hoc basis, depending on team needs and project availability. The transition to paid work is based on performance, reliability, and the specific needs of our ongoing investigations.

---

## Accessing Artifacts
The repository provides two ways to access the artifacts:

1. **Parsed Documents**: Pre-processed artifacts are available in the [GitHub Releases](../../releases) section of this repository.

2. **Complete Dataset**: For analysts who wish to work with all available data, we provide access through our MEGA repository.

| Simulated Case | Complete Dataset (Google Drive) | Alternative (Mega) |
|----------------|------------------------|---------------------------|
| Simulated-Case-1 | [Download (Gdrive)](https://drive.google.com/file/d/1tpIUu4_uVQ2W_vnzzJjA3aLUhlQpS75k/view?usp=sharing) | [Download (MEGA)](https://mega.nz/file/IJhl0QgD#uQwoeFjIiLHwL16AS_fxPCX3XZKN8oTso6qiH_K307M)

### Available Artifacts

| Category | GitHub Release Contains | Complete Dataset Contains |
|----------|-------------|-------------|
| 🗂️ Logs | • Parsed Kape sandbox analysis logs<br>• Kape system logs (CSV format)<br>• Windows Event Logs (Elastic export in JSON format) from all affected hosts - ready for Elastic import | All GitHub Release logs plus:<br>• Raw system logs<br>• Additional parsed logs<br>• Complete log datasets |
| 💾 Memory | - | Memory dumps from affected systems |
| 📁 Files | - | Relevant malicious files |
| 🌐 Network | - | Network captures and sensor data |

> **Elastic Import Note:** The Windows Event Logs in the GitHub Release are provided in JSON format. This makes it easy to import them into your Elastic instance for analysis using the same tools and visualizations you're familiar with.

| ⚠️ Password for All Compressed Files |
|:-----------------------------------:|
| **Password:** `infected` |
| **Note:** All password-related inquiries will be ignored |

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
