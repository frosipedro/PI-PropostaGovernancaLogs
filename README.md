# PI-PropostaGovernancaLogs

Projeto integrador do curso de Ciência da Computação da UNIJUÍ sobre governança,
segurança e proteção de dados no processamento de logs de infraestrutura de TI.

O documento principal está em `main.tex` e o PDF final é gerado como `main.pdf`.

## Visão geral

O repositório está organizado para compilar um trabalho acadêmico em LaTeX com
ABNTeX2. Os capítulos ficam separados em arquivos próprios, o que facilita a
revisão e a manutenção do texto.

Estrutura principal:

- `main.tex`: arquivo de entrada do documento.
- `capitulos/`: capítulos textuais do trabalho.
- `apendices/`: anexos e apêndices.
- `anexos/`: materiais complementares.
- `referencias.bib`: base bibliográfica.
- `unijui.sty` e `abntex2cite.sty`: ajustes de estilo e citações.
- `build-latex.sh`: script de compilação.

## Como gerar o PDF

Use uma distribuição LaTeX com suporte ao ABNTeX2 e execute:

```bash
./build-latex.sh
```

O script faz as passagens necessárias de compilação e gera o arquivo `main.pdf`.
Se preferir compilar manualmente, a sequência é `pdflatex`, `bibtex`, `pdflatex`
e `pdflatex` novamente.

## Limpeza

Para remover arquivos temporários da compilação:

```bash
./build-latex.sh clean
```

## Arquivo gerado

- `main.pdf`
