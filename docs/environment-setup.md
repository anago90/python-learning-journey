# Python Environment Setup

Project: Tinker AI – Hands-On Development  
Workspace: C:\Users\agome\projects\tinker-work  
Python Version: 3.11.9  
Virtual Environment: .venv311

---

## Objective

Establish a reliable, repeatable Python development environment to support hands-on experimentation with Tinker and modular, AI-assisted application development.

---

## Environment Architecture

### Workspace

A project-scoped directory that contains all source code, configuration files, and documentation related to a single system.

- Purpose: Organize files and project artifacts
- Scope: Human-defined (Python itself is unaware of workspaces)
- Path used:  
  `C:\Users\agome\projects\tinker-work`

### Virtual Environment (venv)

An isolated Python runtime with its own interpreter and dependency set.

- Purpose: Prevent dependency and version conflicts across projects
- Contains:
  - python.exe
  - pip
  - Lib/site-packages
- Path used:  
  `C:\Users\agome\projects\tinker-work\.venv311`

**Key rule:** One workspace → one virtual environment

---

## Setup Process

### 1. Project Workspace Creation
- Created a dedicated `projects` directory under the user profile
- Created a project-specific folder: `tinker-work`

### 2. Virtual Environment Creation
- Created a Python 3.11 virtual environment inside the workspace
- Naming convention: `.venv311` (explicit Python version for clarity)

### 3. Interpreter Verification

```powershell
.\.venv311\Scripts\python.exe --version
# Python 3.11.9

.\.venv311\Scripts\python.exe -m pip --version
# pip 24.0 from ...\.venv311\Lib\site-packages\pip
