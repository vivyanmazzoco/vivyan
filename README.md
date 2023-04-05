TIPOS DE DADOS, ESTRUTURA CONDICIONAL, ESTRUTURA DE REPETIÇÃO DE LINGUAGEM JAVA, tipos de elementos visuais do android studio e switch case. 
tipos de dados, estrutura condicional e estrutura de repetição de linguagem Java, tipos de elementos visuais do android studio e switch case. 

ESTRUTURA CONDICIONAL-

*estrutura condicional simples (se - if)*

a estrutura condicional é baseada em uma condicao que se for atendendida o algoritmo toma uma descisão. exemplo: 

SE (A > B)ENTAO 
 escreva("o numero A é maior que o numero B")
FIMSE 

Agora se pensar na linguagem C o algoritmo mudara e seguira a segunte forma, exemplo:

if(a > b){
   printf("o numero %d maior que o numero %d", a, b);
}

uma pequena observacao  utilizando a linguagem C , o fundamento das estruturas condicionais são os mesmos para qualquer linguagem 
somente  alterando a sintaxe  particular de cada uma .



*estruturas condicional composta (senao - else)*

a diferença de uma condicional simples para uma composta, é que nesse caso mesmo se  a condiçao for FALSA nosso algoritmo 
tambem 
ira ter uma execuçao e seguira o programa. exemplo : 

se(A > B)ENTAO 
  exibir mensagem "o numero A e maior que o numero B"
  SENAO
  exibir mensagem "o numero A é menor que o numero B"
  
utilizando a linguagem C, o algoritmo ficara da seguinte maneira 

 if (A > B) {
    printf("o número %d é maior que o número %d", a, b);
} else {
    printf("o número %d é menor que o número %d", a, b);
}

Note que o código acima representa a seguinte condição: se o número A for maior que o número B, o algoritmo irá entender que 
a condição é verdadeira e deve exibir a mensagem “o número A é maior que o número B”, se esta condição não for atendida, ou 
seja, se ela for falsa.
Diferente do exemplo sobre estrutura condicional simples onde o algoritmo não tomava nenhuma ação, aqui ele toma uma decisão 
diferente, exibindo a mensagem “o número A é menor que o número B”.

*ESTRUTURAS DE REPETICAO*

para situacoes no qual precisamos executar a mesma tarefa mais de uma vez podemos utilizar a estrutura de repeticao dentro delas existem 3 estruturas, sendo elas enquanto(while), para(for) e 


*enquanto(while)*

Uma das condições que podemos usar é o enquanto, ou seja, enquanto a expressão booleana for verdadeira o algoritmo executa o 
bloco proposto, por fim é necessário que algo dentro do bloco altere a condição.
Podemos exemplificar o uso do enquanto supondo um algoritmo que retorne o resultado de uma tabuada, onde:

i sendo uma variável inteira de valor 1.

exemplo : 
i=1
escreva("digite o numero da tabuada")
 ENQUANTO (i <= 10)faca
	 result:= numtabuada * i
 	 i:= i+1 
    escreva ("o resultado é: ", result)
FIM DA CONDIÇÃO

ja na linguagem C ficaria da seguinte maneira :

while (i <= 10) {
       printf("9 x %d = %d\n", i, 9 * i);
       i++;
   }

a condicao que colocamos no algoritmo é de que a variavel 'i' ira repetir o programa ate que seja igual a 10. Enquanto isso sera exibido a mensagem "9 x i =(9*i)". a cada linha executada sera somado a variavel i que é igual a 1. essa soma é chamada de iteraçao, e muitos programadores referencia-se a ela como i++. quando i chegar ao valor de 11 o algoritmo ira parar de executar a soma e desta forma o resultado ira aparecer na tela


*para(for)*

a condiçao PARA  tem a mesma intencao que a ENQUANTO, 
porem ela é mais utilizado quando se sabe a quantidade de 
vezes que ira se repetir, como listar os valores de um 
vetor por exemplo. tambem vale ressaltar a legibilidade do 
codigo mais limpo, seguindo o mesmo exemplo da tabuada 
citado a cima temos um exemplo: 

escreva ("digite a tabuada: ")
leia(numtabuada)
 para i de 1 ate 10 passa 1 faca
  result:= numtabuada * i 
   i:= i +1
   escreva ("o numero da tabuada é: "result)
  fimpara
 fimalgoritmo 
 
 
 na linguagem C fica da seguinte maneira :
 
 for (int i = 1; i <= 10; i++) {
       printf("9 x %d = %d\n", i, 9 * i);
   }



Note que ao usar o PARA (for) o contador (a variável i) é inicializado e incrementado na própria condição do laço junto a expressão booleana a ser atendida, deixando o código mais limpo e sem a necessidade de criar variáveis adicionais.
No fim o retorno aguardado será o mesmo que do exemplo que utilizamos a do laço enquanto.



*estrutura repita- ate*

A estrutura de repetição Repita-até é utilizada quando
um conjunto de comandos deve ser executado
repetidamente, até que uma condição (expressão lógica)
seja verdadeira. ▫ O comando é executado uma vez.
▫ Após, a condição é testada: se ela for falsa, a lista de
comandos é executada novamente e este processo é
repetido até que a condição seja verdadeira, quando
então a execução prossegue pelo comando
imediatamente seguinte ao final da construção, exemplo:

numtabuada,result:real
i:inteiro

