# Git

## Commits semânticos
```sh
feat: Novo recurso (feature) adicionado ao código.
fix: Correção de bug ou erro no código.
docs: Alterações na documentação do projeto.
style: Alterações que não afetam o comportamento do código (por exemplo, formatação, espaçamento).
refactor: Refatoração do código, sem adição de novos recursos ou correção de bugs.
perf: Melhorias de desempenho no código.
test: Adição ou modificação de testes.
chore: Atualizações diversas no processo de desenvolvimento, configurações, etc.
build: Alterações que afetam o sistema de build ou dependências externas.
ci: Alterações nos arquivos de integração contínua (por exemplo, GitHub Actions, Travis CI).
```

## Comandos Básicos
- ****git init:**** iniciando um novo repositório.
- ************************git status:************************ verifica os status do repositório
- **************************git add “seu arquivo”:************************** adiciona o arquivo para ser comitado
- ********************git add . :******************** adiciona todos os arquivos para ser comitado
- ******************************git commit “seu arquivo” -m “mensagem do commit”:****************************** commit especifico para um arquivo
- **********************git commit -m “mensagem do commit”:********************** commit para todos os arquivos
- ********************git push:******************** comando para subir as novas modificações do projeto
- ******************git pull:****************** comando para descer modificações do projeto
- ****************************git clone “url do repositorio”:**************************** comando para realizar um clone do repositorio
- **************git log:************** comando para verificar os commits do repositorio
- ****************************git checkout “seu arquivo”:**************************** comando para voltar o arquivo para o ultimo commit salvo
- ******git reset --hard origin/main:****** faz voltar para o último commit do projeto
