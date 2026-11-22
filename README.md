## Actividad Formativa `GA-TL-02 - FORM` (Taller de entrevista estructurada y design thinking)

* **Archivo principal:** `GA/TL-02/main.tex`
* **PDF compilado:** `GA/TL-02/main.pdf`
* **Manifiesto de evidencias privadas (LOPDP):** `GA/TL-02/evidencias/MANIFIESTO.md`
* **Compilador y gestor bibliográfico:** `pdflatex` + `biber` (TeX Live 2024+ o MiKTeX)
* **Dependencias (paquetes LaTeX):** `inputenc`, `fontenc`, `babel` (`spanish`), `geometry`, `microtype`, `array`, `tabularx`, `booktabs`, `colortbl`, `xcolor`, `enumitem`, `fancyhdr`, `lastpage`, `tcolorbox`, `csquotes`, `biblatex` (`backend=biber,style=ieee`), `hyperref`.
* **Orden de comandos para regenerar `GA/TL-02/main.pdf`:**
  ```bash
  cd GA/TL-02
  pdflatex main.tex
  biber main
  pdflatex main.tex
  pdflatex main.tex
  ```
