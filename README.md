# Meu repositório de anotações sobre Git/GitHub
Repositório criado para o desafio de projeto do bootcamp da DIO.


## Links Importantes:
[Sintaxe Basica Markdown](https://www.markdownguide.org/basic-syntax/)

[Download do Git](https://git-scm.com/downloads)

[Download do GitHub](https://desktop.github.com/)

## O que é Git?:
Git é um sistema de **controle de versão de arquivos** onde podemos desenvolver projetos na qual **diversas pessoas podem contribuir simultaneamente**, editando e criando novos arquivos,permitindo que os mesmos possam existir sem o risco de suas alterações serem sobrescritas.

#### Comandos de terminal (Windows Version):

- **cd** (*Change Directory*): Usado para mudar de diretório;
- **cd ..** (*Change Directory ..*): Retorna a pasta anterior a atual;
- **dir** (*Directory*): Lista os diretórios;
- **mkdir** (*Make Directory*): Cria diretórios;
- **cls** (*Clear*): Limpa o terminal;
- **del/rmdir** (*Delete/Remove Directory*): O comando del deleta aquivos e o rmdir deleta diretórios;
- **Tecla TAB**: Tecla usada para auto completar palavras.

#### Comandos GitBash:

- **git commit**: Ele leva as mudanças de um ambiente local para o repositório no git;
- **git add**: Prepara arquivos para o próximo “commit”, ou seja, para subir para o repositório na web;
- **git innit**: Comando para começar um repositório;
- **git clone**: Clona um código de um repositório para a sua máquina;
- **git status**: Para saber informações sobre a ramificação na qual você está trabalhando;
- **git rm**: Remove arquivos do git;
- **git pull**: É uma forma de atualizar a sua versão da aplicação com o que foi alterado remotamente;
- **git push**: É uma forma de atualizar a versão remota da aplicação com o que foi alterado na sua maquina;
- **git config**: Comando inicial para vincular o trabalho no repositório com sua conta no github.

#### Objetos do Git:

![imagem-blob-tree-e-commit](https://user-images.githubusercontent.com/105538076/173146945-b7b1c488-0b24-4b57-8b5e-65bfb00739a6.png)

- **Blob**: É o tipo de objeto usado para armazenar o conteúdo de cada arquivo em um repositório;
- **Tree**: A tree representa um diretório, contendo uma mistura de blobs e trees;
- **Commit**: Especifica a tree de nível mais alto para o snapshot do projeto neste ponto; a informação do autor/commiter que usa as configurações user.name e user.

> No **Commit** geralmente nos é gerado um SHA1.

#### E pra que serve o SHA1?

o SHA1 embaralha determinado arquivo, imagem ou texto para que seja gerado um conjunto de caracteres identificadores, caracteres esses que possuem **40** dígitos.Esses quarenta dígitos são **sempre únicos**. Se você pegar um texto enorme e passar ele por esse algoritmo, ele vai gerar esse conjunto de caracteres, **se você alterar uma vírgula que seja desse texto, já será gerado outro conjunto**. Assim, dando mais segurança.

> Outras formas de aumentar a segurança estão disponíveis também no **GitHub**, são elas as **chaves SSH** e os **Access Tokens**

## O que é GitHub?
GitHub é uma plataforma de hospedagem de código-fonte e arquivos com controle de versão usando o Git. Ele permite que programadores, utilitários ou qualquer usuário cadastrado na plataforma contribuam em projetos privados e/ou Open Source de qualquer lugar do mundo.

#### Pra que servem as chaves SSH e os Access Tokens?

**Secure Socket Shell (SSH)**, é um protocolo de segurança de troca de arquivos entre cliente e servidor de internet, usando criptografia. O objetivo do SSH é permitir que desenvolvedores ou outros usuários realizem alterações em sites e servidores utilizando uma conexão simples e segura.
Já os **Tokens de acesso** são usados para a validação de usuários para garantir a autenticidade de quem acessou, ou esta acessando.

