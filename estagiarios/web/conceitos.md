## Fork

Criar um “fork” é produzir um cópia pessoal do projeto de alguém. Os forks como se fossem uma ponte entre o repositório original e a tua cópia pessoal. Podes enviar Pull Requests para ajudar a fazer as outras pessoas a tornar os seus projetos melhor oferecendo as tuas mudanças ao projeto original.

### Dar Fork a um repositório

Para dar fork num repositório, clica no botão _Fork_ localizado acima do repositório.

 ![Image](/sys-config/images/fork_forkbutton.png)

 Quando o fork acabar, serás levado á tua cópia do repositório.

## Clone

- Entra na tua conta em [GitHub.com](https://github.com/) e no GitHub Desktop.
- No GitHub.com, navega até à barra de codificação do teu repositório.
- No lado direito do ecrã, clica em "Clone or download".
  ![Image](/sys-config/images/clone_clonebutton.PNG)
- Depois clica em "Open in Desktop". Isto abrir-te-á o GitHub Desktop.
  ![Image](/sys-config/images/clone_opendesktop.PNG)
- Cria uma pasta com o nome "**Drible**" no teu disco.
- Guarda o diretório da pasta "**Drible**".
- Clica em Clone.
- Seleciona a pasta "**Drible**" para guardares o clone.

## Escolhe 5 issues

Ao abrires este [link](https://github.com/popperz0r/drible/issues), vai-te levar a uma webpage onde terá diversos issues (problemas) e terás que escolher 5 desses problemas e resolvê-los.

## Branch

Para fazeres um branch basta ires ao canto inferior direito do Atom e clicar no botão á direita das setas. Em princípio esse botão deve ter um nome do género "master" ou assim.

[Image](/sys-config/images/branch_howto.PNG)

## Alteração de código

Agora vais ficar a conhecer alguns dos códigos básicos do git.

-Cabeçalhos/Títulos
  Para colocar cabeçalhos ou títulos apenas é preciso um cardinal antes do texto que queremos como cabeçalho. Quanto mais cardinais tiver , menor será o título. Ou seja, no exemplo a seguir o "Header 1" será o maior dos títulos e o "Header 3" o menor.

  Ex:
        (Sem edição)  # Header 1 / ## Header 2  / ### Header 3

# Header 1
## Header 2
### Header 3

-Lista
  Para fazer uma lista, apenas é necessário colocar um hífen  e deixar um espaço antes do que queremos na lista:

  Ex:         
  -Lista (Sem edição)

  - Lista Editada

-Lista numérica
  Para criar uma lista númerica basta adicionar-mos o número, um ponto e um espaço antes do que queremos escrever:

  Lista (Sem edição)

  2. Lista Numérica Editada

-Negrito e Itálico
  Para colocar a Negrito basta colocar 2 asteriscos antes e depois do texto que queremos a Negrito e não deixar espaço.

  Ex:
        ** Negrito ** (Sem edição)  /  **Negrito**

  Para colocar em Itálico basta colocar um underscore antes e depois do texto que queremos a Itálico e não deixar espaço.

  Ex:
        _ Itálico _ (Sem edição)  /  _Itálico_

-Links e Imagens

Para colocar um link colocamos o texto que queremos dentro de parênteses retos e colocamos o URL que queremos que nos leve dentro de parênteses normais e não deixar espaço.

  Ex:
        [Link] (Url) (Sem edição) / [Link](Url)

**Obs**: O link não leva a lado nenhum porque não coloquei o URL.

Dentro da pasta Drible que criaste acima, cria uma página com o nome "images" e coloca lá as imagens que queres usar. Depois no Atom, coloca um ponto de exclamação, seguido do texto Image dentro de parênteses retos e a source da imagem em parênteses normais. A source da imagem será o diretório da imagem ou seja algo do género C:/Drible/sys-config/images/imagem1, mas terás que remover a parte do computador e ficará algo do género sys-config/images/imagem1.

  Ex:
        ![Image] (source)

## Commit

Um commit refere-se a submeter alterações do código fonte ao repositório e fazer com que estas alterações se tornem parte da versão principal do repositório. Deste modo, quando outros utilizadores fazem um UPDATE do repositório, eles receberão a versão enviada mais recentemente.

Para dar commit às tuas alterações basta:

- Verificar que todas as alterações estão corretas.
- Dar Ctrl + S no separador onde fizeste as alterações.
- No lado direito do ecrã, clicar em "Stage All".
- Depois onde diz "Commit message", coloca lá um resumo das alterações que fizeste.
- Clica em Commit.

## Push

Depois de dares commit às tuas alterações, o "Push" envia o teu codigo para ser atualizado no repositório. Para dar push basta clicares nas setas abaixo do botão "Commit" e clicar em "Push".

## Pull

O "Pull" serve para atualizar o teu repositório local com a mais nova versão. Para dar "Pull" clica nas setas abaixo de "Commit" e clica em "Pull".

## Pull Request

Pull requests permitem-te dizer ao outros utilizadores das alterações que fizeste para um repositório no GitHub. Uma vez que um pull request é aberto, tu podes discutir e rever as potenciais alterações com os teus colaboradores e adicionar commits novos antes das alterações serem juntas ao repositório.

Para criares um pull request basta:

- Na página do teu repositório no GitHub.com, clica em "New Pull Request".
- Depois clica em "Create Pull Request" e já deve estar o Pull Request feito.

## Merge

Merging é a maneira do Git de pegar num fork e voltar a juntar-lo ao código fonte. O merge deixa-te tomar linhas de desenvolvimento independentes criadas pelo branch e integrá-las de volta ao código fonte.
O branch atual será atualizado para refletir o merge, mas o branch escolhido será completamente inafetado.

## Merge Conflicts

Git pode, frequentemente, resolver as diferenças entre branchs que foram "merged". Normalmente, as mudanças são em linhas diferentes, ou até em ficheiros diferentes, o que faz do merge simples para computadores compreenderem. No entanto, às vezes existe alterações que o Git precisa da tua ajuda para decidir quais alterações incorparar no merge final. Frequentemente, os merge conflicts acontecem quando as pessoa querem fazer diferentes alterações á mesma linha do mesmo ficheiro, ou quando uma pessoa edita um ficheiro e outra pessoa apaga o mesmo ficheiro. Tu tens de resolver os conflitos antes de poderes dar merge aos branches.

Existe um plugin no Atom chamado "Merge-Conflicts" que te pode ajudar com isto. Fica com os passos que queres saber sobre como instalar o plugin:

- Vai a "File", no canto superior esquerdo do Atom.
- Clica em "Settings".
- Em seguida vai a "Install" e pesquisa por "merge-conflicts".
- Irá te aparecer um plugin, instala-o.
