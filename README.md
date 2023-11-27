<p align="center">
  <img src="https://user-images.githubusercontent.com/57866415/135939695-6f2c2ce7-403b-4aab-977f-561d17be73ce.png" />
</p>

<div align="center">

# PMAT Labs Notes by Enzo Saez - @hashp4 🔬


This repository contains my personal notes and answers to the challenges from the Practical Malware Analysis & Triage course created by [@HuskyHacks](https://github.com/HuskyHacks). This is mainly for everyone following the course or just for people interested by the topic. Feel free to take a look. (:

> https://github.com/HuskyHacks/PMAT-labs

</div>

## 🧭 Repository Structure

The structure of this repository maps to the course videos. The top directory contains the name of the section. My notes will be under the `Course Notes` folder. For challenges, there will be my malware analysis report (named *Report.md*) and its PDF version (*Report.pdf*) For example:
```
📦PMAT-Labs-Notes
 ┣ 📜README.md
 ┣ 📂Course Notes
 ┃ ┗ 📜Notes.md
 ┣ 📂1-3.Challenge-SillyPutty
 ┃ ┣ 📂img
 ┃ ┣ 📜Report.md
 ┃ ┗ 📜Report.pdf
 ┃ 📂...
...
```

---

## 🚩 Course Completion Status

- [X] 0-1.HandlingAndSafety
- [X] 1-1.BasicStaticAnalysis
- [X] 1-2.BasicDynamicAnalysis
- [X] 1-3.Challenge-SillyPutty
- [X] 2-1.AdvancedStaticAnalysis
- [X] 2-2.AdvancedDynamicAnalysis
- [X] 2-3.Challenge-SikoMode
- [X] 2-4.BinaryPatching/SimplePatchMe
- [X] 2-5.AntiAnalysis/1.simpleAntiAnalysis
- [X] 3-1.GonePhishing-MaldocAnalysis
- [X] 3-2.WhatTheShell-ShellcodeAnalysis
- [X] 3-3.OffScript-ScriptMalware
- [X] 3-4.StaySharp-CSharpMalware
- [X] 3-5.GoTime-GoMalware
- [X] 3-6.Mobile-Malware/Android
- [X] 4-1.Bossfight-wannacry.exe
- [X] 5-1.Automation
- [X] 5-2.RuleWriting
- [X] 5-3.ReportWriting
- [X] 6-1.CourseFinal
- [X] 6-2.CourseConclusion

---

## Learning Objectives

The following bulleted items are this course's Learning Objectives. It is split into two categories: **Conceptual Learning Objectives** (*what to understand*) and **Skill-based Learning Objectives** (*what to perform*).

### Conceptual Learning Objectives
```
- Explain the high-level malware analysis methodology.
- Explain safe malware handling and detonation procedures.
- Explain the importance of snapshots during malware analysis.
- Describe a high-level overview of a malware analysis lab network
- Identify safe sources for malware samples.
- Describe how the MITRE ATT&CK Framework informs malware analysis.
- Explain the differences between static and dynamic analysis.
- Explain the differences between basic and advanced analysis.
- Describe the differences between network indicators of compromise and host-based indicators of compromise.
- Explain the function of the IAT in a windows PE.
- Explain how the Windows API functions in a Windows PE.
- Explain the differences between high level languages and low level languages as they relate to malware analysis.
- Explain how decompilers & dissassemblers work.
- Explain the differences between source code, machine code, and assembly code.
- Describe the steps of a simple process injector at the Assembly and Windows API level.
- Explain the difference in .NET compiled binaries and Windows Portable Executables in relation to reverse engineering.
- Explain the differences in analysis & handling of different malware classes, i.e. maldocs, malscripts, PEs, DLLs, and process injectors.
- Explain how WMI can be used by malware.
```

### Skill-based Learning Objectives
```
- Create a local malware analysis lab with FLARE-VM and REMnux.
- Implement proper malware analysis network safety with segmentation of the malware analysis lab via Host Only or Internal networking.
- Implement internet simulation with INetSim within an isolated malware analysis lab network.
- Implement VM snapshots for safety and consistency during analysis.
- Handle malware from source to sink with an emphasis on safety.
- Perform controlled, safe malware detonation in a lab environment.
- Perform basic static analysis on Windows PEs, including: file hashing, analyzing PE strings, analyzing the Import Address Table, analyzing triage information with Capa, identifying and unpacking UPX packed malware.
- Match MITRE ATT&CK matrix items to malware capabilities.
- Perform basic dynamic analysis on Windows PEs, including: detonating and recording initial triage notes, examining network indicators of compromise with Wireshark, examining host-based indicators with Procmon, correlating network and host-based indicators of compromise between tools, analyzing the parent-child process relationships of malware programs.
- Perform advanced static analysis on Windows PEs, including: dissassembly & decompilation with Cutter, analyzing and interpreting i386 and AMD64 Assembly instructions, and analyzing a shellcode process injector at the Assembly level.
- Perform advanced dynamic analysis on Windows PEs, including: controlling flow of a program in a debugger, executing instructions, setting breakpoints, and patching instructions to alter program flow.
- Perform binary patching to alter the execution flow of a malware program.
- Identify and defeat anti-analysis techniques.
- Use Cyber Chef to transform data and decode a payload.
- Analyze malicious Microsoft Office documents.
- Analyze shellcode to determine its function.
- Analyze obfuscated PowerShell scripts.
- Analyze obfuscated VBScript.
- Analyze HTML Application files.
- Reverse-engineer a compiled .NET binary with dnSpy.
- Identify language patterns in compiled binaries
- Perform static analysis on an APK file with MobSF
- Combine all analysis methodologies and analyze a real world ransomware sample.
- Perform automated analysis with scripts and malware sandboxes.
- Compose YARA rules that identify malware program.
- Write & publish a malware analysis report.
```

---

## 🔗 Socials
If you'd like to reach out, please do not hesitate to hit me up ! 

Twitter : [@hashp4_](https://twitter.com/hashp4_)

Website : https://hashp4.fr/

---

### ❤️ Credits

This README is greatly inspired by [Frog Man (@deFr0ggy)](https://github.com/deFr0ggy). Do not hesitate to have a look at his work! 

---
