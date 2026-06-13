# Projetos-de-Sistemas

- Guia com os passos/comandos para gerenciar as alterações em um projeto de software.

## 1. Clonar um repositório: Comando utilizado para copiar um repositório existente de um projeto do GitHub para o computador.

Exemplo: git clone URL_DO_REPOSITORIO

## 2. Verificar o status do projeto: Mostra quais arquivos foram modificados, adicionados, removidos e quais estão prontos para realizar commit.

Exemplo: git status

## 3. Adicionar arquivos: Adiciona todos os arquivos modificados para o próximo commit.

Exemplo: git add arquivo.java - adiciona um arquivo específico.
Exemplo: git add . - adiciona todos os arquivos modificados

## 4. Realizar um commit: Registra uma versão/ponto importante do projeto com uma descrição clara e simples das alterações realizadas.

Exemplo: git commit -m "Descrição da alteração"

## 5. Consultar o histórico de commits: Exibe o histórico de alterações realizadas no projeto, ajudando a acompanhar a evolução do projeto e permitindo identificar mudanças anteriores.

Exemplo: git log - mostra histórico completo.
Exemplo: git log --oneline - mostra versão resumida.

## 6. Criar uma branch: Cria uma nova branch para desenvolver uma funcionalidade sem alterar o código principal do projeto.

Exemplo: git branch nome-da-branch
Exemplo de troca de branch: git checkout nome-da-branch

## 7. Merge: Une alterações de branches diferentes, usado após finalizar uma funcionalidade. As alterações feitas na branch login serão adicionadas a branch main.

O primeiro passo é trocar para a main: git switch main
Exemplo: estando na branch principal (main): git merge nome-da-branch






