# Git e Github <img src="./images/git-icon.png" width="50px" height="50px"></img>

O Git é um sistema de controle de versão de códigos. Gerencia ramificações feitas por diferentes pessoas de um time de modo a manter a ordem e integração de todas as partes. Ou seja, mesmo que várias pessoas estejam trabalhando em um programa ao mesmo tempo, ainda é possível controlar as mudanças para evitar erros.

> Esse repositório tem por objetivo falar sobre o Git, e seus comandos.</br>

## Baixar

Para baixar o git em seu sistema é bem simples basta acessar o site oficial, baixar e instalar Acesse: <a href="https://git-scm.com/">[Site Oficial].</a>

## SSH - Git:

SSH é um protocolo, para quê você possa se conectar a servidores e serviços remotos e se autenticar neles. Com chaves SSH, você pode se conectar a GitHub sem fornecer seu nome de usuário e personal access token em cada visita. Você também pode usar uma chave SSH para assinar confirmações.

Para criar chave SSH e Conectar ao gitHub Acesse a documentação a seguir e execute os passo: <a href="https://docs.github.com/pt/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent">[Documentação SSH].</a>

## Estados: 

(modified) = Modificado;

(staged/index) = Preparado;

(comitted) = Consolidado;

## Comandos

### Ajuda

> git help

### Ajuda Especifica

> git help add</br>
git help commit</br>
git help <qualquer_comando_git>

## Em Geral

As configurações do GIT são armazenadas no arquivo .gitconfig localizado dentro do diretório do usuário do Sistema Operacional (Ex.: Windows: C:\Users\Documents and Settings\*SEU-USUARIO ou *nix /home/*SEU-NOME). As configurações realizadas através dos comandos abaixo serão incluídas no arquivo citado acima.

### Configurar Usuario

> git config --global user.name "Seu Nome"

### Configurar Email

> git config --global user.email seuemail@gmail.com

### Configurar Ferramenta de Merge

> git config --global merge.tool vimdiff

### Configurar Editor

> git config --global core.editor vim

### Configurar Arquivos Quê Serão Ignorados

> git config --global core.excludesfile ~/.gitignore

### Listar Configurações

> git config --list
