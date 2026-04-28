# OSSP_Assignment
Windows 11 virtual machine project demonstrating OS concepts like virtualization and file systems.
Windows 11 Virtual Machine Installation and Operating System Concepts

Project Description

This is a demonstration of how to install Windows 11 on a virtual machine and understand some important concepts about operating systems. This project was carried out for academic purposes to learn more about operating systems, virtual machines, configuration settings, file system support, and basic system calls.



Objectives

- Learn how to install Windows 11 through virtualization tools
- Understand the configuration setting of a virtual machine
- Learn more about file system support in Windows 11
- Basic implementation of system calls in Windows 11
- Learn more about virtualization

System Specifications

Hardware Specification

- 64-bit processor (supporting virtualization)
- Minimum 8 GB RAM
- Minimum 50 GB disk space

Software Specifications

- Oracle VM VirtualBox
- Windows 11 ISO file

Procedure of Installation

1. Install Oracle VM VirtualBox
2. Setup of new virtual machine
3. Allocation of memory and disk space
4. Insert Windows 11 ISO file
5. Start virtual machine
6. Begin Windows 11 installation process

Important Concepts Discussed

Virtualization

Virtualization is the process of running several operating systems on one computer. This concept increases efficiency and aids in testing in isolated conditions.

File System Support

Windows 11 supports NTFS (New Technology File System), which offers:

- Increased security
- High reliability
- Large file support

Additionally, FAT32 and exFAT file systems are supported.

System Calls

System calls form a bridge between the application layer and the OS kernel. This project focuses on memory management topics like "mlock," which locks the memory in RAM.

---

Issues Encountered and Resolutions

- Problem: Virtual machine fails to boot up
Resolution: Enabled virtualization (VT-x/AMD-V) settings in BIOS

- Problem: Slow speed
Resolution: Increased RAM and number of CPUs

- Problem: Error during installation
Resolution: Checked ISO image integrity and compatibility

---

 Outcomes

- Successfully installed Windows 11 on a virtual machine
- Learned about virtualization and system configuration
- Acquired knowledge on file systems and system calls

---

Recommendations for the Future

- Study other virtualization software (like VMware)
- Apply other concepts in systems programming
- Conduct performance comparison of host and virtual machines
- Improve security settings

---

Bibliography

- Official Microsoft Documentation
- Oracle VM VirtualBox User Manual
- Operating System textbooks
