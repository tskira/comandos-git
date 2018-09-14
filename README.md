# Comands Git

## Flow básico:

``` 
git add <arquivos>
git commit -m "<label>"
git push <remote> <branch>
```

Exemplo:

```
git add . 
git commit -m "first commit"
git push origin master

```

## Configurações iniciais do git:

```
git config --global user.name "<nome>"
git config --global user.email <email>
```

Exemplo:

```
git config --global user.name "tskira"
git config --global user.email tskira@hotmail.com
```

## Criar repositorio local

```
git init
```

## Clonando repositório:

```
git clone <url>
```
Exemplo:

```
git clone https://github.com/tskira/comandos-git
```

## Verificando status de arquivos

```
git status
```

## Trabalhando com repositorios remotos

### Conectando a um repositorio remoto

```
git remote add <nome> <url>
```

Exemplo: 

```
git remote add origin https://github.com/tskira/comandos-git.git
```

### Removendo um remote

```
git remote rm <name>
```
Exemplo:

```
git remote rm origin
```

### Listando os remotes

```
git remote -v
```

## Trabalhando com branchs:

### Criar: 

```
git checkout -b <nome_branch>
```
Exemplo: 

```
git checkout -b dev
```

### Trocar:

```
git checkout <nome_branch>
```

Exemplo

```
git checkout dev
```

### Listar:

```
git branch
```

### Remover: 
```
git branch -d <nome_branch>
```

Exemplo:

```
git branch -d dev
```

## Baixando atualizações do repositorio remoto:

```
git pull <remote> <branch>
```

Exemplo:

```
git pull origin master
```

## Merge

```
git merge <nome_branch>
```

Exemplo:

```
git merge dev
```

## Stash

### Empilhar
```
git stash
```
ou

```
git stash name "<nome_stash>"
```
### Desempilhar

``` 
git stash apply 
```

ou :

```
git stash apply stash@{num_stash}
```

### Listar

```
git stash list
```


