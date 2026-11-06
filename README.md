# senai-versoes-colaboracoes

Atividade do SENAI sobre **versionamento e colaboração com Git**: criação de branches, merge e resolução de conflitos.

## Conteúdo

- `index.html` — página simples usada no exercício.

## Como praticar o conflito

```bash
git checkout -b feature1
# altere o <h1> do index.html e faça commit
git checkout main
# altere o mesmo <h1> de outra forma e faça commit
git merge feature1
# resolva os marcadores <<<<<<< ======= >>>>>>> e faça commit
```

Autor: Givanildo Aquino
