# AtomicRedTeam-Computer-Forensic-Report
 
## Introduction

- Created a Computer Forensic Report based off of IEUser account. 
- Malicious executable that was affecting the user account was AtomicService and MavinInject executables.
- The Computer Forensic Report focuses:
  - Executive Summary
  - Artifacts
  - Malicious Files
  - Timeline of Attack
  - Improvements

## Thought Process

- Hash the Vhdx and memory file for integrity purposes.
- Hash the malicious files AtomicRedTeam and MavinInject Executables.
- Perform Computer Forensic Using Open Source Tools.
- Use Arsenal Image Mounter Mount Vhdx File.
- Kape obtain artifacts of Mounted Image.
- Eric ZimmerMan Tools to find timeline information about the artifacts.
- volatility memory forensics

## What I Learned

- How to use Arsenal Image Mounter to mount a Vhdx File on your operating system(Enumeration).
- Using Kape to obtain artifacts from Drives(Arsenal Image Mounter).
- How to use volitility 3.

## Mark

- Extra Curricular.
