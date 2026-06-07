# Slides using [Beamer](https://www.overleaf.com/learn/latex/Beamer)  

> template obtained from Overleaf - [https://www.overleaf.com/learn/latex/Beamer](https://www.overleaf.com/learn/latex/Beamer) 

## Slides generation steps

> Only on Linux/Mac/Unix systems

1. update packages

    ```sh
    sudo apt update
    ```

2. install dependencies

    ```sh
    sudo apt install texlive-latex-extra texlive-extra-utils texlive-fonts-recommended

    sudo apt install latexmk
    ```

3. generate pdf

    ```sh
    latexmk -pdf main.tex
    ```

4. clean up temporary files

    ```sh
    latexmk -c
    ```