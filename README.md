# Informática Aplicada à Engenharia Florestal

Site da disciplina **Informática Aplicada à Engenharia Florestal** — UFAL,
Campus CECA (Rio Largo). Construído com [Quarto](https://quarto.org),
publicado via GitHub Pages (GitHub Actions).

🔗 Site publicado: https://profdavybaia.github.io/informatica-aplicada-a-engenharia-florestal/

## Estrutura

- `index.qmd` — página única do site (Aulas, Ementa, Cronograma, Avaliação,
  Bibliografia, Docente).
- `aulas/NN-tema/` — cada aula tem `aula.qmd` (slides em revealjs) e
  `notas.qmd` (texto de referência).
- `.github/workflows/publish.yml` — publica automaticamente a cada push na
  branch `main`.

## Desenvolvimento local

```bash
quarto preview
```

Requer Python + Jupyter (ver `requirements.txt`) para os blocos de código
executável.
