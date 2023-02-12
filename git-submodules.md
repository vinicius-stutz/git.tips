# Git Submodule para Leigos
Aqui estão os passos básicos para adicionar e usar submódulos do Git

## Adicionar um submódulo
Entre na pasta do seu repositório Git principal e execute o comando `git submodule add <repository-url> <directory>`. O repositório-url é a URL do repositório Git externo que você deseja adicionar como submódulo e o diretório é o nome da pasta onde o submódulo será clonado no seu repositório principal.
Depois de executar o comando, o Git adicionará uma entrada para o submódulo no arquivo ".gitmodules" do seu repositório principal.

##Clonar o repositório principal
Quando você clona o repositório principal, o submódulo não será clonado automaticamente. Você precisa executar o comando `git submodule update --init --recursive` para baixar o submódulo.

## Atualizar um submódulo
Para atualizar um submódulo, entre na pasta do submódulo e execute o comando `git pull`. Em seguida, volte para a pasta do repositório principal e execute o comando `git add <submodule-directory>` para registrar as alterações no submódulo.

## Push de alterações no submódulo
Quando você fizer alterações no submódulo, você precisará enviá-las para o repositório Git externo antes de atualizar o repositório principal. Para isso, basta entrar na pasta do submódulo, fazer as alterações e enviá-las para o repositório Git externo com os comandos `git commit` e `git push`. Em seguida, você pode atualizar o repositório principal com as novas alterações no submódulo.

## Considerações finais
Observe que os submódulos são uma ferramenta poderosa, mas também podem ser complicados de gerenciar. Certifique-se de entender bem o funcionamento deles antes de usá-los em seus projetos.

[Voltar](/README.md)
