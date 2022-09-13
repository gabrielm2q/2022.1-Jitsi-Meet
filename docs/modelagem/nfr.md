# NFR Framework

## Versionamento

| Versão | Data  |                           Modificação                           |             Autor              |
| ------ | ----- | :-------------------------------------------------------------: | :----------------------------: |
| 1.0    | 01/08 |               Elaboração do NFR          |   Gabriel Sabanai e Samuel Avila    |
| 1.1    | 02/08 |               Criação da Documentação                   |  Gabriel Sabanai e Samuel Avila |
| 1.2    | 03/08 |               Finalização da Documentação                           |  Gabriel Sabanai e Samuel Avila |
| 1.3    | 03/08 |               Revisão: Correção de Pequenos Erros no Documento                         |  Gabriel Mariano |
| 1.4    | 03/08 |               Revisão: Adição das Referências                         |  Gabriel Sabanai |

_Tabela 1: Versionamento_

## Introdução

O NFR framework é uma abordagem para análisar e representar os requisitos não funcionais. Dessa forma, ele orienta a engenharia de requisitos em volta aos requisitos não funcionais e inclui características de prioridades e carga de trabalho, tudo isso a partir da utilização do modelo SIG (Softgoal Interdepency Graph). (SILVA., 2019)


### Softgoals
* Softgoal NFR: São as características abstratas, ou seja, são os requisitos não funcionais sendo postos a análise para definir se o mesmo será cumprido ou não.

* Softgoal de Operacionalização: Representam soluções de implementação para satisfazer softoals NFR ou outros de operacionalização. Envolve varios tipos de dados, tais quais: opereções, processos, representações de dados, estruturações e restrições que atendam a necessidade do softgoal.

* Softgoal de Afirmação: Permitem que as características externas de cada softgoal (como prioridades ou carga de trabalho) sejam consideradas e refletidas no processo de decisão. Logo, servem para justificar a priorização do softgoal.

![Legenda Softgoals](https://raw.githubusercontent.com/Requisitos-de-Software/2022.1-Grupo-03/main/docs/media/nfr/tipos-soft.png)

_Figura 1: Legenda softgoals_ 

### Decomposições

As decomposições refinam os softgoals para obter softgoals mais especializados, de forma que estes possam auxiliar na construção do projeto.

As relações entre eles podem ser divididas em 4 tipos de decomposição, tais quais:

* Decomposição de Softgoal NFR
* Decomposição de Operacionalização
* Decomposição de Afirmação
* Priorização
## Metodologia

Para elaborar os diagramas SIG (cada um gerenciando um requisito não funcional da Especificação Suplementar) abordamos os NFRs a partir de uma decomposição destes requisitos em um nível operacional, facilitando em seu entendimento, em sua priorização e garantindo que as necessidades do cliente sejam atendidas (PARADKAR, 2017).

A seguir segue definições importantes para o entendimento do artefato NFR:

* AND: Caso os softgoals descendentes sejam satisfeitos, serão também os ascendentes.
* OR: Caso algum softgoal descendentes seja satisfeitos, será também os ascendente.
* MAKE (++): Caso o softgoal descendente for suficientemente satisfeito, será também o ascendente, porém, a contribuição é fornecida como suficientemente positiva concebida no nível mais alto de satisfação.
* HELP (+): Caso o softgoal descendente seja parcialmente satisfeito, será parcialmente satisfeito o ascendente.
* HURT (-): Caso o softgoal descendente seja satisfeito, o softgoal ascendente será parcialmente negado.

Rótulos:

| Rótulo | Descrição |
| :----: | :-------: |
| ![Simbolo check](../../assets/modelagem/check.png) | Satisfeito |
| ![Simbolo Wrong](../../assets/modelagem/wrong.png) | Negado |

Os diagramas foram montados pelos membros Gabriel Sabanai e Samuel Ávila sendo e em seguida foi validado e revisado por demais membros do grupo. Além disso, eles foram feitos utilizando a plataforma Draw.io e Lucidchart no dia 01 de agosto de 2022.

## Resultados

### Legenda

Nas figuras 2 e 3 é possível ver as legendas com as simbologias usadas para criar os diagramas SIG.

![Legenda](https://cdn.discordapp.com/attachments/744698026462937211/1004542201604349962/unknown.png)

_Figura 2: Legendas_

![Legenda](https://cdn.discordapp.com/attachments/744698026462937211/1004510204131553400/unknown.png)

_Figura 3: Legendas_

## Gráfico de Interdependencia de Softgoal (SIG)

### Usabilidade 
![Usabilidade NFR](../../assets/modelagem/usabilidadenfr.png)
_Figura 4: NFR Usabilidade_

### Usabilidade Propagação
![Usabilidade Propagação NFR](../../assets/modelagem/usabilidadenfrpropagacao.png)
_Figura 5: NFR Usabilidade Propragação_

### Confiabilidade
![Confiabilidade NFR](../../assets/modelagem/confiabilidadenfr.png)
_Figura 6: NFR confiabilidade_

### Confiabilidade Propagacao
![Confiabilidade NFR](../../assets/modelagem/confiabilidadenfrpropagacao.png)
_Figura 7: NFR confiabilidade propagacao_
### Desempenho
![Desempenho NFR](../../assets/modelagem/desempenhonfr.png)
_Figura 8: NFR Desempenho_

### Desempenho Propagação
![Desempenho Propagação NFR](../../assets/modelagem/desempenhonfrpropagacao.png)
_Figura 9: NFR Desempenho Propragação_

### Suportabilidade
![Suportabilidade NFR](../../assets/modelagem/suportabilidadenfr.png)
_Figura 10: NFR Suportabilidade_

### Suportabilidade Propagação
![Suportabilidade NFR](../../assets/modelagem/suportabilidadenfrpropagacao.jpeg)
_Figura 11: NFR Suportabilidade Propagação_

## Referências

  SILVA, Reinaldo Antônio da. NFR4ES: Um Catálogo de Requisitos Não-Funcionais para Sistemas Embarcados. Universidade Federal de Pernambuco, Recife, 2019. 2.4 - NFR Framework.

  PARADKAR, Mastering Non-Functional Requirements. Universidade Federal de Pernambuco, Recife, 2017.