inicio
  i=1
  escreva ("digite o numero da tabuada: ")
  leia(numtabuada)
   repita 
    result:= numtabuada*i 
    i:= 1+1 
     screva("o resultado é : ", result)
   ate(i > 10)
fimalgoritmo 




*TIPOS-DE-ELEMENTOS-VISUAIS-DO-ANDROID-STUDIO*



Existem vários tipos de elementos visuais disponíveis no Android Studio, que permitem criar interfaces de usuário ricas e atraentes para seus aplicativos Android. Alguns dos principais elementos visuais incluem:

Views: são elementos de interface de usuário que podem ser adicionados a uma tela, como botões, caixas de texto, listas e imagens.

Layouts: são contêineres que permitem organizar as Views na tela, como RelativeLayout, LinearLayout e ConstraintLayout.

Fragments: são componentes reutilizáveis que podem ser usados,para construir telas dinâmicas e flexíveis.

Menu: permite criar menus e submenus para seu aplicativo.

Dialogs: são janelas pop-up que exibem informações ou solicitações de entrada do usuário.

Adapters: permitem vincular dados a uma lista ou grid de Views, como ListView, RecyclerView e GridView.

Toasts: são mensagens curtas que aparecem na parte inferior da tela, geralmente para exibir informações temporárias.

Animations: permitem criar transições e efeitos visuais em suas Views, como animações de rotação, transição de tela e transição de elemento compartilhado.

Esses são apenas alguns exemplos de elementos visuais disponíveis no Android Studio. O desenvolvedor pode também criar elementos personalizados para atender às suas necessidades específicas.


-Switch case

AA estrutura switch case é composta por uma expressão ou variável que é comparada com várias opções case. Cada caso é seguido por um bloco de código que será executado se a expressão ou variáveis testadas for igual ao valor do caso. Além disso, é possível incluir uma opção padrão (padrão) após os casos.

int opcao = 3;
switch (opcao) {
    case 1:
        System.out.println("Opção 1 selecionada.");
        break;
    case 2:
        System.out.println("Opção 2 selecionada.");
        break;
    case 3:
        System.out.println("Opção 3 selecionada.");
        break;
    default:
        System.out.println("Opção inválida.");
        break;
}




*TIPOS DE DADOS*

-tipo inteiro-

Números inteiros são tipicamente armazenados na memória em agrupamentos de 32-bits ou 64-bits, permitindo representar os seguintes intervalos de números:

para 32-bits: de −2.147.483.648 até 2.147.483.647 ou de -(231) até 231 − 1
para 64 bits: de −9.223.372.036.854.775.808 até 9.223.372.036.854.775.807 ou de -(263) até 263 − 1
Estes são os limites típicos da maioria das linguagens de programação.


-tipo float-

Você já encontrou esse outro tipo de dados numéricos anteriormente: o tipo “número real” Este tipo permite cálculos em números muito grandes ou muito pequenos (dados científicos, por exemplo), com um grau constante de precisão. Para que um dado numérico seja considerado como sendo do tipo float pelo Python, basta que ele contenha em sua formulação um elemento como um ponto decimal ou um expoente de 10.



*alfa numericos*
Até agora só manipulamos números. Mas um programa de computador também pode manipular caracteres alfabéticos, palavras, frases ou seqüências de quaisquer símbolos. Na maioria das linguagens de programação, existem estruturas de dados específicas para esse propósito chamadas “strings de caracteres”


-tipo string-

Uma variável do tipo string pode ser definida em primeira aproximação como uma seqüência de caracteres. Em um script python, podemos delimitar tal sequência de caracteres, entre aspas simples ou duplas

                   >>> frase1 = 'de alface'
                   >>> frase2 = '"Sim", ele respondeu,'
                   >>> frase3 = "eu gosto"
                   >>> print (frase2, frase3, frase1)
                   "Sim", ele respondeu, eu gosto de alface.


As 3 variáveis frase1, frase2 e frase3 são, portanto, variáveis do tipo string. Observe o uso de aspas para delimitar uma cadeia na qual existem aspas simples ou o uso de aspas simples para delimitar uma cadeia que contenha aspas. Observe também que a função print () insere um espaço entre os elementos exibidos. O caractere especial “" (barra invertida) permite algumas sutilezas complementares:

Primeiro, permite escrever em várias linhas um comando que seria muito longo para caber em um (isso se aplica a qualquer tipo de comando).
Dentro de uma string, a barra invertida permite que você insira um número de códigos especiais (quebras de linha, aspas simples, aspas e assim por diante)

-operacoes basicas com string-


É possível agrupar strings pequenas para construir strings maiores. Essa operação é chamada de concatenação e é executada no Python usando o operador + (esse operador, portanto, executa a operação de adição quando aplicado a números e a operação de concatenação quando é aplicado às strings). Exemplo:
              a = 'O peixinho'
              b = 'vai crescer'
              c = a + b
              print(c)
              O peixinho vai crescer

Também é possível determinar o comprimento (isto é, o número de caracteres) de uma string, usando a função integrada len():
                >>> ch = 'Georges'
                >>> print(len(ch))
                7
É possível converter um número real uma string que represente um número. Exemplo:
                      >>> ch = '8647'
                      >>> print(ch + 45)
                      TypeError: Can't convert 'int' object to str implicitly
                      >>> n = int(ch)
                      >>> print(n + 65)
                      8712
Neste exemplo, a função interna int() converte a string em um inteiro. Também seria possível converter uma string em um número real, usando a função float().





