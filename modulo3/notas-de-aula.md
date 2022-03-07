## **Módulo 3: Trabalhando com branchs**

</br>

### Notas de aula referentes ao **Módulo 3** do **Curso de Git & GitHub**, via *Potência Feminina*, para o Bootcamp de Back-end Java da *WoMakersCode*.

</br>

Branchs são separações de código, e com elas é possíve que várias pessoas atuem em um mesmo projeto de forma indepedente e simultâneo.

A branch inicial de todo projeto é a **master** (ou **main**). Nas empresas, as branchs normalmente são criadas de acordo com o ambiente em que o código será disponibilizado: **Develop**, **Homolog**, **Master**.

Para criar uma nova branch, utilizar o seguinte comando:

> `git checkout -b <nome da branch>`

Para saber em qual branch você está:

> `git branch`

Para retornar para a branch principal:

> `git checkout master`

</br>

Esse comando vai criar e já trocar para essa nova branch.

Para criar a branch pelo GitHub:

**1.** Acessar o repositório;

**2.** Ir na sessão de listagem das branchs;

**3.** Inserir o nome da nova branch;

**4.** Confirmar a criação dessa nova branch.

</br>

Caso queira excluir uma branch pelo GitHub:

**1.** Vá na seção de listagem de branchs

**2.** Clique no ícone da lixeira para realizar a exclusão dessa branch.

</br>

> `git merge`

Esse comando faz a união de duas ou mais branchs.
**IMPORTANTE:** Manter a branch `master` sempre atualizada.
