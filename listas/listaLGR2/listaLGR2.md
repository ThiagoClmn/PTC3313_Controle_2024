# Lista Extra 2 - Lugar Geométrico das Raízes

## Exercício 1

Considere o sistema de controle com realimentação unitária com função de transferência de malha aberta dada por

$$
G(s)H(s) = K\dfrac{(s^2+5s+9)}{s^2(s+3)}
$$

Utilizando o método do lugar das raízes, determine $K$ de modo que as raízes dominantes tenham coeficiente de amortecimento $\xi = 0.5$.

<div style="border: 2px solid #ccc; padding: 10px; background-color: #0000;">

**Minha solução:**

...
</div>

## Exercício 2

Considere o sistema de controle com realimentação unitária com função de transferência de malha aberta dada por

$$
G_c(s)G(s) = \dfrac{7500K(1+0.2s)}{(s+1)(s+10)(s+50)(1+0.025s)}\text{ , }G_c(s) = \dfrac{K(1+0.2s)}{1+0.025s}
$$

Responda os itens a seguir:
a) Utilizando o método do lugar das raízes, determine o máximo valor de $K$ para estabilidade em malha fechada;
b) Suponha que o controlador como função de transferência $G_c(s)$ é trocado por um controlador proporcional i.e. $G_c(s) = K$. Utilizando o método do lugar das raízes, determine o máximo valor de $K$ para estabilidade em malha fechada.

<div style="border: 2px solid #ccc; padding: 10px; background-color: #0000;">

**Minha solução:**

### Letra 2a

...

### Letra 2b

...

</div>


## Desafio

Em 1892 o matemático francês Henri Padé (pronuncia-se *padê*) publicou um trabalho referente ao estudo de aproximações de funções utilizando-se funções racionais do tipo $p(x)/q(x)$, $q(x) \ne 0$. A essas representações propostas damos o nome de aproximantes de Padé. As aplicações são diversas no desenvolvimento, por exemplo,
de métodos computacionais com maior velocidade de convergˆencia utilizados em projetos de Controle.

No contexto da teoria de sistemas de controle, são muitos os casos em que lidamos com problemas com atraso i.e. $e^{−sT}$, $T \in\mathbb{R}_{>0}$ e, eventualmente, precisamos reescrever a função exponencial de uma forma que possamos utilizar propriedades mais interessante (e.g. diferenciação, integração). Fazendo-se uso da Fórmula de Taylor podemos gerar uma família de aproximantes de Padé para a função $f(x) = e^x$ da seguinte forma:

$$
e^x = \sum_{i\geq 0}\dfrac{x^i}{i!}\implies e^x = \dfrac{e^{x/2}}{e^{-x/2}}=\dfrac{
    1+x+\dfrac{x^2}{2}+\dfrac{x^3}{6}+...
}{
    1-x+\dfrac{x^2}{2}-\dfrac{x^3}{6}+...
}
$$

O i-ésimo termo do somatório a partir do qual decidimos truncar corresponde a aproximação para $n = i \geq 1$. Neste exercício, considere que você está desenvolvendo um projeto cuja representação matemática da função de transferência de malha aberta $L(s)$ de um sistema com realimentação unitária positiva é dada por

$$
L(s) = G(s)H(s) = \dfrac{Ke^{-sT}}{s+1}\text{ , }K\in\mathbb{R}_{>0}
$$

a) Mostre que uma aproximação para o atraso temporal é dada por

$$
e^{-sT} = \dfrac{\dfrac{2}{T} - s}{\dfrac{2}{T} + s}
$$

Dê exemplo de uma segunda aproximação temporal para o atraso (para $i=2$, por exemplo).

b) Usando o item anterior e considerando $T = 0.1$ s, desenhe o lugar geométrico das raízes para o sistema considerado e o diagrama de blocos.

c) Repita o item anterior considerando realimentação unitária negativa

<div style="border: 2px solid #ccc; padding: 10px; background-color: #0000;">

**Minha solução:**

### Exercício A do desafio

...

### Exercício B do desafio

...

### Exercício C do desafio

...

</div>