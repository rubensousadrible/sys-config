# O que vamos fazer?

## Configuração do Git

Para começar, tens que criar uma conta no [Github](https://github.com/join)

Em Seguida, tens que fazer [download](https://desktop.github.com/) do GitHub

### Fork

Criar um “fork” é produzir um cópia pessoal do projeto de alguém. Os forks como se fossem uma ponte entre o repositório original e a tua cópia pessoal. Podes enviar Pull Requests para ajudar a fazer as outras pessoas a tornar os seus projetos melhor oferecendo as tuas mudanças ao projeto original.

#### Dar Fork a um repositório

Para dar fork num repositório, clica no botão _fork_ localizado acima do repositório.

 ![Image](/sys-config/images/fork_forkbutton.png)

 Quando o fork acabar, serás levado á tua cópia do repositório.

#### Dá clone ao teu fork

- Entra na tua conta em [GitHub.com](https://github.com/) e no GitHub Desktop.
- No GitHub.com, navega até à barra de codificação do teu repositório.
- No lado direito do ecrã, clica em "Clone or download".
  ![Image](/sys-config/images/clone_clonebutton.PNG)
- Depois clica em "Open in Desktop". Isto abrir-te-á o GitHub Desktop.
  ![Image](/sys-config/images/clone_opendesktop.PNG)
- Cria uma pasta com o nome "**Drible**" no teu disco.
- Guarda o diretório da pasta "**Drible**"
- Clica em Clone.
- Seleciona a pasta "**Drible**" para guardares o clone.

### Fazer alterações e dar "push" a elas

Vai e faz alguma alterações ao projeto usando um editor de texto, como o Atom.

Quando tiveres pronto para enviar as tuas alterações,  Clica em "Stage All" no canto superior direito e clica depois em commit (não esquecer que tens que escrever o que fizeste em "Commit message").

Assim que fizeres isto, essencialmente disseste ao Git, “Okay, eu guardei as minhas alterações!” Podes continuar a fazer mais alterações e a guardá-las. Quando tiveres pronto para enviar as tuas alterações para o GitHub.com, dá "push" às tuas alterações clicando nas setas abaixo do botão _Commit_ e depois clicando em _Push_.


## Configuração do Atom

- Abre o Atom.
- Clica em "File" no canto superior esquerdo do ecrã.
- Em seguida, clica em "Open Folder" e seleciona a pasta onde tu guardaste o teu clone.

Agora já deves ter o clone do fork no teu Atom. Para teres certeza de que funcionou, a tua pasta deve ficar parecida a como ficou a pasta abaixo.

  ![Image](/sys-config/images/atom_folderexample.PNG)

## Issues

Vamos agora começar a fazer alterações no código. Para isso tens que escolher 5 tarefas nos issues e corrigir o que elas tem de errado. Para cada issue faz 1 commit relacionada com o issue.

Segue este [link](https://github.com/popperz0r/drible/issues) que te vai levar a uma pasta com certos problemas no fork. Com o que aprendeste de git , resolve apenas 5 desses problemas.

## GitHub Desktop

- Ao abrires o programa, em princípio o teu repositório, já deve estar selecionado.
- No Atom, sempre que fizeres uma alteração e guardares-la (Ctrl+S), a alteração irá te aparecer no GitHub Desktop no painel esquerdo.
- Depois onde diz "Summary", preenche com um título para a alteração que fizeste.
- Onde diz "Description", podes descrever o que fizeste (não obrigatório).
- Quando terminares os passos anteriores clicas em "Commit to gh-pages".
- E depois em cima clica em "Push to origin"
- Verifica se tens o "commit" guardado no repositório
