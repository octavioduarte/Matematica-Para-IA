
### Números e Representações
Na matemática, uma variedade de números e suas representações são usados para diferentes propósitos. Aqui está uma lista dos tipos mais comuns de números e suas representações:

**Números Naturais (N)**: São os números inteiros não-negativos. Incluem 0, 1, 2, 3, 4, ... Eles são usados para contar e ordenar.

**Números Inteiros (Z)**: Incluem todos os números naturais, seus opostos negativos e o zero. Portanto, são ..., -3, -2, -1, 0, 1, 2, 3, ...

**Números Racionais (Q)**: São os números que podem ser expressos como a fração de dois inteiros, onde o denominador não é zero. Incluem números como 1/2, -3/4, 5, 0.75, etc.

**Números Irracionais**: São números que não podem ser expressos como uma fração simples de dois inteiros. Incluem números como π (pi) e √2. Esses números têm uma expansão decimal infinita não periódica.

**Números Reais (R)**: Incluem todos os números racionais e irracionais. Os números reais podem ser representados em uma linha numérica.

**Números Complexos (C)**: Incluem todos os números que podem ser expressos na forma a + bi, onde a e b são números reais e i é a unidade imaginária. A unidade imaginária é uma extensão dos números reais e foi criada para solucionar equações que não possuem soluções dentro do conjunto dos números reais. A unidade imaginária é representada pela letra i, que é definida como a raiz quadrada de −1. 

**Números Primos**: São números maiores que 1 que têm exatamente dois divisores distintos: 1 e eles mesmos. Exemplos incluem 2, 3, 5, 7, 11, ...

Cada um desses tipos de números tem sua própria utilidade e aplicação em diferentes áreas da matemática e ciência.
### PEMDAS
A regra PEMDAS é um acrônimo usado para ajudar a lembrar a ordem das operações em matemática. Significa:

- Parênteses
- Expoentes (ou potências)
- Multiplicação e Divisão (da esquerda para a direita)
- Adição e Subtração (da esquerda para a direita)

Esta regra é um guia para determinar qual operação matemática deve ser realizada primeiro em uma expressão matemática. Aqui está como ela funciona:

Parênteses: Realize primeiro as operações dentro dos parênteses. Isso também se aplica a colchetes [ ] e chaves { }.

Expoentes: Em seguida, calcule as potências e as raízes.

Multiplicação e Divisão: Estas operações são realizadas da esquerda para a direita. Elas têm a mesma prioridade, o que significa que você deve fazer a que aparecer primeiro.

Adição e Subtração: Por último, faça as operações de adição e subtração, também da esquerda para a direita. Assim como na multiplicação e divisão, adição e subtração têm a mesma prioridade.

É importante notar que, embora a regra PEMDAS seja um guia útil, ela não substitui a compreensão das propriedades matemáticas e de como as expressões são construídas e simplificadas.
### O Que São Equações?

Equações são cálculos em que uma ou mais variáveis representam valores desconhecidos. Neste Lab, você aprenderá algumas técnicas fundamentais para resolver equações usando programação.
### Resolvendo Equações com 1 Passo

Considere a seguinte equação:

\begin{equation}x + 12 = -37\end{equation}

O desafio aqui é encontrar o valor de **x** e para isso precisamos *isolar a variável*. Nesse caso, precisamos colocar **x** em um lado do sinal "=" e todos os outros valores no outro lado. Para isso, seguiremos estas regras:

1. Usar operações opostas para cancelar os valores que não queremos de um lado. Nesse caso, o lado esquerdo da equação inclui uma adição de 12, então vamos cancelar isso subtraindo 12 e o lado esquerdo da equação se torna **x + 12 - 12**.
2. O que quer que você faça de um lado, você também deve fazer do outro lado. Nesse caso, subtraímos 12 do lado esquerdo, portanto também devemos subtrair 12 do lado direito da equação, que se torna **-37 - 12**.

Nossa equação agora fica assim:

\begin{equation}x + 12 - 12 = -37 - 12\end{equation}

Agora podemos calcular os valores em ambos os lados. No lado esquerdo, 12 - 12 é 0, então ficamos com:

\begin{equation}x = -37 - 12\end{equation}

O que produz o resultado **-49**. Nossa equação agora está resolvida, como você pode ver aqui:

\begin{equation}x = -49\end{equation}

É sempre uma boa prática verificar seu resultado inserindo o valor da variável que você calculou na equação original e garantindo que ele seja verdadeiro. Podemos fazer isso facilmente usando algum código Python simples.
# Atribuindo valor a x
x = -49
# Comparando as expressões
x + 12 == -37
# Atribuindo valor a x
x = 1
# Comparando as expressões
x + 12 == -37
### Resolvendo Equações com 2 Passos

O exemplo anterior foi bastante simples - você provavelmente poderia resolvê-lo em sua cabeça. Então, que tal algo um pouco mais complexo?

