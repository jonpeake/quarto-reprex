This repository demonstrates the potential bug where a branded revealjs quarto file will not render from a subdirectory if `theme: brand` is specified.

Steps to reproduce:
1. Clone GitHub repo
2. Change directory into the `test` folder
3. Run `quarto render reprex.qmd` in the terminal to verify that the file renders correctly
4. Change directory into the `quarto-reprex` folder
5. Run `quarto render test/reprex.qmd` in the terminal to verify that file no longer renders correctly