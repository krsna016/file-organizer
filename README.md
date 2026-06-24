# c1-file-organizer

[![Language: Python](https://img.shields.io/badge/language-Python-blue.svg)]()
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![CI Pipeline](https://github.com/krsna016/c1-file-organizer/actions/workflows/ci.yml/badge.svg)](https://github.com/krsna016/c1-file-organizer/actions/workflows/ci.yml)
[![Security: CodeQL](https://github.com/krsna016/c1-file-organizer/actions/workflows/codeql.yml/badge.svg)](https://github.com/krsna016/c1-file-organizer/actions/workflows/codeql.yml)

Professional engineering repository configurations deployed inside your GitHub profile.

---

## Overview & Core Description

Effortlessly organize your files with this Python-based File Organizer. The project comes with a graphical user interface (GUI) built using Tkinter, making file management intuitive and efficient.

## Overview

File Organizer simplifies the task of arranging files within a specified directory. It intelligently categorizes files based on types, including images, documents, videos, and others. The use of Tkinter ensures a seamless and user-friendly experience.

## Features

- **Automatic File Categorization**: Files are grouped into folders based on their types, such as Images, Documents, Videos, and Others.
- **Intuitive User Interface**: Tkinter provides a responsive GUI, making navigation and interaction straightforward.
- **Custom Categorization Algorithms**: The project includes custom algorithms for efficient file organization.
- **Responsive Design**: The application is designed to adapt to different screen sizes, providing an enhanced user experience.

## Project Structure

- `main/Main.py`: The main Python script containing the file organizer implementation with Tkinter.

## Usage

1. **Run the `Main.py` Script:**
   - Execute the `Main.py` script to launch the application.

2. **Select Target Directory:**
   - Choose the directory you want to organize.

3. **Initiate Organization:**
   - Click the "Organize Files" button to start the categorization process.

4. **Review Results:**
   - Files will be automatically categorized and moved into respective folders within the target directory.

## Configuration

- **No Explicit Configuration Required:**
  - The basic functionality works without additional configuration.
  
- **Future Enhancements:**
  - Upcoming updates might introduce additional configuration settings stored in a `json/` directory.

## Getting Started

To start using the File Organizer project:

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/krsna016/upskill-campus-intern-project-2.git


---

## System Design & Folder Structure
```text
.github/                  # CI/CD pipelines, Dependabot, and Issue/PR schemas
.editorconfig             # Unified file formatting configuration
.gitattributes            # Normalization variables for LF line endings
.gitignore                # Local environment overrides and cache limits
.pre-commit-config.yaml   # Quality check execution triggers
LICENSE                   # Permissive open-source MIT License
Makefile                  # Development workspace orchestrator
CHANGELOG.md              # Historical version tracking
CONTRIBUTING.md           # Developer onboarding guidelines
CODE_OF_CONDUCT.md        # Communication guidelines
SECURITY.md               # Responsible vulnerability disclosures
```

---

## Tooling & Tech Stack
- **Primary Environment:** Python runtime.
- **Workflow Automation:** GitHub Actions CI, Dependabot, and CodeQL.
- **Standards Checkers:** Git `pre-commit` hook validations.

---

## Quickstart & Local Setup
1. Clone this repository locally:
   ```bash
   git clone https://github.com/krsna016/c1-file-organizer.git
   cd c1-file-organizer
   ```
2. Trigger the local setup runner:
   ```bash
   make help
   ```

---

## Security & Responsible Disclosure
For details on disclosing vulnerabilities or hardcoded secrets, refer directly to our [SECURITY.md](SECURITY.md) guidelines.

---

## License
This repository is licensed under the permissive **MIT License**. For details, see the [LICENSE](LICENSE) file.
