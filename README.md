# git-academy-22

## Configurações iniciais:
- Precisamos vincular nossos dados ao git local, facilitando a identificação dos
responsáveis pelo código

- É recomendado utilizar o username e email que usamos na conta do github

```bash
git config --global user.name 'Username'
git config --global user.email 'example@email.com'
```

## Iniciando um repositório local
Inicialização de um projeto:

```bash
git init
```

## Controle de alterações
Para exibir as alterações feitas, vamos usar:

```bash
git status
```

## Criando commits
Primeiramente, precisamos adicionar as mudanças e enfim 'commitar':

- Utilize o ponto (.) para adicionar todas as alterações!

```bash
git add .
git commit -m "Descrição das alterações"
```

## Histórico de alterações
- Podemos listar todos os commits feito usando:

```bash
git log
```

## Branches
Podemos ramificar o código usando branches. Para criar uma nova, executamos:

```bash
git switch --create <nome-da-nova-branch>
or
git checkout -b <nome-da-nova-branch>
```

- Listando todas as branches criadas:

```bash
git branch
```

- Apagando uma branch:

```bash
git branch -D <nome-da-branch>
```

## GitHub
> O GitHub é uma plataforma onde podemos subir repositórios e controlar versões
on-line, o que vai facilitar no trabalho em equipe;

> Desenvolvedores utilizam como portfólio;

> Muitas empresas de desenvolvimento usam como padrão em seus projetos;

- Adicionando um remote origin:

```bash
git remote add origin git@github.com:user/nome-do-repo.git
```

- Subindo alterações:

```bash
git push origin <nome-da-branch>
# caso a branch nao exista no GitHub use:
git push -u origin <nome-da-branch> # ele criara a branch no GitHub
```
- Baixar alterações para o repositório local:

```bash
git pull
```

- Clonando repositórios:

```bash
git clone git@github.com:user/nome-do-repo.git
```