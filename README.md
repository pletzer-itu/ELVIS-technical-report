# ELVIS technical report template

This repository contains a LaTeX template for the Learn Lab ELVIS final
sensor-demonstrator technical report. It uses the `report` document class,
stores chapters in `chapters/`, and imports them from `report.tex`. The
bibliography remains in `report.tex`.

## Build requirements

- A LaTeX distribution providing `pdflatex` and the `geometry`, `fontenc`,
  `graphicx`, `hyperref`, `booktabs`, and `tabularx` packages.
- For building in VS Code, install the **LaTeX Workshop** extension.

The [`.vscode/settings.json`](.vscode/settings.json) file provides an example
LaTeX Workshop configuration that runs `pdflatex` twice to update
cross-references and the table of contents.