\begin{equation}3x - 2 = 10 \end{equation}

Como antes, precisamos isolar a variável **x**, mas desta vez faremos isso em duas etapas. 

A primeira coisa que faremos é cancelar as *constantes*. Uma constante é qualquer número que se mantém sozinho, então, neste caso, o 2 que estamos subtraindo do lado esquerdo é uma constante. Usaremos uma operação oposta para cancelá-lo no lado esquerdo, portanto, como a operação atual é subtrair 2, adicionaremos 2; e é claro que tudo o que fazemos no lado esquerdo também precisamos fazer no lado direito, então após o primeiro passo, nossa equação fica assim:

\begin{equation}3x - 2 + 2 = 10 + 2 \end{equation}

Agora os -2 e +2 à esquerda se cancelam, e à direita, 10 + 2 é 12; então a equação agora é:

\begin{equation}3x = 12 \end{equation}

OK, hora do passo dois - precisamos lidar com os *coeficientes* - um coeficiente é um número que é aplicado a uma variável. Nesse caso, nossa expressão à esquerda é 3x, o que significa x multiplicado por 3; para que possamos aplicar a operação oposta para cancelá-lo, desde que façamos o mesmo para o outro lado, ficaria assim:

\begin{equation}\frac{3x}{3} = \frac{12}{3} \end{equation}

3x &divide; 3 é igual a x, então agora isolamos a variável.

\begin{equation}x = \frac{12}{3} \end{equation}

E podemos calcular o resultado como <sup>12</sup>/<sub>3</sub> que é **4**:

\begin{equation}x = 4 \end{equation}

Vamos verificar esse resultado usando Python:
# Atribuindo valor a x
x = 4
# Comparando as expressões
3 * x - 2 == 10
### Resolvendo Equações Combinando Termos

Termos semelhantes são elementos de uma expressão que se relacionam com a mesma variável ou constante (com a mesma *ordem* ou *exponencial*, que discutiremos mais adiante). Por exemplo, considere a seguinte equação:

\begin{equation}\textbf{5x} + 1 \textbf{- 2x} = 22 \end{equation}

Nesta equação, o lado esquerdo inclui os termos **5x** e **- 2x**, ambos representando a variável **x** multiplicada por um coeficiente. Observe que incluímos o sinal (+ ou -) na frente do valor.

Podemos reescrever a equação para combinar estes termos semelhantes:

\begin{equation}\textbf{5x - 2x} + 1 = 22 \end{equation}

Podemos então simplesmente realizar as operações necessárias nos termos semelhantes para consolidá-los em um único termo:

\begin{equation}\textbf{3x} + 1 = 22 \end{equation}

Agora, podemos resolver isso como qualquer outra equação de duas etapas. Primeiro vamos remover as constantes do lado esquerdo - neste caso, há uma expressão constante que adiciona 1, então vamos usar a operação oposta para removê-la e fazer o mesmo do outro lado:

\begin{equation}3x + 1 - 1 = 22 - 1 \end{equation}

Isso nos dá:

\begin{equation}3x = 21 \end{equation}

Então vamos lidar com os coeficientes - neste caso x é multiplicado por 3, então vamos dividir por 3 em ambos os lados para remover o coeficiente:

\begin{equation}\frac{3x}{3} = \frac{21}{3} \end{equation}

Isso nos dá como resposta:

\begin{equation}x = 7 \end{equation}
# Atribuindo valor a x
x = 7
# Comparando as expressões
5 * x + 1 - 2 * x == 22
### Trabalhando com Frações - Exemplo 1

Algumas das etapas para resolver as equações acima envolveram trabalhar com frações - que em si são apenas operações de divisão. Vamos dar uma olhada em um exemplo de uma equação em que nossa variável é definida como uma fração:

\begin{equation}\frac{x}{3} + 1 = 16 \end{equation}

Seguimos a mesma abordagem de antes, primeiro removendo as constantes do lado esquerdo - então subtraímos 1 de ambos os lados.

\begin{equation}\frac{x}{3} = 15 \end{equation}

Agora precisamos lidar com a fração à esquerda para que fiquemos com apenas **x**. 

A fração é <sup>x</sup>/<sub>3</sub> que é outra maneira de dizer *x dividido por 3*, então podemos aplicar a operação oposta para ambos os lados. Nesse caso, precisamos multiplicar ambos os lados pelo denominador sob nossa variável, que é 3. 

Para facilitar o trabalho com um termo que contém frações, podemos expressar números inteiros como frações com denominador 1; então, à esquerda, podemos expressar 3 como <sup>3</sup>/<sub>1</sub> e multiplicamos com <sup>x</sup>/<sub>3</sub>. 

