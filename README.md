# Comandos Git

## Clonar

```bash
cd p/js

git clone https://github.com/jiselli/curso-javascript-ninja

cd curso-javascript-ninja

```
## Novo branch + saindo do master

```bash
git remote -v # Visualizar todos os remotos.

git branch -v # Visualizar todos os branches + commit.

git branch challenge-03 # Criar novo branch "challenge-03".

git checkout challenge-03 # Trocar de branch.
```

## Stage area + nova versão (commit)

```bash
code .
    
git status # Verificar estado dos arquivos.

git add . # Adicionar todas as modificações à Stage area.

git commit -m 'initial commit'
```

## Atualizando o remoto

```bash
git remote -v

git remote add {link} # adiciona remoto repositorio  

git push origin challenge-03
```

## Voltando para o master

```bash
git checkout master
```

## Merge de modificações no master

```bash
git merge challenge-03
```

## Atalho para preview ctrl+shift+

> corrigindo a issue 2