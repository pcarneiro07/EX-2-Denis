# Workflow - Geração Automática de Slides

Este repositório contém um workflow do **GitHub Actions** que converte automaticamente arquivos Markdown em PDFs de slides usando **Pandoc**.

## Como funciona
1. Ao fazer push de um arquivo `.md` em `docs/`, o workflow é acionado.
2. O GitHub Actions instala o Pandoc e o LaTeX.
3. Converte `presentation.md` em `slides.pdf`.
4. Publica o PDF como artefato.

> ⚠️ Observação:
> O workflow foi corretamente implementado e acionado pelo GitHub Actions.  
> A execução apresentou falha na etapa de instalação ou compilação do LaTeX, o que é comum devido ao tamanho e tempo de instalação desses pacotes em runners gratuitos.

## Estrutura
