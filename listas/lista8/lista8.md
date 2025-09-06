# Lista 8 - Revisão para P2

## Questão 1
Um engenheiro tem a tarefa de projetar um sistema de controle em malha fechada proporcional para a planta instável
$$
G(s) = \dfrac{s+3}{s(s-9)}
$$

1. Esboce o diagrama de Nyquist completo de $G(s)H(s)$ considerando que $H(s) = K$ .
2. Usando critério de Estabilidade de Nyquist, determine a faixa de valores de $K$ para que o sistema em malha fechada seja estável.


## Questão 2
Seja a função de transferência em malha aberta dada por
$$
G(s)H(s) = \dfrac{K(s-1)}{s^2(s+2)}
$$
onde $K>0$.

1. Esboce os diagramas de Bode desta função de transferência.
2. Esboce o diagrama de Nyquist para $K > 0$.
3. Determine, usando critério de estabilidade de Nyquist, a estabilidade em malha fechada para $K > 0$.

## Questão 3
Dada a planta
$$
G(s) = \dfrac{1}{s(s+5)(s+3)}
$$
pede-se:

1. Projete um compensador em malha fechada tal que o erro estacionário à rampa seja 0, 1 e a margem de fase seja de 30 ◦ . Verifique se a nova margem de fase real atende às especificações.
**Dica**: desenhe os diagramas de Bode.
2. Calcule a Margem de ganho para este sistema compensado.
3. Calcule a função de transferência em malha fechada. Existem polos dominantes?

## Questão 4
Seja a planta $G(s) = \dfrac{s+4}{s(s+1)(s+2)}$. Deseja-se projetar um sistema de controle em malha fechada de
modo que $e_{ss} = 0.016$ e a margem de fase seja de 30°. Pede-se:
1. Determine um compensador por avanço de fase que atenda estas especificações.
2. Verifique se a margem de fase projetada é próxima da especificada.
3. Determine a banda-passante do sistema.