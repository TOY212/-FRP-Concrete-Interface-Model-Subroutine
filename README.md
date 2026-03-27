# FRP-Concrete Interface Model Subroutine (FRP混凝土界面模型子程序) 🏗️

![Version](https://img.shields.io/badge/Version-1.0-blue.svg)
![Platform](https://img.shields.io/badge/Platform-Windows%20%7C%20Linux-lightgrey.svg)
![FEA](https://img.shields.io/badge/FEA-Abaqus-red.svg)

> **[English](#english-version)** | **[中文说明](#中文版说明)**

---

## English Version

### 📖 Introduction
This repository provides a compiled user subroutine for modeling the complex interfacial bond-slip behavior between Fiber-Reinforced Polymer (FRP) and concrete. This subroutine is specifically developed for finite element analysis (FEA) and captures the critical debonding mechanics under various loading conditions.

*(Note: To protect intellectual property pending publication, the raw source code (Fortran) is not publicly available at this time. We provide the compiled subroutine files and an example input file for researchers to apply and test the model.)*

### 📥 Download & Usage
1. Navigate to the **[Releases](../../releases)** page.
2. Download the `.zip` package containing the compiled subroutine file (e.g., `.obj` or `.dll`) and the example `.inp` test file.
3. Extract the files to your FEA working directory.
4. Call the subroutine during your job submission. For example, in Abaqus command line:
   ```bash
   abaqus job=your_model user=FRP_Interface_Subroutine.obj