Observe que a notação para multiplicação é um símbolo **&bull;** em vez do operador de multiplicação *x* padrão (que causaria confusão com a variável **x**) ou o símbolo de asterisco usado pela maioria das linguagens de programação.

\begin{equation}\frac{3}{1} \cdot \frac{x}{3} = 15 \cdot 3 \end{equation}

Isso nos dá o seguinte resultado:

\begin{equation}x = 45 \end{equation}
# Atribuindo valor a x
x = 45
# Comparando as expressões
x / 3 + 1 == 16
# Comparando as expressões
1 + x / 3 == 16
### Trabalhando com Frações - Exemplo 2

Vejamos outro exemplo, em que a variável é um número inteiro, mas seu coeficiente é uma fração:

\begin{equation}\frac{2}{5}x + 1 = 11 \end{equation}

Como de costume, começaremos removendo as constantes da expressão variável; então, neste caso, precisamos subtrair 1 de ambos os lados:

\begin{equation}\frac{2}{5}x = 10 \end{equation}

Agora precisamos cancelar a fração. A expressão equivale a dois quintos vezes x, então a operação oposta é dividir por <sup>2</sup>/<sub>5</sub>; mas uma maneira mais simples de fazer isso com uma fração é multiplicá-la por sua *recíproca*, que é apenas o inverso da fração, neste caso <sup>5</sup>/<sub>2</sub>. Claro, precisamos fazer isso para os dois lados:

\begin{equation}\frac{5}{2} \cdot \frac{2}{5}x = \frac{10}{1} \cdot \frac{5}{2} \end{equation}

Isso nos dá o seguinte resultado:

\begin{equation}x = \frac{50}{2} \end{equation}

Que podemos simplificar para:

\begin{equation}x = 25 \end{equation}
# Atribuindo valor a x
x = 25
# Comparando as expressões
2 / 5 * x + 1 == 11
### Equações Com Variáveis em Ambos os Lados

Até agora, todas as nossas equações tiveram um termo variável em apenas um lado. No entanto, os termos variáveis podem existir em ambos os lados.

Considere esta equação:

\begin{equation}3x + 2 = 5x - 1 \end{equation}

Desta vez, temos termos que incluem **x** em ambos os lados. Vamos usar exatamente a mesma abordagem para resolver esse tipo de equação que fizemos para os exemplos anteriores. Primeiro, vamos lidar com as constantes adicionando 1 a ambos os lados. Isso elimina o -1 à direita:

\begin{equation}3x + 3 = 5x \end{equation}

Agora podemos eliminar a expressão variável de um lado subtraindo 3x de ambos os lados. Isso elimina o 3x à esquerda:

\begin{equation}3 = 2x \end{equation}

Em seguida, podemos lidar com o coeficiente dividindo ambos os lados por 2:

\begin{equation}\frac{3}{2} = x \end{equation}

Agora isolamos x. Parece um pouco estranho porque geralmente temos a variável do lado esquerdo, então se isso te deixa mais confortável você pode simplesmente inverter a equação:

\begin{equation}x = \frac{3}{2} \end{equation}

O resultado é 1,5.
# Atribuindo valor a x
x = 1.5 
# Comparando as expressões
3*x + 2 == 5*x -1
### Usando a Propriedade Distributiva

A propriedade distributiva é uma lei matemática que nos permite distribuir a mesma operação para termos entre parênteses. Por exemplo, considere a seguinte equação:

\begin{equation}\textbf{4(x + 2)} + \textbf{3(x - 2)} = 16 \end{equation}

A equação inclui duas operações entre parênteses: **4(*x* + 2)** e **3(*x* - 2)**. Cada uma dessas operações consiste em uma constante pela qual o conteúdo entre parênteses deve ser multiplicado: por exemplo, 4 vezes (*x* + 2). 

A propriedade distributiva significa que podemos obter o mesmo resultado multiplicando cada termo entre parênteses e somando os resultados, então para a primeira operação entre parênteses, podemos multiplicar 4 por *x* e somar 4 vezes +2; e para a segunda operação entre parênteses, podemos calcular 3 vezes *x* + 3 vezes -2). Observe que as constantes entre parênteses incluem o sinal (+ ou -) que as precede:

\begin{equation}4x + 8 + 3x - 6 = 16 \end{equation}

Agora podemos agrupar nossos termos semelhantes:

\begin{equation}7x + 2 = 16 \end{equation}

Em seguida, movemos a constante para o outro lado:

\begin{equation}7x = 14 \end{equation}

E agora podemos lidar com o coeficiente:

\begin{equation}\frac{7x}{7} = \frac{14}{7} \end{equation}

O que nos dá a resposta:

\begin{equation}x = 2 \end{equation}
# Atribuindo valor a x
x = 2
# Comparando as expressões
4 * (x + 2) + 3 * (x - 2) == 16
%reload_ext watermark
%watermark -a "Data Science Academy"
#%watermark -v -m
# Fim