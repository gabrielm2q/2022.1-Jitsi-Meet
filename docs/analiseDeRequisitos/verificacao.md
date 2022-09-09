# Verificação

## Versionamento

| Versão | Data  |                           Modificação                           |             Autor              |
| ------ | ----- | :-------------------------------------------------------------: | :----------------------------: |
| 1.0    | 16/08 | Criação do Documento | Felipe Moura, Gabriel Mariano, Laís Ramos |
| 1.1    | 16/08 | Introdução, Metodologia e Planejamento | Gabriel Mariano | 
| 1.2    | 16/08 | Visão Geral, Preparação, Inspeção, Correção, Acompanhamento e Referências | Gabriel Mariano | 
| 1.3    | 16/08 | Revisão | Gabriel Sabanai | 
| 1.4    | 08/09 | Adição dos Revisores | Gabriel Mariano | 


_Tabela 1: Versionamento_


## Introdução

O processo de verificação consiste em uma importante etapa da Engenharia de Requisitos, sendo fundamental para garantir que o produto desenvolvido esteja atendendo as especificações definidas. Segundo (SERRANO, Milene; SERRANO, Maurício), existem várias técnicas de verificação, sendo estas automatizadas por software ou desempenhadas por humanos. Dentre estas, destacam-se as **inspeções**, o **uso de estratégias formais** e a **reutilização de domínios**.

## Metodologia

Dentre as metodologias citadas anteriormente, foi definido pelo grupo que será utilizado o método das **inspeções com checklist**. Para a inspeção, será adotado o **Método de Inspeção de Fagan** que, conforme descrito por (SERRANO, Milene; SERRANO, Maurício _apud_ FAGAN), segue os seguintes passos: </br>

* Planejamento; </br>
* Visão Geral; </br>
* Preparação; </br>
* Inspeção; </br>
* Correção; </br>
* Acompanhamento. </br>

### Planejamento

Primeiramente, foram definidos os artefatos produzidos que serão inspecionados, sendo estes:

|  Tópico  |  Artefatos  |
|----|----|
|  Planejamento  |  [Cronograma](../planejamento/cronograma.md)  |
|  Pré-Rastreabilidade  |  [Rich Picture](../preRastreabilidade/richPicture.md)  | 
|  Elicitação  |  [Análise de Protocolo](../elicitacao/analiseProtocolo.md), [Brainstorming](../elicitacao/brainstorming.md), [Personas e Storytelling](../elicitacao/personas.md) e [Requisitos Elicitados](../elicitacao/requisitoselicitados.md)  |
|  Modelagem dos Requisitos  |  [Cenários](../modelagem/cenarios.md), [Léxico](../modelagem/lexico.md), [Use Case](../modelagem/useCase.md), [Especificação Suplementar](../modelagem/especificacaoSuplementar.md) e [NFR Framework](../modelagem/nfr.md)  |
|  Modelagem de Requisitos Ágeis  |  [Backlog](../modelagem/agil/backlog.md) e [Histórias de Usuário](../modelagem/agil/historiasDeUsuario.md)  | 

_Tabela 2: Artefatos a serem inspecionados_

Logo, foram definidos os responsáveis pela inspeção de cada artefato, que será realizada utilizando-se dos **Checklists**, e os revisores das inspeções realizadas:

|  Checklist  |  Artefato  |  Inspetor  |  Revisor  |
|-------------|------------|------------|-----------|
| [C01](./checklists/cronograma_cl.md) | [Cronograma](../planejamento/cronograma.md) | Gabriel Mariano | Gabriel Sabanai |
| [C02](./checklists/pre_rastreabilidade_cl.md) | [Rich Picture](../preRastreabilidade/richPicture.md) | Gabriel Mariano | Laís Ramos |
| [C03](./checklists/elicitacao_cl.md) | [Análise de Protocolo](../elicitacao/analiseProtocolo.md) | Gabriel Mariano | Laís Ramos |
| [C04](./checklists/elicitacao_cl.md) | [Brainstorming](../elicitacao/brainstorming.md) | Gabriel Mariano | André Alves |
| [C05](./checklists/elicitacao_cl.md) | [Personas e Storytelling](../elicitacao/personas.md) | Gabriel Mariano | Samuel Ávila |
| [C06](./checklists/elicitacao_cl.md) | [Requisitos Elicitados](../elicitacao/requisitoselicitados.md) | Laís Ramos | Gabriel Mariano |
| [C07](./checklists/modelagem_cl.md) | [Cenários](../modelagem/cenarios.md) | Laís Ramos | Gabriel Sabanai |
| [C08](./checklists/modelagem_cl.md) | [Léxico](../modelagem/lexico.md) | Laís Ramos | Felipe Moura |
| [C09](./checklists/modelagem_cl.md) | [Use Case](../modelagem/useCase.md) | Laís Ramos | Gabriel Sabanai |
| [C10](./checklists/modelagem_cl.md) | [Especificação Suplementar](../modelagem/especificacaoSuplementar.md) | Felipe Moura | Gabriel Mariano |
| [C11](./checklists/modelagem_cl.md) | [NFR Framework](../modelagem/nfr.md) | Felipe Moura | Laís Ramos |
| [C12](./checklists/modelagem_agil_cl.md) | [Backlog](../modelagem/agil/backlog.md) | Felipe Moura | André Alves |
| [C13](./checklists/modelagem_agil_cl.md) | [Histórias de Usuário](../modelagem/agil/historiasDeUsuario.md) | Felipe Moura | Samuel Ávila |
| [C14](./checklists/pos_rastreabilidade_cl.md) | [Backward-From](../posRastreabilidade/backwardFrom.md) | Gabriel Mariano | a definir |
| [C13](./checklists/pos_rastreabilidade_cl.md) | [Forward-From](../posRastreabilidade/forwardFrom.md) | Felipe Moura | a definir |

