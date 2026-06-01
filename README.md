# Projeto IDEB Paraíba

Site estático com visualizações dos dados do IDEB para a Paraíba.

Como publicar no GitHub:

1. Crie um repositório no GitHub (público ou privado).
2. No seu repositório local execute:

```bash
cd "c:\Users\moise\Downloads\Projeto.Daniel"
git remote add origin https://github.com/SEU_USUARIO/NOME_DO_REPO.git
git branch -M main
git push -u origin main
```

O repositório inclui um workflow que faz deploy automático para GitHub Pages
usando a pasta `docs/`. Após o primeiro push, o Actions irá criar a branch
`gh-pages` e publicar o site em `https://SEU_USUARIO.github.io/NOME_DO_REPO/`.

Observação: substitua `SEU_USUARIO` e `NOME_DO_REPO` nos comandos e no link.
