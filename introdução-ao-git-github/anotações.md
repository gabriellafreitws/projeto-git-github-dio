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

## Como exportar e importar documentos?

#### Trajeto Github → Local:
- Copia-se o HTTPS do repositório:

![FOLLOW-THROUGH-GIT5](https://user-images.githubusercontent.com/105538076/173152761-b568e3da-1201-430d-b308-ab5feb81cf0e.png)
- Abre-se o GitBash numa pasta:

![6](https://user-images.githubusercontent.com/105538076/173153291-aab236c1-cbfa-4312-8b1e-4a0e8de34c6a.png)

- Inserir comando **git clone** + **link** e logo depois dar um **cd** + **nome do repositório**:

![FOLLOW-THROUGH-GIT](https://user-images.githubusercontent.com/105538076/173153598-320c2bcc-548c-49c5-aa2b-2f6ef1e0e615.png)
> Ao usar o comando **git status** nota-se conformidade.

![FOLLOW-THROUGH-GIT7](https://user-images.githubusercontent.com/105538076/173154120-25ba4e7e-a995-410f-b08d-5874bc28b6c7.png)

#### Trajeto Local → Github:
- Cria-se um arquivo de texto dentro da pasta do repositório:

![FOLLOW-THROUGH-GIT8](https://user-images.githubusercontent.com/105538076/173154401-5a5686d9-5705-4e47-89e0-0904f447238f.png)  
- Utiliza-se o comando **git status** (que mostra que não está reconhecido ainda):

![FOLLOW-THROUGH-GIT2](https://user-images.githubusercontent.com/105538076/173154593-511f8bf6-c812-46e7-8a1e-bc2a0be2037a.png)
- O próprio programa pede a execução do comando **git add .**, e é esse o próximo passo:

![FOLLOW-THROUGH-GIT3](https://user-images.githubusercontent.com/105538076/173154788-a7dc44f1-a20a-497f-91f4-5e1c00ca37bd.png)
> Executa-se o **git status** apenas pra checar conformidade.

- Usar **git commit** e dar um título a esse commit:

![FOLLOW-THROUGH-GIT4](https://user-images.githubusercontent.com/105538076/173155651-ce1571f1-5574-42ee-ac66-c6955e9aec8b.png)
