# DIO | Git e GitHub

Repositório para armazenar resumos sobre Git e GitHub do curso Versionamento de Código com Git e GitHub da [Digital Innovation One](https//www.dio.me/)

## 📚 Documentação
- [Documentação Git](https://git-scm.com/doc)
- [Documentação GitHub](https://docs.github.com/pt)

## 💻 Resumos das Aulas

| Aulas | Resumos |
|-------|---------|
| Gravando Alterações no Repositório Local | [Resumos]()|

1. Inicia um novo repositório Git no diretório atual.
```
git init
```
2. : Adiciona arquivos ao índice para prepará-los para o commit.
```
git add <nome_do_arquivo>
```
3. Registra as alterações no repositório. Você precisa adicionar uma mensagem de commit que descreva as alterações realizadas.
```
git commit -m "mensagem_do_commit"
``` 
4. Mostra o estado atual do diretório de trabalho e do índice (staging area).
```
git status
```
5. Mostra o histórico de commits.
```
git log
```
6. : Clona um repositório remoto para o seu diretório local.
```
git clone
```
7. Puxa as alterações de um repositório remoto para o seu repositório local.
```
git pull
```
8. Envia commits para um repositório remoto.
```
git push
```
9. Para remover um diretório e todo o seu conteúdo a força.
```
rm -rf nome_do_diretorio
```
10. Restaura um arquivo do diretório para o estado em que estavam no último commit
```
git restore
```
11. Muda o nome do último commit feito
```
git commit --amend -m"nome do commit"
```
12. Muda o nome do último commit feito
```
git commit --amend -m"nome do commit"
```
13. Muda o nome do último commit feito abrindo o editor
```
git commit --amend
```
14. Remove as alterações do commit especificado da área de preparação, deixando-o apenas no diretório de trabalho.
```
git reset <hash do commit>
```
15. Desfaz o último commit, mantendo as alterações no diretório de trabalho e na área de preparação.
```
git reset --soft <hash do commit>
```
16. Desfaz o último commit e todas as alterações associadas a ele, revertendo o repositório para o estado em que estava antes desse commit.
```
git reset --hard <hash do commit>
```
17. Registra todas as operações recentes realizadas no repositório Git, permitindo visualizar e recuperar alterações perdidas.
```
git reflog 
```
18. Conecta os dois repositórios (remoto e local)
```
git remote add origin <url>
```
19. Envia as alterações locais para a branch "main" no repositório remoto chamado "origin" e configura essa branch como a upstream (permitindo futuras operações de push e pull sem a necessidade de especificar o nome da branch remota e local)
```
git push -u origin main
```
20. Envia suas alterações locais para o repositório remoto, atualizando-o com suas últimas modificações.
```
git push
```
21. Atualiza seu repositório local com as últimas alterações do repositório remoto. 
```
git pull 
```


## 🔍 Referências
- [Digital Innovation One]().
