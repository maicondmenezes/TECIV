# Aula 2 - Signals

Slides de Apresentação
---

A apresentação é um resumo do segundo capítulo do livro [base da disciplina](https://pergamum.ufpel.edu.br/pergamum/biblioteca_s/mostra_doc.php?arquivo=aHR0cHM6Ly9pbnRlZ3JhZGEubWluaGFiaWJsaW90ZWNhLmNvbS5ici9ib29rcy85NzgtODUtMjE2LTI4NDgtNA==) que aborda o tema de Sinais de Controle

---

## O Introdução

* Sinais são o ingrediente básico de circuitos eletrônicos;
* Sinais na forma de tensão ou corrente, imitam o que percebemos na natureza;
* Um importante distinção entre sinais: Analógio ou Digital;
* Os sinais podem ter uma representação de dados contínuos ou de amostra.
* Os sinais são estudados no tempo ou em outros domínios adequados: Laplace, Fourier ou transformada-Z.

---

## Uma história engraçada

*O Homem que tinha 100 carros*

---

## Lista de Desejos (Objetivos)

* Tornar-se um especialistas em sistemas eletrônicos, conhecer suas propriedades básicas, estar apto para avaliá-las e reconhecer seus limites;
* Saber mais sobre os sinais usados e processados em sistemas eletrônicos para entender se um valor de parâmetro é bom ou ruim, aprender a gerar sinais de teste e usá-los para verificações de desempenho;
* Ler diagramas de circuitos, possivelmente, de relance, para ver onde os pontos críticos estão localizados e estimar o desempenho esperado;
* Conhecer sobre os blocos básicos usados em um sistema. otimizar o desempenho geral usando ferramentas de simulação computadorizadas e saber como conectar esses blocos para obter determinadas funções de processamento;
* Conhecer em detalhes como transistores funcionam e aprender tecnologias integradas modernas usadas para compreender transistores e circuitos integrados;
* Curiosidade sobre a modelagem de transistores e os princípios físicos e químicos subjacentes à sua fabricação;

---

## Pré-requisitos

* Uma experiência em matemática razoável, com capacidade para resolver equações diferenciais de primeira e segunda ordem;
* Conhecimento das leis de Kirchhoff e alguns conhecimentos sobre as transformadas de Laplace e Fourier. Familiaridade com a escrita e resolução de equações de malha e nodais;
* Bom conhecimento de uso do computador, como instalar programas e como usar a Web;

> **Portanto**
>
>*Refine a lista de desejos com base em sua atividade futura (indique qual é o perfil profissional que você deseja seguir). Na preparação desta viagem "eletrônica", verifique e expanda os pré-requisitos. Avalie sua forma e verifique se você está pronto.*

---

## Sistemas Eletrônicos

![Fig-A](https://i.ibb.co/SXVBhFk/fig-A.png)

---

## Montagem do Sistema

![Fig-B](https://i.ibb.co/1dW72gT/fig-B.png)

---

## Conhecendo Sistemas

![Fig-C](https://i.ibb.co/3YVXZhR/fig-C.png)
*O relógio digital com display de sete segmentos*

![Fig-D](https://i.ibb.co/Htyc2nj/fig-D.png)
*A incubadora de bebês, um exemplo de controle de feedback*

![Fig-E](https://i.ibb.co/MCH8YfT/fig-E.png)
*Diagrama de blocos de um sistema de comunicação sem fio*

>**Usar a hierarquia**
>
>*A melhor maneira de descrever um sistema complexo é dividi-lo em funções básicas, sem muitos detalhes, e descer hierarquicamente dentro de cada bloco para obter uma descrição mais detalhada até chegar ao fundo, no nível físico*

---

## Sistema com quantidades do mundo real

>**Sensores e Atuadores**
>
>Um sensor detecta uma quantidade do mundo real e gera um sinal elétrico com uma determinada sensibilidade. Um atuador gera uma quantidade do mundo real sob o controle de um sinal elétrico.

![Fig-F](https://i.ibb.co/ctm0kdk/fig-F.png)
*Todo o sistema envolvendo sinais do mundo real*

---

## Sensor Ótico

![Fig-G](https://i.ibb.co/5TwZ90n/fig-G.png)
*Diferentes tipos de fotodiodos e seção transversal do dispositivo*

---

## Sensor de Gás

![Fig-H](https://i.ibb.co/vkd0Wxn/fig-H.png)
*Sensor de gás micro-usinado com micro-placa quente.*

---

## Dispositivos micro-usinados

![Fig-I](https://i.ibb.co/bdDJxq2/fig-I.png)
a. Estrutura de Micro-Espelho (DMD<sup>TM</sup> Digital Micromirror Device) usado no DLP.

b. Microfotografia de um DMD (Cortesia da Texas Instruments)

---

## Sistemas em Pacote

![Fig-J](https://i.ibb.co/GkC9KNq/fig-J.png)
a. Microestrutura de um acelerômetro

b. Diagrama de Montagem de um sistema em pacote (systemon-package SOP)

c. Microfotografia de um SOP. (Cortesia da Silicon Designs, Inc.).

---

## Fases de Backend

* Empacotamento: vedação do sistema para garantir proteção e estabilidade mecânica.
* Testes no nível de wafer e triagem de chips
* Testes com Equipamentos de Teste Automatizados (ATE na sigla em inglês).
* Verificações de qualidade e confiabilidade (vida operacional em alta temperatura, HTOL, teste de panela de pressão ou esterilizador [autoclave](https://pt.wikipedia.org/wiki/Autoclave), descarga eletrostática, EDS, trava) [clique aqui para mais detalhes](https://en.wikipedia.org/wiki/Wafer_testing).
* Análise estatística de dados e estimativa de rendimento

> **Sobre a Testagem**
>
>Antes de distribuir circuitos ou sistemas eletrônicos é necessário verificar as funções por testagem. Se a entrada é uma quantidade elétrica não é difícil gerar alguma coisa parecida. A operação é bem mais complicada se o processo envolve quantidades não-elétricas que exigem usar na entrada um sinal não-elétrico controlado.

---

## O Computador e Microeletrônicos

![Fig-K](https://i.ibb.co/4YJqwLq/fig-K.png)

* Computador e programas de simulação de circuitos ou sistemas são ferramentas importantes para o projeto eletrônico;
* [**SPICE**](https://en.wikipedia.org/wiki/SPICE) é a primeira das ferramentas para simulção de circuitos. Ela foi desenvolvida em 1960 na Universidade de Berkeley, Califórnia. Agora muitas ferramentas estão disponíveis para síntese, verificação de circuito e outras necessidades.

> **Sugestão Amigável**
>
>Não permita que o computador seja mais rápido que o seu cérebro. Depois de receber qualquer simulação, pare e se questione. Você encontrará algo útil oculto nos resultados. Certamente - e surpreendentemente - você encontrará algo que ajuda a sua compreensão.

---

## Proficiências de um especialista

* **Noções Iniciais**: Conhecimento prévio em eletrônica significa compreender sistemas, arquiteturas, métodos de processamento, linguagens e técnicas de implementação;

* **Perícia inconsciente**: resulta da absorção lenta e de longo alcance das noções estudadas na escola, apreendida pela leitura de livros e resultante de histórias de sucesso e de falhas técnicas (muito mais importantes que sucessos fáceis).

* **Conhecimento específico**: é o conhecimento específico em uma das diferentes facetas da profissão.

* **Atitude no trabalho em equipe**: O espectro de conhecimentos necessários não é possuído por uma única pessoa. Trabalhar com outras pessoas, ser capaz de se comunicar, escrever relatórios e fazer apresentações técnicas é importante

* **Criatividade**: Um pouco de criatividade, balanceada com execução, procedimentos e cuidados com o estilo (ou hábito), é essencial;

* **Habilidade em Usar Ferramentas**: Para a eletrônica, vários programas de desenho assistido por computador (CAD, na sigla em inglês) obtêm uma previsão confiável da operação de circuitos e sistemas, antes de serem fabricados. Outras ferramentas facilitam o design do PCB

---

## O Processo de aprendizagem

*Existem cinco características diferentes:*

* **Aprender** como memorizar e armazenar informações simples que podem ser reproduzidas sem alterações significativas.

* **Aprender** como obter um aumento quantitativo no conhecimento, apenas coletando informações. Neste caso, as informações são armazenadas como noções aproximadas.

* **Aprender** como adquirir habilidades e métodos que podem ser retidos como conhecimento prévio e usados quando necessário.

* **Aprender** como compreender ou abstrair significado. Aprender envolve relacionar partes do assunto entre si e com o mundo real.

* **Aprender** como interpretar e entender os fatos de uma maneira diferente, que envolve compreender o mundo reinterpretando o conhecimento.

---

## Por que exemplos e simulações de computador são importantes?

Os benefícios esperados são:

* Superar a incredulidade: muitas vezes os resultados de uma descrição teórica feita com premissas duvidosas e aproximadas não são convincentes. O resultado parece simples demais, não suficientemente genérico ou talvez simplesmente inacreditável.

* Entender os limites de aproximação: os modelos simples usados ​​para cálculos manuais geralmente são muito aproximados e podem gerar resultados enganosos. No entanto, equações simples e regras simplificadas são fundamentais para direcionar a atividade do projetista.

* Reforçar o conhecimento: esse é um efeito benéfico geral do uso de exemplos e simulações em computador. Para a eletrônica, como muitas vezes o conhecimento não é codificado por equações confiáveis ​​ou regras razoáveis, o uso de exemplos e verificações por computador é particularmente útil.

* Aprender regras práticas: o uso de regras práticas é muito comum na atividade de projetistas especializados; com exemplos e simulações, é possível acumular conhecimento codificado em um conjunto de regras práticas.

---

## SPICE e sua análise

![Fig-L](https://i.ibb.co/KK63y2M/fig-L.png)

* Análise de corrente contínua: DC é um estudo de corrente contínua que determina o ponto operacional do circuito.

* Análise de CA: CA significa Corrente Alternada. A análise refere-se ao circuito linear ou assume comportamentos linearizados.

* Análise transitória: É o estudo da resposta às entradas que mudam no tempo.

* Análise de ruído: Feito para determinar a contribuição de sinais indesejados chamados ruído.

* Análise de Monte Carlo: Realiza um estudo estatístico de performances. Essa análise altera estatisticamente os parâmetros de projeto para reproduzir o efeito de erros de fabricação.

---

## Fluxo de Projeto Digital

![Fig-M](https://i.ibb.co/71xjHRL/fig-M.png)

---

## [ElvisLab](https://wikis.mit.edu/confluence/display/ILAB2/ELVIS+Lab)

![Fig-N](https://i.ibb.co/vXdRDv6/fig-N.png)