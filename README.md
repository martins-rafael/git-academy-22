# git-academy-22

## Configurações Iniciais:

```bash
git config --global user.name 'Username'
git config --global user.email 'example@email.com'
```

## git init
Inicialização de um projeto:

```bash
git init
```

## Controle de alterações
Para iniciar as alterções feitas, vamos usar:

```bash
git status
```

## Criando commits
Primeiramente, precisamas adicionar as mudanças e enfim 'commitar':

- Utiliize o ponto para adicionar todas as alterações!

```bash
git add .
git commit -m "Descrição das alterações"
```

## Branches
Podemos ramificar o código usando branches para criar uma nova, executamos:

```bash
git switch --create <nome-da-nova-branch>
or
git checkout -b <nome-da-nova-branch>
```

- Listando branchs criadas:

```bash
git branch
```

- Apagando uma branch:

```bash
git branch -D <nome-da-branch>
```

## GitHub
- Adicionando um remote origin:

```bash
git remote add origin git@github.com:user/nome-do-repo.git
```

- Subindo alterações:

```bash
git push -u origin <nome-da-branch>
```
