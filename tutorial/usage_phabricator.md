# Phabricator

---

## Maniphest
Maniphest é o gerenciador de tasks do Phabricator.
Sua interface é bem intuitiva.

![](maniphest/maniphest.png)

Do lado esquerdo, em *Queries*, temos como filtrar as tasks existentes.
Por default, temos o acesso rápido aos filtros
- Assigned: tasks assignadas para você
- Subscribed: tasks em que você está inscrito
- Open Tasks: tasks que estão em aberto
- All Tasks: todas as tasks visíveis para você

Já na seção *Search*, podemos fazer buscas por tasks usando o `Advanced Search`.

![](maniphest/advanced_search.png)

A maioria dos campos são auto-explicativos e, ao clicar na lupa presente em
alguns campos, será listado para você uma lista interativa de objetos para
compor a sua busca.

![](maniphest/advanced_search_2.png)

![](maniphest/advanced_search_3.png)

Após preencher os campos com o que deseja buscar, basta clicar no botão
`Execute Query` para realizar a busca.

![](maniphest/execute_query.png)


### Creating tasks

Para criar uma nova task, basca clicar no botão `Create Task`, localizado no
canto superior direito.

![](maniphest/create_task.png)

Logo após, aparecerá um menu com as possíveis tasks a serem criadas

![](maniphest/create_task2.png)

#### Request a Feature
Como o próprio nome sugere, é o formulário para enviar uma sugestão de feature.
Deve conter o título e, se possível, uma descrição da Feature.

![](maniphest/feature.png)

#### Report a Bug
Quando você encontra um bug, pode reportá-lo pelo proprio Maniphest.

![](maniphest/bug.png)

Além do título, descrição e tags, você deve selecionar uma prioridade para o bug

![](maniphest/bug_priority.png)

#### Custom Task

![](maniphest/custom.png)

---


## Diffusion
Diffusion é o sistema de repositórios do Phabricator

![](diffusion/diffusion.png)

Do lado esquerdo, temos as `Queries`, que filtram rapidamente os repositorios em
*Active Repositories* ou, se preferir, *All Repositories*.
Também é possível fazer buscas mais complexas utilizando-se da
`Advanced Search`.

Do lado direito, temos a listagem de repositórios segundo a *query* escolhida.
Cada repositório apresenta algumas informações de forma resumida, para acessar o
repositório basta clicar no seu nome.

![](diffusion/repo1.png)

### Repository page
Na página do repositório, temos acesso a vários informações, tais como histórico
de commits, branches e navegar pelos arquivos.

Em `Details`, temos as informações necessárias para *clonar* o repositório, no
caso utilizando-se da ferramenta *git*.

![](diffusion/details.png)

Outra seção bem útil é a que nos permite navegar pelo conteúdo do repositório,
normalmente está sob o nome do próprio repositório. Ao clicar
`Browse Repository`, poderá navegar por todos os arquivos do repositório.

![](diffusion/repo2.png)

Também há possibilidade de navegar pelo histórico de commits

![](diffusion/repo3.png)

---


## Differential
Differential é o sistema de review de código do Phabricator

![](differential/differential.png)

### Review Page
A primeira seção nos mostra informações básicas a respeito do review, tais como
autor, projeto, comando para aplicar o *Patch* e o `Sumário`, que é um resumo do
diff.

![](differential/revision.png)

Nos detalhes do diff, temos:
- Nome do repositorio
- Branch
- Lint (verificador de erros)
- Unit (para testes unitários)
- Build status (indicando se a build foi bem sucedida ou não)

![](differential/diff_detail.png)

Em `Revision Update History`, temos o histórico de *diffs* dessa revisão.

![](differential/history.png)

Onde o podemos compará-los entre si, selecionando um para ser a base
(em vermelho) e outro para ser a atualiazação (em verde) e clicando no botão
`Show Diff`.

![](differential/compare.png)

Logo mais abaixo, podemos visualizar a diferença entre os arquivos do *diff*

![](differential/code_diff.png)


---


## Pholio
Pholio te permite fazer o upload de imagens de mocks para revisão

![](pholio/polio.png)

Para visualizar os detalhes de um mockup, basta clicar no nome dele

![](pholio/polio2.png)


### Mockup page
Na página do mockup, podemos visualizar mais informações sobre o mockup

Na seção `Image`, podemos visualizar as imagens com comentários do mockups por
revisão.

![](pholio/images.png)

