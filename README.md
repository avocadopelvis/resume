# HOW TO RUN?
- Download this repository.
- Upload the files on Overleaf.
- Compile resume.tex.

To make an image, paste the below code in 'latexmkrc': 

``END { system('convert -density 600 -background white -flatten output.pdf resume.png'); }``

