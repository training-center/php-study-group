# Fonte

### [dojopuzzles.com - Números Romanos](http://dojopuzzles.com/problemas/exibe/numeros-romanos/)

# Desafio

O sistema de numeração romana (ou números romanos) desenvolveu-se na Roma Antiga e utilizou-se em todo o seu Império. Neste sistema as cifras escrevem-se com determinadas letras, que representam os números. As letras são sempre maiúsculas, já que no alfabeto romano não existem as minúsculas, as letras são I, V, X, L, C, D e M.

Sua tarefa é desenvolver um programa que converta números indo-arábicos para o formato romano e vice-versa. As regras para a formação dos números romanos são apresentadas a seguir.

Cada letra corresponde a um determinado valor:

 - I = 1
 - V = 5
 - X = 10
 - L = 50
 - C = 100
 - D = 500
 - M = 1000

Agrupando as letras acima, podemos representar os números de acordo com um conjunto de regras:

- Com exceção de V, L e D, os outros numerais podem se repetir no máximo três vezes:
    - III = 3
    - XXX = 30
    - CCC = 300
    - MMM = 3000
- Quando escritos à direita de numerais maiores, I, X e C somam-se aos valores dos primeiros:
    - VIII   = 5 + 1 + 1 + 1 = 8
    - LXII   = 50 + 10 + 1 + 1 = 62
    - CLVIII = 158
    - MCXX   = 1000 + 100 + 10 + 10 = 1120
- Mas se os numerais I, X e C estiverem à esquerda dos maiores, seus valores são subtraídos como, por exemplo, em:
    - IV = 5 - 1 = 4
    - IX = 10 - 1 = 9
    - XC = 100 - 10 = 90

# Dicas

- Fique atento as regras de calculo!

# Resultado esperado

#### Exemplo:

- **Entrada:** 
    - MCXX (1000 + 100 + 10 + 10)
- **Saída**
    - 1120