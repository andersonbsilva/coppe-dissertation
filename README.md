# Thor

Este repositório contém minha dissertação de mestrado defendida em 2011 na COPPE/UFRJ.

This repository contains my master degree dissertation.

---

<p align="center">

Resumo da Dissertação apresentada à COPPE/UFRJ como parte dos requisitos
necessários para a obtenção do grau de Mestre em Ciências (M.Sc.)

**THOR: UM SISTEMA DE DISTRIBUIÇÃO DE VÍDEO PAR-A-PAR BASEADO NA TECNICA D1HT**
</p>

Anderson Borges da Silva
Setembro/2011

Orientador: Claudio Luis de Amorim
Programa: Engenharia de Sistemas e Computação

Neste trabalho apresenta-se o Thor, um sistema peer-to-peer de distribuição de
vídeo sob demanda baseada na técnica D1HT. A D1HT é uma Tabela Hash Distribuída que resolve as consultas em apenas um salto e com baixo custo de manutenção de suas tabelas. Utilizando-se desta técnica, desenvolveu-se uma camada
chamada de D1HThor que é responsável pelo gerenciamento dos segmentos de dados
que formam o vídeo distribuído. Esse gerenciamento é feito de forma a garantir que
se algum membro da rede possuir um vídeo, este será sempre encontrado por todos
os demais. O Thor utiliza-se então desta camada para realizar a busca e distribuição
dos vídeos. Foram realizados experimentos com alterações de tamanho de buffer e
taxa de chegada dos nós. Os resultados demonstram que a aplicação possui uma
alta escalabilidade garantindo uma boa qualidade de serviço.

---
<p align="center">

Abstract of Dissertation presented to COPPE/UFRJ as a partial fulfillment of the
requirements for the degree of Master of Science (M.Sc.)

**THOR: A PEER-TO-PEER DISTRIBUTION VIDEO SYSTEM BASED ON D1HT TECHNIQUE**
</p>

Anderson Borges da Silva
September/2011

Advisor: Claudio Luis de Amorim
Department: Systems Engineering and Computer Science

This work presentes Thor, a peer-to-peer distribution video system based on
D1HT technique. The D1HT is a Distributed Hash Table that solves the lookups in
just one hop with low maintenance cost of its tables updates. Using this technique,
it was developed a layer called D1HThor, which is responsible for managing data
segments that form the distributed video. This management is done to ensure that
if any member of the network has a video, it will always be found by everyone else.
Thor uses this layer to perform the search and distribution of videos. Experiments
were performed with changes in buffer size and arrival rate at nodes. Results show
that the application has a high scalability, ensuring a good quality of service.
