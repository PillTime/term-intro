# Introdução ao Terminal

Bem-vindo à **Introdução ao Terminal** do NuCC.
Este guia tem como objetivo ensinar-te o essencial para poderes usar o terminal.

Não vale a pena estar a preencher isto com texto desnecessário, por isso vamos começar já.

## Terminal e Shell

Começa por abrir o terminal.
Dependendo da distribuição Linux que estás a usar, o terminal pode ter nomes diferentes por causa do
  ambiente que a tua distribuição usa.
Nalgums chama-se **Gnome Terminal**, noutros **Konsole**, e noutros outra coisa qualquer, mas se
  procurares simplesmente por **`terminal`** deve-te aparecer a aplicação correta, que vai ter mais
  ou menos este aspeto:
![empty terminal](./img/term00.png)

Na realidade temos dois programas a correr aqui.
Primeiro temos o terminal em si, que trata só da parte gráfica, como por exemplo o tipo de letra e
  tamanho da janela.
O segundo programa é uma **shell**, e está a correr dentro do terminal.
A shell é o programa que dá output do texto (incluindo o que aparece ao iniciar o terminal), e lê,
  interpreta, e executa os comandos que lhe dás.

_**Basicamente, o cérebro do terminal é a shell.**_

Existem várias shells, mas quase todas as distribuições usam a mesma por predefinição: **`bash`**.

<details>
  <summary>NOTA: Acerca do nome <b>terminal</b></summary>
  Na realidade um terminal é o ecrã preto que (possivelmente) aparece quando ligas o computador.
  O "terminal" que estamos a usar é um <b>emulador de terminal</b>, mas não vale a pena estar a ser
    tão pedante.
</details>

### Prompt

O **prompt** é o texto que está no screenshot acima, e aparece sempre que a shell está à espera de
  um comando.
Serve para indicar o estado atual da shell.

O prompt é algo que pode ser configurado, e distribuições diferentes provavelmente vão ter o prompt
  ligeiramente (ou muito) diferente umas das outras.
Para não estar a complicar muito, vamos analisar o prompt do screenshot.

 - `[`: Só um separador visual, não tem significado especial.
 - `carlos`: Nome do utilizador atual.
 - `@`: Outro separador, no entanto o `@` costuma ser usado para indicar uma localização.
 - `armix`: Hostname do sistema atual.
 - `~`: Pasta atual. Nas shells, `~` indica a pasta pessoal do utilizador atual.
 - `]`: Mais um separador visual, não tem significado especial.

E no fim, o prompt acaba com um `$`, que indica o final do prompt e também indica que estamos com um
  utilizador normal.
Normalmente as shells estão configuradas para mostrar `#` quando estamos com o utilizador `root`,
  que no Linux é o utilizador que serve de administrador, com acesso total ao sistema.

## `pwd`

Vamos então começar com comandos.

O primeiro comando que vamos ver é bastante simples, e chama-se `pwd` (**P**rint **W**orking
  **D**irectory).
Experimenta correr o comando, vais ter um output do género:
![pwd command](./img/term01.png)

No teu caso a pasta deve ter um nome diferente por causa do nome to teu utilizador, mas também deve
  estar dentro da pasta `/home/`, que é a pasta onde as pastas pessoais costumam ficar.

O `pwd` é raramente usado, não por ser um comando bastante simples, mas porque a informação que ele
  dá já está disponível no prompt.
Experimenta abrir o teu explorador de ficheiros e carregar com o botão direito do rato numa pasta
  qualquer.
Deve-te aparecer uma opção do estilo "abrir o terminal aqui" (se não tiveres essa opção, azar):
![open in terminal option](./img/file00.png)

Carrega nela e executa `pwd` no terminal que te aparece:
![pwd in other folder](./img/term02.png)

Experimenta fazer isto em mais pastas, ou se quiseres, podes passar já para o próximo comando.

<details>
  <summary>CURIOSIDADE: Diferença entre <b>pastas</b> e <b>diretórios</b></summary>
  Não há realmente uma diferença entre os dois termos.
  "Diretório" era o termo usado antigamente, e com o surgimento de GUIs, o nome "pasta" começou a
    ser utilizado.

  Há quem diga que há realmente uma diferença, e até podem ter alguma razão (aceito
    [este](https://retrocomputing.stackexchange.com/a/26176) argumento), mas há dois casos que não
    tem razão absolutamente nenhuma:
  <ul>
    <li>Se disserem que "diretório" é o quando usas o terminal e "pasta" é o quando usas GUI.</li>
    <li>Se disserem que é "pasta" no Windows e macOS, e "diretório" nos outros SOs.</li>
  </ul>
  Esse pessoal tem só problemas na cabeça.
</details>

## `ls`

### Flags

#### Ficheiros Escondidos

## `man`

## `mkdir`

## `cd`

## `clear`

### Ctrl + D

## `touch`

## `rmdir`

## `rm`

### Perigos do `rm`

## `cp`

## `mv`

## `echo`

### Variáveis de Ambiente

## `cat`

## `less`

## `grep`

## `sudo`

### Perigos do `sudo`

### Instalação de Aplicações

## Perigos de Comandos na Internet

### explainshell.com

## Operadores

### Pipes

### `&&`, `||`, e `;`

### `&`

#### `kill`
