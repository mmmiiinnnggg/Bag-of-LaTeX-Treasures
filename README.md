# Bag-of-LaTeX-Treasures
LaTeX-documented knowledge summaries of main math courses in bachelor, including diploma work

 - Folder `LaTeX` contains template latex codes
 - Folder `PDF` contains corresponding pdf files
 - You can look up the pdf file for direct learning usage
 - Any possible problems, questions, typos: contact me / raise issues

1. [Diploma LaTeX template](https://github.com/mmmiiinnnggg/Bag-of-LaTeX-Treasures/tree/master/LaTeX/%D0%94%D0%B8%D0%BF%D0%BB%D0%BE%D0%BC%D0%BD%D0%B0%D1%8F%20%D1%80%D0%B0%D0%B1%D0%BE%D1%82%D0%B0)  
    [(Example click here)](https://github.com/mmmiiinnnggg/Bag-of-LaTeX-Treasures/blob/master/PDF/%D0%94%D0%B8%D0%BF%D0%BB%D0%BE%D0%BC%D0%BD%D0%B0%D1%8F%20%D1%80%D0%B0%D0%B1%D0%BE%D1%82%D0%B0.pdf) It satisifies the requirements for diploma work of CMC MSU-BIT. In order to use:
    - Write latex code for each section
    - Plug them into `main.tex` with `\input{}`
    - Complie with pdflatex
2. Knowledge handouts (in Russian)
    - [Комплексный анализ](https://github.com/mmmiiinnnggg/Bag-of-LaTeX-Treasures/blob/master/PDF/3-%D0%BA%D1%83%D1%80%D1%81-%D0%BA%D0%BE%D0%BC%D0%BF%D0%BB%D0%B5%D0%BA%D1%81%D0%BD%D1%8B%D0%B9%20%D0%B0%D0%BD%D0%B0%D0%BB%D0%B8%D0%B7.pdf)
    - [Математический анализ - 4 (интегралы зависящие от параметров, ряды Фурье)](https://github.com/mmmiiinnnggg/Bag-of-LaTeX-Treasures/blob/master/PDF/3-%D0%BA%D1%83%D1%80%D1%81-%D0%BC%D0%B0%D1%82%D0%B0%D0%BD%D0%B0%D0%BB%D0%B8%D0%B7-4.pdf)
    - [Функциональный анализ](https://github.com/mmmiiinnnggg/Bag-of-LaTeX-Treasures/blob/master/PDF/3-%D0%BA%D1%83%D1%80%D1%81-%D1%84%D1%83%D0%BD%D0%BA%D1%86%D0%B8%D0%BE.%20%D0%B0%D0%BD%D0%B0%D0%BB%D0%B8%D0%B7.pdf)
    - [Методы оптимизации](https://github.com/mmmiiinnnggg/Bag-of-LaTeX-Treasures/blob/master/PDF/4-%D0%BA%D1%83%D1%80%D1%81-%D0%BC%D0%B5%D1%82%D0%BE%D0%B4%D1%8B%20%D0%BE%D0%BF%D1%82%D0%B8%D0%BC%D0%B8%D0%B7%D0%B0%D1%86%D0%B8%D0%B8.pdf)
    - [Теория вероятностей и математическая статистика](https://github.com/mmmiiinnnggg/Bag-of-LaTeX-Treasures/blob/master/PDF/4-%D0%BA%D1%83%D1%80%D1%81-%D1%82%D0%B5%D0%BE%D0%B2%D0%B5%D1%80%20%D0%B8%20%D0%BC%D0%B0%D1%82%D1%81%D1%82%D0%B0%D1%82%D0%B8%D1%81%D1%82%D0%B8%D0%BA%D0%B0.pdf)
    - [Математические основы теории управления](https://github.com/mmmiiinnnggg/Bag-of-LaTeX-Treasures/blob/master/PDF/4-%D0%BA%D1%83%D1%80%D1%81-%D0%BC%D0%B0%D1%82.%D0%BE%D1%81%D0%BD%D0%BE%D0%B2%D1%8B%20%D1%82%D0%B5%D0%BE%D1%80%D0%B8%D0%B8%20%D1%83%D0%BF%D1%80%D0%B0%D0%B2%D0%BB%D0%B5%D0%BD%D0%B8%D1%8F.pdf)
    - [Модели извлечения знаний](https://github.com/mmmiiinnnggg/Bag-of-LaTeX-Treasures/blob/master/PDF/4-%D0%BA%D1%83%D1%80%D1%81-%D1%81%D0%BF%D0%B5%D1%86%D0%BA%D1%83%D1%80%D1%81-%D0%B8%D0%B7%D0%B2%D0%BB%D0%B5%D1%87%D0%B5%D0%BD%D0%B8%D0%B5-%D0%B7%D0%BD%D0%B0%D0%BD%D0%B8%D0%B9.pdf)
    - [Математические модели в физике](https://github.com/mmmiiinnnggg/Bag-of-LaTeX-Treasures/blob/master/PDF/4-%D0%BA%D1%83%D1%80%D1%81-%D0%BC%D0%B0%D1%82%D0%BC%D0%BE%D0%B4%D0%B5%D0%BB%D0%B8%20%D0%B2%20%D1%84%D0%B8%D0%B7%D0%B8%D0%BA%D0%B5-%D0%BD%D0%B5%D0%BA%D0%B8%D0%B9%20%D0%BE%D0%B1%D0%B7%D0%BE%D1%80.pdf)

**Notions:**  
- How to plug in `Python` code in the latex:
  1. Download package [`pythonhighlight`](https://github.com/olivierverdier/python-latex-highlighting) (pythonhighlight.sty), put it in the folder which contains `.tex`.
  2. In the `.tex` file: before `\usepackage{document}` write
     ```
     \usepackage{graphicx}  
     \usepackage{pythonhighlight}
     ```
  3. plug in python code in the following way:
     ```
     \begin{python}  
     print("Hello world!")  
     \end{python}  
     ```
 - How to plug in `C/C++` and other language code: use package `listings`
