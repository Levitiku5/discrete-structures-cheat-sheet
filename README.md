# Discrete Mathematics Quick Reference Notes 
This repository contains concise, easy-to-reference notes for discrete mathematics, suitable as a cheat sheet or quick reference guide. The notes are neatly formatted in LaTeX for clarity and convenience. Discrete mathematics/structures is a powerful area of mathematics for computer scientists, engineers, and mathematicians. Personally, I found a large portion of the study is terminology coupled with concepts. These notes seek to summarize the most important definitions and concepts in a single, largely comprehensiuve, and easy-to-reference document.
## Contents 
- `definitions.pdf`: A compiled PDF file with essential definitions and quick-reference materials. 
- `definitions.tex`: The primary LaTeX file that integrates all components of the notes. 
- Supporting `.png` files for diagrams. 
## Quick Start 
### Downloading Just the Definitions PDF 
If you only need the compiled quick-reference definitions, download directly: 
```sh
wget https://github.com/Levitiku5/discrete-structures-cheat-sheet/blob/main/definitions.pdf
```
### Cloning the Entire Repository To download and modify the full set of LaTeX notes: 
```sh 
git clone https://github.com/Levitiku5/discrete-structures-cheat-sheet
```
### Compiling the LaTeX Source To compile the notes locally after making changes: 
```sh 
pdflatex definitions.tex 
``` 
For full reference resolution (recommended): 
```sh 
pdflatex definitions.tex pdflatex definitions.tex 
``` 
Alternatively, use `latexmk` for convenience: 
```sh 
latexmk -pdf definitions.tex 
``` 
## Modifying Notes 
Feel free to edit `definitions.tex` to tailor the notes to your needs. I figured I'd upload to Github for easy modification of the source since there is quite a bit of content.
## Dependencies 
- A LaTeX distribution (e.g., TeX Live, MiKTeX) 
- Recommended: `latexmk` for automated builds 
## License 
This project is licensed under the MIT License. Feel free to use, modify, and share these notes as needed.

