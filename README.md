# Muhammad Zawad Mubassher - Curriculum Vitae

![LaTeX](https://img.shields.io/badge/Typeset_in-LaTeX-008080?style=flat-square&logo=latex&logoColor=white)
![Build](https://img.shields.io/badge/Build-XeLaTeX-blue?style=flat-square)

This repository contains the source code and compiled version of my resume. It is typeset in LaTeX using the **Lato** font family cause I found it quite neat.

[**Click here to download the latest PDF version**](Resume.pdf)

I've omitted my phone number and specific address for obvious reasons. Feel free to reach out to me for more details!

## Project Structure
* **`Resume.tex`**: Main LaTeX source code.
* **`Resume.pdf`**: Compiled document.
* **`.gitignore`**: Ensures build artifacts (`.aux`, `.log`, etc.) remain local.

## How to Build Locally
If you wish to compile this resume from source, you will need a LaTeX distribution (TeX Live or MacTeX) and the Lato font installed. I used the homebrew solution on Mac.

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/ZMTempest/Resume.git](https://github.com/ZMTempest/Resume.git)

2. **Compile with XeLaTeX**
   ```bash
   xelatex Resume.tex

⚠️ Important: This project uses the fontspec package and custom system fonts (Lato). You must use xelatex (or lualatex) to compile it. Attempting to run it with standard pdflatex will result in a crash.