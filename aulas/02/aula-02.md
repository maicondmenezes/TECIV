# Aula 2 - Signals

Slides de Apresentação
---

A apresentação é um resumo do segundo capítulo do livro [base da disciplina](https://pergamum.ufpel.edu.br/pergamum/biblioteca_s/mostra_doc.php?arquivo=aHR0cHM6Ly9pbnRlZ3JhZGEubWluaGFiaWJsaW90ZWNhLmNvbS5ici9ib29rcy85NzgtODUtMjE2LTI4NDgtNA==) que aborda o tema de Sinais de Controle

Page: 1

---

## O Introdução

* Sinais são o ingrediente básico de circuitos eletrônicos;
* Sinais na forma de tensão ou corrente, imitam o que percebemos na natureza;
* Um importante distinção entre sinais: Analógio ou Digital;
* Os sinais podem ter uma representação de dados contínuos ou de amostra.
* Os sinais são estudados no tempo ou em outros domínios adequados: Laplace, Fourier ou transformada-Z.

Page: 2

---

## Sinais Simples

* Sinais representam informação
* Vamos considerar um exemplo comum: a temperatura de um forno.

![Figura A](img\fig-A.png)

* Os possíveis Sinais são: A temperatura do forno, temperatura e umidade da mistura de ingredientes, qualidade do bolo

Page: 3

---

## Caso Nominal e Pior Caso

* Definimos _nominal_ o caso em que a saída é o que esperamos de resposta quando aplicamos uma entrada específica.
* Pior Caso Máximo e Pior Caso Mínimo nos dáos sinais maiores o menores que o caso _nominal_

![Figura B](img/fig-B.png)

* Sinais não nominais podem ser possivelmente contrabalanceados para produzir resultados aceitaveis

Page: 4

---

## Tipos de Sinais

* Dependente de Tempo
* Dependente de coordenadas espaciais
* Elementos agruprados, elementos distribuídos
* Amplitude Contínua, Amplitude Discreta
* Sinais lógicos ou binários

Page: 5

---

## Sinais de Dados de Amostragem

![Figura C](img\fig-C.png)

* Tempo discreto ou dados de amostragem

Page: 6

---

## Sinal Constante

* Constante para um sistema eletrônico não corresponde ao seu equivalente matemático

![Figura-D](img\fig-D.png)
>**Observação:**
>
>_A tensão de alimentação e as referências de qualquer circuito eletrônico não são as esperadas, mas são sempre afetadas por erros ou mudanças estáticas. Esses erros devem ser mantidos abaixo de um determinado limite, pois afetam a operação do circuito._
Page: 7

---

## Ruídos que Corrompem o Sinal Constante

Existe também o ruído

![Figura E](img\fig-E.png)

* O ruído é um tipo especial de sinal que não carrega nenhum tipo de informação, mas ao contrário, corrompe a informação.

![Figura F](img\fig-F.png)

Page: 8

---

## Propriedades do Ruído

* A variação quadrática do ruído, σ <sup>2</sup><sub>n</sub>, é a média de tempo do quadrado do sinal de ruído

![Figura-G](img\fig-G.png)

* Frequentemente, apenas a raiz quadrada da variação é relatada e, para tensões de ruído, o símbolo usado pode ser simplesmente V<sub>n</syb>.

* Outras propriedades são a função de correlação automática e o espectro de ruído.

> _Se o valor do sinal for muito maior que o ruído, a forma de onda do sinal é facilmente distinguível. Por outro lado, se o sinal for menor que o ruído, ele será "submerso" por impulsos, tornando impossível reconhecê-lo._

Page: 9

---

## A Onda Senoidal

* Este é um importante tipo de sinal utilizado na eletrônica

![Figura-H](img\fig-H.png)

* A<sub>0</sub>, é a amplitude de pico, ω<sub>0</sub> a frequência angular e φ<sub>0</sub> a fase.
* O argumento do seno não é dimensionável (ou medido em radiantes), portanto, ω<sub>0</sub> é dado em rad/s.

![Figura-I](img\fig-I.png)

* f<sub>0</sub> é a frequência da onda senoidal medida em Hz (períodos por segundo).

Page: 10

---

## Ruído Afetando Ondas Senoidais

* Uma verdadeira onda senoidal

![Figura-J](img\fig-J.png)

* _rand(t)_ é uma função matemática que representa um sinal aleatório
* Temos ruído de amplitude e ruído de fase.

> **Tenha em Mente**
>
>_Um sinal de onda senoidal usado em eletrônica é sempre uma aproximação da função matemática **seno**. Seus limites são descritos por alterações distorcidas e termos de ruído._

Page: 11

---

## Onda senoidal ideal e efeitos de vários limites

![Figura K](img/fig-K.png)

* Distorção, ruído de amplitude, ruído de fase

* A taxa máxima de uma onda senoidal ocorre no cruzamento zero.

![Figura-L](img/fig-L.png)
![Figura-M](img/fig-M.png)

* Onda senoidal deslocada

![Figura-N](img/fig-N.png)

* Exponencial complexo, uma generalização da onda senoidal

![Figura-O](img/fig-O.png)

Page: 12

---

## O Sinal Degrau

![Figura-P](img/fig-P.png)

![Figura-Q](img/fig-Q.png)

* Isto é zero para _t < t<sub>0</sub>_ e tem amplitude _B<sub>0</sub>_ para _t >= t<sub>0</sub>_

* A combinação de Degraus dá origem aos _**pulsos**_

![Figura-R](img/fig-R.png)

* Pulsos repetidos com um determinado ciclo de função.

![Figura-S](img/fig-S.png)

Page: 13

---