_Tabela 3: Checklists com Inspetores_

### Visão Geral

Conforme detalhado anteriormente, todos os artefatos produzidos passarão por inspeção devida através do uso de *checklists* a serem elaboradas pelos devidos "inspetores" e, posteriormente à inspeção, estes *checklists* serão revisados por outras pessoas a fim de encontrar possíveis inconsistências na produção do *checklist* ou na eventual avaliação dos pontos definidos no *checklist*. Deste modo, passaremos por todos os artefatos e evitaremos que erros conceituais e erros na elaboração do documento sejam identificados e posteriormente corrigidos. </br>

Em geral, os tópicos dos artefatos a serem corrigidos são cinco: Planejamento, Pré-Rastreabilidade, Elicitação, Modelagem de Requisitos e Modelagem de Requisitos Ágil.

### Preparação

Para a preparação, os **checklists** de cada artefato estarão separados em páginas conforme os tópicos previamente definidos, sendo eles o [Planejamento](./checklists/cronograma_cl.md), [Pré-Rastreabilidade](./checklists/pre_rastreabilidade_cl.md), [Elicitação](./checklists/elicitacao_cl.md), [Modelagem de Requisitos](./checklists/modelagem_cl.md) e [Modelagem de Requisitos Ágil](./checklists/modelagem_agil_cl.md). </br>

Os **checklists** elaborados estarão divididos conforme o artefato e numerados conforme a identificação descrita no Planejamento.

### Inspeção com Checklists

|  Checklist  |  Artefato  |  Tópico  |
|-------------|------------|----------|
| [C01](./checklists/cronograma_cl.md) | [Cronograma](../planejamento/cronograma.md) | Planejamento |
| [C02](./checklists/pre_rastreabilidade_cl.md) | [Rich Picture](../preRastreabilidade/richPicture.md) | Pré-Rastreabilidade |
| [C03](./checklists/elicitacao_cl.md) | [Análise de Protocolo](../elicitacao/analiseProtocolo.md) | Elicitação de Requisitos |
| [C04](./checklists/elicitacao_cl.md) | [Brainstorming](../elicitacao/brainstorming.md) | Elicitação de Requisitos |
| [C05](./checklists/elicitacao_cl.md) | [Personas e Storytelling](../elicitacao/personas.md) | Elicitação de Requisitos |
| [C06](./checklists/elicitacao_cl.md) | [Requisitos Elicitados](../elicitacao/requisitoselicitados.md) | Elicitação de Requisitos |
| [C07](./checklists/modelagem_cl.md) | [Cenários](../modelagem/cenarios.md) | Modelagem de Requisitos |
| [C08](./checklists/modelagem_cl.md) | [Léxico](../modelagem/lexico.md) | Modelagem de Requisitos |
| [C09](./checklists/modelagem_cl.md) | [Use Case](../modelagem/useCase.md) | Modelagem de Requisitos |
| [C10](./checklists/modelagem_cl.md) | [Especificação Suplementar](../modelagem/especificacaoSuplementar.md) | Modelagem de Requisitos |
| [C11](./checklists/modelagem_cl.md) | [NFR Framework](../modelagem/nfr.md) | Modelagem de Requisitos |
| [C12](./checklists/modelagem_agil_cl.md) | [Backlog](../modelagem/agil/backlog.md) | Modelagem de Requisitos Ágil |
| [C13](./checklists/modelagem_agil_cl.md) | [Histórias de Usuário](../modelagem/agil/historiasDeUsuario.md) | Modelagem de Requisitos Ágil |

_Tabela 4: Checklists_

### Correção

Posteriormente à **Inspeção com Checklists** realizada, os pontos analisados que não cumprirem com o esperado serão devidamente corrigidos por corretor a ser definido. Após a devida correção dos artefatos, os *checklists* serão atualizados para exibirem o *status* de corrigido aos pontos que necessitaram de correção.

### Acompanhamento

Quando realizada a correção, os pontos corrigidos serão avaliados para verificar se estes se adequam ao esperado e serão avaliadas as consequências da correção, isto é, se outros artefatos serão impactados com a correção realizada.

## Referências

**SERRANO, Milene. SERRANO, Maurício**. "Requisitos - Aula 23". 52 slides. Disponibilizado em ambiente virtual pelo docente.

**Lucas e Pedro**. "Aula de Análise", pelos monitores Lucas e Pedro. 37 slides. Disponibilizado em ambiente virtual pelo docente.

**Documento de Requisitos do Duolingo**. "Inspeção". Disponível em: <https://requisitos-de-software.github.io/2019.2-Duolingo/analise/verificacao/inspecao/>. Acesso em 16 ago. 2022.

**Documento de Requisitos do Disney Plus**. "Verificação". Disponível em: <https://requisitos-de-software.github.io/2021.1-DisneyPlus/analise/verificacao/verificacao/>. Acesso em 16 ago. 2022.
