## **MÓDULO 3: TRABALHANDO COM BRANCHS**

### Notas de aula referentes ao **MÓDULO 3** do **CURSO DE GIT & GITHUB**, via *Potência Feminina*, para o Bootcamp de Back-end Java da *WoMakersCode*.

Branchs são separações de código, e com elas é possíve que várias pessoas atuem em um mesmo projeto de forma indepedente e simultâneo.

A branch inicial de todo projeto é a **master** (ou **main**). Nas empresas, as branchs normalmente são criadas de acordo com o ambiente em que o código será disponibilizado: **Develop**, **Homolog** e **Master**.

Para criar uma nova branch, utilizar o seguinte comando:

`git checkout -b <nome da branch>`

Para saber em qual branch você está:

`git branch`

Para retornar para a branch principal:

`git checkout master`

Para criar a branch pelo GitHub:

- Acessar o repositório;

- Ir na sessão de listagem das branchs;

- Inserir o nome da nova branch;

- Confirmar a criação dessa nova branch.

Caso queira excluir uma branch pelo GitHub:

- Vá na seção de listagem de branchs

- Clique no ícone da lixeira para realizar a exclusão dessa branch.

Caso queira unir duas ou mais branchs usar esse comando:

`git merge`


**IMPORTANTE:** Manter a branch `master` sempre atualizada.
