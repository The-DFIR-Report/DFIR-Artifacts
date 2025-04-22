<div align="center">
  <img src="https://thedfirreport.com/wp-content/uploads/2020/04/cropped-dfir-v1-w.png" width="200" alt="DFIR Report Logo">
</div>

### Position Details
Passionate about Digital Forensics and Incident Response? Want to share your expertise with the security community while collaborating with talented analysts worldwide?

We're looking for volunteer analysts to join the team! We dive deep into real-world threats and publish monthly public reports detailing threat actor TTPs and how they achieve their goals.

As part of the team, you will:

- Analyze intrusion data and contribute to impactful DFIR reports.
- Help shape how we share findings 📄🎨
- Collaborate with and learn from amazing analysts across the globe.
- Access our internal group to ask questions, share insights, and improve processes. 🧠
- Have the unique opportunity to present our collective findings at security conferences and talks! 🎤

This position is a volunteer role. Successful candidates may be offered opportunities for paid work on an ad hoc basis, depending on team needs and project availability.

---

### Requirements

- Analyze the provided artifacts thoroughly
- Submit a detailed report following our analysis style
- Demonstrate strong analytical and technical writing skills
- Show potential for growth within our team

---

### Current Open Position 🔴

| | |
|:---:|:---|
| **Case** | Simulated-Case-1 |
| **Position** | Volunteer Analyst with Opportunities for Ad Hoc Paid Work |
| **Status** | 🔴 Currently Closed |
| **Apply** | - |
| **Deadline** | - |

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
