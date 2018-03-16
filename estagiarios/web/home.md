## Introdução à Web

Nothing Written

## Ferramentas Necessárias

### ATOM

[Atom](https://atom.io/) é um editor de texto, podes fazer download [aqui](https://atom.io/), vamos utilizar esta ferramenta mais a frente.

#### O que é, para que serve e o que procurar num editor de texto?

Essencialmente, um editor de texto é um programa que te permite criar e editar variadas linguagens de programação.

Editores de texto são frequentemente equipados com sistemas operacionais ou pacotes de desenvolvimento de software, e pode ser usado para alterar arquivos de configuração e linguagem de programação de código fonte.

- Fácil de usar e navegar.
- Ferramenta de encontrar e mudar (para que possas uma mudar uma palavra no ficheiro inteiro sem muito esforço).
- Cortar, copiar e colar.
- Syntax highlighting (torna mais fácil ler o código e encontrar algum erro).
- Aparência Customizável (tal como mudar a fonte da letra, esquema de cores, etc., do teu editor).
- Extensibilidade (que forneça algum mecanismo de plugin, ou que seja programável , para que um programador possa costumizar o editor com características adicionais).


## Git

### O que é um git?

Git é um tipo de sistema de controlo de versões que torna mais fácil monitorizar as alterações no ficheiro. Por exemplo, quando editas um ficheiro, git pode ajudar te a determinar exatamente oque mudou, quando mudou e porquê.

É útil para coordenar trabalho entre múltiplas pessoas num projeto, e para monitorizar o progresso ao longo do tempo guardando "checkpoints".

Existe vários tipos de alojamento online tais como o [GitHub](https://github.com/) e o [BitBucket](https://bitbucket.org/).

### Compreender o git

Git usa muita analogias relacionadas com "árvores". Pensa na código principal como se fosse o tronco de uma árvore 🎄.

Sempre que adicionares mais alterações (commits), o teu tronco fica maior. Mesmo que apagues o código, ainda é considerado uma mudança e isso faz com que o tronco cresça. É como a ferramenta “undo” [desfazer] funciona num editor de texto (tipo o Word), salva todas as alterações, incluindo o apagar.

Pode andar para cima e para baixo no tronco — equivalente a andar para a frente e para trás no tempo — por verificar os tais "checkpoints" específicos.

### O que é Branching?

Muito dos projetos têm uma acumulação de características novas para adicionar e bugs para arranjar. Quando te queres dirigir a um destes problemas, uma maneira seria aumentar a árvore e comprometer-se diretamente ao tronco. Isto funciona perfeitamente para projetos pequenos ou projetos onde és a única pessoa a fazer alterações, mas e se múltiplas pessoas estiverem a trabalhar ao mesmo tempo? É muito fácil atrapalharmo-nos e acabar por dar conflitos de alterações.

A solução é branching (ramificar). Em vez de te comprometeres ao tronco, crias o teu próprio ramo e trabalhas a partir daí. Assim tornas o ramo maior em vez do tronco.

Ao visualizar ramos, normalmente eles são desenhados lateralmente para ocupar menos espaço. Imagina que o seguinte é uma árvore, tombada, com as raízes á esquerda. Cada círculo é uma alteração. Quanto mais para a direita o círculo é, mais recentemente foi alterado:

  ![Image](/sys-config/images/branching_exemplo1.png)
Legenda: Trunk = tronco / Branch = ramo / Root = raíz

Existe um tronco azul e um ramo verde. Existe várias alterações em ambos, mostrado cronologicamente da esquerda para a direita. O teu ramo começa no 2º tronco (Trunk #2). Enquanto trabalhas no teu ramo [ alterações no 1º e 2º ramo ( Branch #1 e Branch #2 )], alguém trabalhou diretamente no tronco [ alterações no 3º e 4º tronco ( Trunk #3 e Trunk #4 )]. Essas alterações ainda não afetaram o teu ramo ainda, o teu ramo está desatualizado.

## Submeter as tuas alterações

Agora tens as tuas alterações num ramo e o teu objetivo é eventualmente voltar a passar-los para o tronco como parte da “oficial” código base.

Uma vez que testado as tuas alterações, precisarás de a partilhar com a tua "equipa". Isto é feito através de um Pull Request (PR) ou um Merge Request (MR) — são a mesma coisa, o termo apenas depende de que software estás a usar (exemplo: GitHub). Estás a pedir que as tuas alterações sejam alteradas e convergidas com o código base.

  ![Image](/sys-config/images/branching_exemplo2.png)
Legenda: Trunk = tronco / Branch = ramo / Root = raíz / Merge = convergir


### Como obter o git?

[GitHub Desktop](https://desktop.github.com/) (para Windows e Mac)

#### Agora vamos por isto tudo em prática. Clica [aqui](/sys-config/estagiarios/web/hello-drible)
