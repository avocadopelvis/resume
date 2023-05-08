# HOW TO USE THIS TEMPLATE?
- Download this repository.
- Upload the files on [Overleaf](https://www.overleaf.com/).
- Compile resume.tex.

To make an image, paste the below code in 'latexmkrc': 

``END { system('convert -density 600 -background white -flatten output.pdf resume.png'); }``

![resume](https://user-images.githubusercontent.com/92647313/236775539-a93af7a5-bcef-41b4-9ebf-ae6041f40d3e.png)
