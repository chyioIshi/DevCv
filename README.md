<h1 align="center">DevCv · Stanislav Makarov</h1>

<p align="center">
  <b>Senior SDET / Python Automation Engineer</b>
</p>

<p align="center">
  <a href="https://github.com/chyioIshi/DevCv/raw/refs/heads/main/ru/ru_cv.pdf"><img src="assets/download-ru.svg" alt="Скачать резюме на русском (PDF)" width="340"></a>
  <a href="https://github.com/chyioIshi/DevCv/raw/refs/heads/main/en/en_cv.pdf"><img src="assets/download-en.svg" alt="Download resume in English (PDF)" width="340"></a>
</p>

<p align="center">
  <a href="https://github.com/chyioIshi">GitHub</a>
  ·
  <a href="https://linkedin.com/in/chyioIshi">LinkedIn</a>
  ·
  <a href="https://t.me/makarovsvv">Telegram</a>
  ·
  <a href="mailto:takahiroMushashii@proton.me">Email</a>
</p>

<p align="center">
  Резюме на русском и английском · CV in Russian and English<br>
  Исходники LaTeX и готовые PDF · LaTeX sources and ready-to-download PDFs
</p>

---

<details>
<summary><b>Сборка / Build</b></summary>

### Requirements

Requirements:

- MiKTeX or TeX Live
- `latexmk`
- XeLaTeX for the Russian version
- Libertinus OpenType fonts for the Russian version (included in full TeX Live / MacTeX)

### English CV

Run from the repository root:

```sh
latexmk -pdf -interaction=nonstopmode -file-line-error -outdir=en -auxdir=en en/en_cv.tex
```

### Russian CV

```sh
latexmk -xelatex -interaction=nonstopmode -file-line-error -outdir=ru -auxdir=ru ru/ru_cv.tex
```

Generated LaTeX auxiliary files are ignored by Git.

</details>
