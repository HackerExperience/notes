# Phabricator

---

Maniphest is Phabricator's task manager. It's where we track issues, discuss new features and solve any sort of problems related to the game and its components.

{F2952, size=full, layout=center}

On the left side we can filter all existing tasks through //Queries//.

By default, we have a quick access to the following filters:
- **Assigned** - tasks assigned to you.
- **Subscribed** - tasks you are following.
- **Open Tasks** - tasks that are not resolved yet.
- **All Tasks** - all tasks that are visible to you.

The //Search// sections allows you to perform a detailed search through `Advanced Search`.

{F2948, size=full, layout=center}

The vast majority of fields are self explanatory and, when clicking on the magnifier icon, you'll see an interactive list of object to compose the search.

{F2950, size=full, layout=center}

{F2956, size=full, layout=center}

After filling the fields with what you want, just click `Execute Query` to perform the search.

{F2949, size=full, layout=center}

### Creating tasks

To create a new task, just click on `Create Task`, located in the upper-right corner.

{F2958, size=full, layout=center}

Soon after that, a menu will show up with all possible tasks to be created. Select the one that best matches your task.

{F2953, size=full, layout=center}

#### Request a Feature

This is the form to suggest a feature. Fill the fields with your suggestions details and then submit it.

{F2951, size=full, layout=center}

#### Report a Bug

This is the form to report a bug. Describe it as detailed as you can and submit the task.

{F2955, size=full, layout=center}

#### Custom Task

You can add generic tasks, with specific options, by using the `Custom Task` form. To avoid abuse, this option is only available to members of the group #contributors.

{F2954, size=full, layout=center}

---


## Differential
Differential is Phabricator's code review application. It's the place where we review, discuss and accept/reject submitted patches.

{F2963, size=full, layout=center}

### Review Page

The first section show us some basic information about the review, such as author, project, associated tasks and `Summary`.

{F2961, size=full, layout=center}

The diff details are:
- Repository's name
- Branch
- Lint (error checker)
- Unit (for unit tests)
- Build status (indicates whether the build was successful)

{F2962, size=full, layout=center}

Em `Revision Update History`, temos o histórico de *diffs* dessa revisão.

{F2964, size=full, layout=center}

Onde o podemos compará-los entre si, selecionando um para ser a base
(em vermelho) e outro para ser a atualiazação (em verde) e clicando no botão
`Show Diff`.

{F2965, size=full, layout=center}

Logo mais abaixo, podemos visualizar a diferença entre os arquivos do *diff*

{F2960, size=full, layout=center}


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

Agora, na seção `Action`, selecione `Send me a email` e, em seguida, no botão
`New Action`

![](herald/rule_action.png)

Com tudo feito, clique em `Save Rule` e você será redirecionado para a página da
regra recém-criada.

![](herald/save.png)
