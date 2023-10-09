# Git <img src="./images/git-icon(50x50).png" width="50px" height="50px"></img>

O Git é um sistema de controle de versão de códigos. Gerencia ramificações feitas por diferentes pessoas de um time de modo a manter a ordem e integração de todas as partes. Ou seja, mesmo que várias pessoas estejam trabalhando em um programa ao mesmo tempo, ainda é possível controlar as mudanças para evitar erros.

# GitHub <img src="./images/github-icon(50x50).png" width="50px" hight="50px"></img>

GitHub é uma plataforma de hospedagem de código-fonte e arquivos com controle de versão usando o Git. Ele permite que programadores, utilitários ou qualquer usuário cadastrado na plataforma contribuam em projetos privados e/ou Open Source de qualquer lugar do mundo.

> Esse repositório tem por objetivo falar sobre o quê é Git e Github, e os principais comandos do git.</br>

## Baixar git <img src="./images/download(50x50).png" width="50px" height="50px"></img>

Para baixar o git em seu sistema é bem simples basta acessar o site oficial, baixar e seguir o instalador normalmente Acesse o site oficial: <a href="https://git-scm.com/">[Site Oficial].</a>

## SSH - Git  <img src="./images/ssh-key-icon(50x50.png).png" width="50px" height="50px"></img>

SSH é um protocolo, para quê você possa se conectar a servidores e serviços remotos e se autenticar neles. Com chaves SSH, você pode se conectar a GitHub sem fornecer seu nome de usuário e personal access token em cada visita. Você também pode usar uma chave SSH para assinar confirmações.

Para criar chave SSH e Conectar ao gitHub Acesse a documentação a seguir e execute o passo a passo: <a href="https://docs.github.com/pt/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent">[Documentação SSH].</a>

## Em Geral <img src="./images/geral-icon(50x50).png" width="50px" height="50px"></img>

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

### Estados: 

> (modified) = Modificado;

> (staged/index) = Preparado;

>(comitted) = Consolidado;

### Ajuda

> git help

### Ajuda Especifica

> git help add</br>
git help commit</br>
git help <qualquer_comando_git>

## Comandos <img src="./images/comandos-icon(50x50).png" width="50px" height="50px"></img>

| Comando | Descrição |