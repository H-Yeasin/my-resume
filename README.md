# 📄 Md. Habib Ullah Yeasin - Resume

[![Build Resume PDF](https://github.com/Yeasin84/my-resume/actions/workflows/build_resume.yml/badge.svg)](https://github.com/Yeasin84/my-resume/actions/workflows/build_resume.yml)
[![PDF Status](https://img.shields.io/badge/Resume-Live-success)](https://yeasin84.github.io/my-resume/Habib_Ullah_Yeasin_Resume.pdf)

This repository contains the **LaTeX source code** for my professional resume. It utilizes a **CI/CD pipeline** (GitHub Actions) to automatically compile and deploy the latest version whenever I push changes.

---

### 🚀 **Download Latest Version**
👉 **[View & Download PDF](https://yeasin84.github.io/my-resume/Habib_Ullah_Yeasin_Resume.pdf)**

---

### 🛠 **How It Works (CI/CD)**
I treat my resume as software. Instead of manually exporting PDFs, I use **GitHub Actions** to automate the build process:

1.  **Source:** The resume is written in LaTeX (`main.tex`).
2.  **Trigger:** Pushing to the `main` branch triggers the workflow.
3.  **Build:** A Linux container compiles the LaTeX code into a PDF.
4.  **Deploy:** The generated PDF is automatically renamed and deployed to the `pdf-hosting` branch, making it instantly available via GitHub Pages.

### 🧰 **Tech Stack**
* **Language:** LaTeX
* **Automation:** GitHub Actions
* **Hosting:** GitHub Pages
* **Editor:** Overleaf / VS Code

---
*Last Updated: (The date on the PDF is always current)*
