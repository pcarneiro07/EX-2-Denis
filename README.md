# Workflow - Geração Automática de Slides

Este repositório contém um workflow do **GitHub Actions** que converte automaticamente arquivos Markdown em PDFs de slides usando **Pandoc**.

## Como funciona
1. Ao fazer push de um arquivo `.md` em `docs/`, o workflow é acionado.
2. O GitHub Actions instala o Pandoc e o LaTeX.
3. Converte `presentation.md` em `slides.pdf`.
4. Publica o PDF como artefato.

## Estrutura
