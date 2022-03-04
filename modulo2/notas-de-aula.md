## **Módulo 2: Criando o seu primeiro repositório e aprendendo os comandos mais utilizados**

</br>

### Notas de aula referentes ao **Módulo 2** do **Curso de Git & GitHub**, via *Potência Feminina*, para o Bootcamp de Back-end Java da *WoMakersCode*.

</br>

### **Aprendendo os comandos mais utilizados do Git:**

</br>

`git config`

**1. Sua identidade:** Definir o seu nome de usuário e endereço de e-mail.

>`git config --global user.name "username"`

>`git config --global user.email email`

**2. Testando suas configurações:** Verificar se a sua identidade no Git foi configurada corretamente. 

> `git config --list`

</br>

`git help`

**1. Direto no terminal:** Traz informações sobre os comandos mais utilizados, e explica como acessar os guias referentes a comandos específicos.

> `git --help` 

**2. Através da `manpage` do comando `config`:** Acessa a página do manual de ajuda (`manpage`) para qualquer um dos comandos Git. 

>`git help config`

</br>

`git init`

**1. Inicializando um repositório em um diretório existente:** Digitar esse comando no diretório do projeto. Isso cria um novo subdiretório chamado .git que contém todos os arquivos necessários do seu repositório. 

**2. Primeira versão:** Para controlar o versionamento dos arquivos existentes (diferente de um diretório vazio), é necessário fazer um commit inicial. 

>`touch .gitignore`

>`git add .gitignore`

>`git commit -m "Versão inicial do projeto"` 

</br>

`git status`

Principal ferramenta utilizada para determinar o estado dos arquivos, e mostrar em qual branch o usuário se encontra. Caso o arquivo não exista e você execute o comando `git status`, o arquivo não monitorado será listado  sob o cabeçalho **"Untracked files"** no terminal.

> ***Não monitorado** significa basicamente que o Git está vendo um arquivo que não existia na última captura (`commit`). Portanto, o Git não vai incluí-lo nas suas capturas de `commit` até que você o diga explicitamente que assim o faça. Ele faz isso para que você não inclua acidentalmente arquivos binários gerados, ou outros arquivos que você não têm a intenção de incluir.*

</br>

`git remote`

**1. Exibindo os seus repositórios remotos (URL's):** Mostra quais servidores remotos o usuário configurou, indicando as URLs que o Git tem armazenado, de acordo com os nomes abreviados de cada repositório específico.

> `git remote -v`

**2. Adicionando repositótios remotos:** Para adicionar um novo repositório Git remoto como um nome curto que você pode referenciar facilmente, execute:

> `git remote add origin <shortname> <url>`

> `git remote add origin https://github.com/kammonteiro/curso-git-github.git`

</br>

`git add`

Quando um repositório é inicialmente clonado, todos os seus arquivos estarão monitorados e inalterados porque você simplesmente os obteve e ainda não os editou. Conforme você edita esses arquivos, o Git passa a vê-los como modificados, porque você os alterou desde seu último `commit`. Você seleciona esses arquivos modificados e então faz o `commit` de todas as alterações selecionadas e o ciclo se repete.

**1.Adiciona um arquivo em específico:**
> `git add [caminho do arquivo]`

**2.Adiciona todos os arquivos para a esteira de `commit`:**
> `git add .`

</br>

`git commit`

Armazena o conteúdo atual do índice em um novo `commit`, juntamente com uma mensagem de registro do usuário que descreve as mudanças. 

> `git commit - m "Detalhe das modificações."
