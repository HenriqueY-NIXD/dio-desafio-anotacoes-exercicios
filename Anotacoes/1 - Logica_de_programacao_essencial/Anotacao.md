# Introdução à lógica e à programação

### Lógica
> `Filosofia`
> 
> "Parte da filosofia que trata das formas do pensamento em geral (dedução, indução, hipótese, inferência etc.) e das operações intelectuais que visam à determinação do que é verdadeiro ou não."
> 
> **`Informática`**
> 
> **"Organização e planejamento das instruções, assertivas etc. em um algoritmo, a fim de viabilizar a implantação de um programa."**

### Lógica de programação
> "Significa apenas apenas contextualizar a lógica na programação de computadores/sistemas/redes/programas/algoritmos/protocolos/etc, buscando a melhor sequência de ações para `solucionar um problema`"

### Algoritmo
> "Uma `sequência lógica`, finita e definida de **instruções **que devem ser seguidas para **resolver um problema** ou executar uma tarefa."

### Fluxograma
> " É um `diagrama` que descreve um processo, sistema ou algoritmo de computador. São amplamente utilizados em várias áreas para documentar, estudar, planejar, melhorar e comunicar processos complexos por meio de diagramas claros e fáceis de entender."

![Imagem fluxograma](https://i.pinimg.com/originals/47/14/60/4714607b27f7b9668606674320884ae0.png)

### Variável
> "Região de memória (do computador) previamente identificada cuja finalidade é armazenar os **dados ou informações** de um programa por um determinado espaço de tempo"

#### ⮩ Variável - Constantes
> "As constantes são usadas na programação de computadores para armazenar **valores fixos**"

### Operadores aritméticos

Função | Operador
-------- | --------
Soma | +
Subtração | -
Multiplicação | *
Divisão | /
Potenciação | ^
Porcentagem | %

### Linguagens de programação
> "A linguagem de programação é um método padronizado, formado por um conjunto de regras sintáticas e semânticas, de implementação de um código fonte - que pode ser compilado e transformado em um programa de computador, ou usado como script interpretado (linguagens interpretadas) e ela vai permitir que o programador especifique precisamente quais os dados que o computador irá atuar, como estes dados serão armazenados ou transmitidos e, quais ações devem ser tomadas de acordo com as circunstâncias. Linguagens de programação podem ser usadas para expressar algoritmos com precisão."

### Linguagens de programação de alto/baixo nível:

#### ⮩ Alto nível
> "Aquela cuja sintaxe é voltada para o **entendimento humano**, assim esse tipo de linguagem é muito mais intuitivo, amigável e mais fácil de aprender. As linguagens de alto nível abstraem conceitos voltados para a máquina e sintetizam comandos"

**Exemplo:**
<div>
  <img src="https://docs.microsoft.com/pt-br/visualstudio/get-started/csharp/media/csharp-console-calculator-switch-code.png?view=vs-2022" alt="Imagem de código em C#">
</div>

#### ⮩ Baixo nível
>"As de baixo nível são voltadas para o **entendimento da máquina**. Por isso, elas têm uma sintaxe mais complexa e não contam com comandos tão intuitivos."

**Exemplo:**
<div>
  <img width="560" src="https://upload.wikimedia.org/wikipedia/commons/f/f3/Motorola_6800_Assembly_Language.png" alt="Imagem de código em Assembly">
</div>

### Linguagens de programação Compiladas/Interpretadas:

#### ⮩ Compiladas
> "As linguagens compiladas são **convertidas** diretamente na máquina em um **código de máquina** que o processador pode executar. Como resultado, elas tendem a ser mais rápidas e mais eficientes em sua execução do que as linguagens interpretadas. Elas também dão ao desenvolvedor mais controle sobre alguns aspectos do **hardware**, como o gerenciamento da memória e o uso da CPU."

##### Exemplos:
C, RUST, C#, JAVA e PASCAL

#### ⮩ Interpretadas
> "Linguagem interpretada é uma linguagem de programação em que o código fonte nessa linguagem é executado por um programa de computador chamado **interpretador**, que em seguida é executado pelo sistema operacional ou processador. Mesmo que um código em uma linguagem passe pelo processo de compilação, a linguagem pode ser considerada interpretada se o programa resultante não for executado diretamente pelo sistema operacional ou processador."

##### Exemplos:
JavaScript, Python, Ruby e Lua

### Concatenação
> "Operação que une o conteúdo de duas strings (cadeia de caracteres alfanuméricos)."

~~~C#
// C# babyyyyy ♪┏(・o･)┛♪┗ ( ･o･) ┓♪

string nome = "Henrique";
string sobrenome = "Yamada";
string nome_completo = "";

//Concatenação
nome_completo = nome + " " + sobrenome; 

//Outra maneira
nome_completo = string.Format("{0} {1}", nome, sobrenome); 

//Funciona apenas versão .NET 6 para frente
nome_completo = $"{nome} {sobrenome}"; 
~~~

### Matriz e vetor

#### Matriz
> "Uma matriz é uma coleção de variáveis de mesmo tipo, acessíveis com um unico nome e armazenados contiguamente na memória"

#### Vetores
> "Os vetores são matrizes de uma dimensão só"

### Estrutura de repetição
> " É uma estrutura que permite executar mais de uma vez o mesmo comando ou conjunto de comandos, de acordo com uma **condição** (lógica, número determinado de vezes e etc)"

~~~C#
// C# babyyyyy ♪┏(・o･)┛♪┗ ( ･o･) ┓♪

//Estrutura de repetição com "for"
for(int i=0; i<5; i++){
  //Código até contador bater com a condição
}

//Estrutura de repetição com "while"
while(/*condição*/){
  //Código até condição ser efetuada
}
~~~

### Estrutura Condicional
> "A Estrutura Condicional possibilita a escolha de um grupo de ações e estruturas a serem executadas quando determinadas condições são ou não satisfeitas. A Estrutura Condicional pode ser Simples ou Composta."

~~~C#
// C# babyyyyy ♪┏(・o･)┛♪┗ ( ･o･) ┓♪

// Estrutura SIMPLES
if(/*CONDIÇÃO*/){
  // Código que vai ser executado
}

// Estrutura COMPOSTA
if(/*CONDIÇÃO*/){
  // Código que vai ser executado
}
else{ 
  // Código que vai ser executado se a primeira condição não for atendida
}
~~~
