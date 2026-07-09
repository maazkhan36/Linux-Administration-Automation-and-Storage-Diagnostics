# Linux-Administration-Automation-and-Storage-Diagnostics

📌 Project Overview
This repository contains a technical overview of a hands-on Linux systems administration project. The work focuses on two core pillars: system automation through custom shell scripting and infrastructure diagnostics through non-destructive system auditing.

The entire project was developed and executed within a controlled Ubuntu Linux virtual machine environment, focusing on safe, read-only analytical practices.

🎯 Key Objectives
1. Automation & System Guardrails
Developed modular Bash scripts to automate environmental profiling and system greetings using runtime variables.

Implemented strict defensive programming practices, including input sanitization and parameter validation to prevent blank strings or path-traversal vulnerabilities.

2. System Profiling & Data Mapping
Conducted a non-invasive baseline inventory of system hardware components (CPU architecture, memory allocation, and block storage devices).

Mapped critical Linux data categories, analyzing the operational boundaries between persistent filesystems (such as user environments and configuration logs) and volatile, temporary runtime spaces.

3. Storage Architecture & Analysis
Audited filesystem capacities and mapped the structural relationship between virtual block devices and underlying mount points.

Investigated workspace disk consumption to isolate high-volume storage consumers and formulated an evidence-based optimization and remediation strategy.

🛠️ Skills & Competencies Demonstrated
Defensive Shell Scripting: Input validation, positional parameters, error handling, and iterative automation loops.

System Auditing: Non-destructive hardware profiling, environmental security controls, and permission management (chmod).

Storage & Resource Management: Block device topology tracking, filesystem health verification, and proactive capacity planning.