Já em `History Beckons`, podemos postar comentários sobre o mockup.

![](pholio/comment.png)


### Creating mockups
Para criar um novo mockup, clique no botão `Create Mock` localizado no canto
superior direito.

![](pholio/create.png)

Na página de criação, teremos que preencher um formulário com as informações a
respeito do novo *Mock*.

![](pholio/create1.png)

Em `Projects` e `Subscribers`, você pode clicar na lupa
![](common/magnifier.png) para buscar objetos relativos a cada campo.

Não se esqueça de adicionar as imagens do Mockup no espaço *Drag and drop*
![](pholio/files.png)

Depois de tudo pronto, só clicar no botão `Create`

![](common/create.png)


---


## Paste
O sistema de paste te permite fazer o upload de arquivos de texto.

Para acessá-lo, clique em `Applications`, localizando no menu esquerdo.

![](common/applications.png)

Na lista de aplicativos, procure pelo `Paste`

![](paste/applications.png)

E pronto, terá acesso a lista de pastes, podendo filtra-los com as `Queries`

![](paste/paste.png)


### Creating pastes

Para criar um novo paste, basta clicar no botão `Create Paste`, localizado no
canto superior direito

![](paste/create_button.png)

No formulário seguinte, preencha o título com o nome que desejar e, se quiser
que o proprio Paste detecte a linguagem utilizada (para syntax highlighting),
coloque também uma extensão depois do nome.

![](paste/title.png)

Se preferir, pode selecionar uma das linguagens disponiveis no campo `Language`

![](paste/lang.png)

Digite ou copy-paste dentro o texto/código que deseja subir pro Paste

![](paste/text.png)

Selecione as visibilidade, possibilidade de edição, tags e subscribers
desejados.

![](paste/options.png)

Agora, pra finalizar, basta clicar no botão `Create new paste`.

![](paste/new_button.png)


---


## Conpherence
Conpherence é o serviço para conversação do Phabricator, que lhe permite
conversar em grupo ou privadamente com outras pessoas

Para acessa-lo, selecione `Applications` no menu esquerdo da página principal, e
depois procure por `Conpherence`.
Você se depará com a sua página inicial.

![](conpherence/conpherence.png)

### Checking messages
Para visualizar mensagens, o jeito mais fácil é clicando no ícone no canto
superior esquerdo, em formato de balão ![](conpherence/icon.png) e selecionando
a room desejada.

![](conpherence/fast_room.png)

Se preferir, pode checar na própria página do Conpherence.

![](conpherence/room.png)


### Creating a new room
Para criar uma nova sala, basta clicar no botão `New Room`, localizado no campo
superior direito.

![](conpherence/new_button.png)

No formulário de criação, dê um nome para a sala e selecione os participantes
(podendo ser uma ou mais pessoas). Lembrando que você pode pesquisar por
usernames clicando no icone de lupa ![](common/magnifier.png).

![](conpherence/new_room.png)

Após configurar as opções extras como desejar, basta clicar no botão
`Create Room`.

![](conpherence/create_button.png)


---


## Herald
Com o Herald, podemos configurar diversas regras de notificação para
modificações no Phabricator.
Para acessa-lo, procure-o na lista de aplicativos.

![](common/applications.png)

![](herald/list.png)

### Creating a new rule
Para criar uma nova regra, clique no botão superior direito `Create Herald Rule`

![](herald/create_button.png)

Nesse exemplo, criaremos uma regra para nos notificar via email toda vez que
houver um commit com a mensagem contendo a palavra `bug`

No primeiro formulário, selecione a opção `Commits` e clique em `Continue`.

![](herald/rule_commits.png)

Como só queremos nos notificar, selecione a opção `Personal`.

![](herald/rule_personal.png)

Em `Rule Name`, dê um nome para a notificação, no exemplo usarei `CommitBug`.

![](herald/rule_name.png)

Em conditions, escolhemos "When **all of** ...", já que queremos que nos
notifique para todos os commits.
Nos campos seguintes, escolha respectivamente: `Commit message`, `contains` e,
no campo de texto, digite `bug`.
Para criar a condição, clique em `New Condition`.

![](herald/rule_condition.png)

Agora, na seção `Action`, selecione `Send me an email` e, em seguida, no botão
`New Action`

![](herald/rule_action.png)

Com tudo feito, clique em `Save Rule` e você será redirecionado para a página da
regra recém-criada.

![](herald/save.png)
