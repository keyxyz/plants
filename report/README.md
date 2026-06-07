# CVPR/ICCV/3DV Official LaTeX template 

> template obtained from [https://github.com/cvpr-org/author-kit](https://github.com/cvpr-org/author-kit) 

## PDF generation steps

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
    latemk -pdf main.tex
    ```
