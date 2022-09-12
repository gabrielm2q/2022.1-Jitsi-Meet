# Post Mortem

## Versionamento do projeto

| Versão | Data  |    Modificação    |             Autor              |
| ------ | ----- | :---------------: | :----------------------------: |
| 1.0    | 12/09 | Criação da Página | Gabriel Mariano                |
| 1.1   | 12/09 | Adição dos Tópicos do Post Mortem | Gabriel Mariano |

_Tabela 1: Versionamento_

## Introdução

Esse documento contém o **Post Mortem** do projeto, que visa apresentar todos os pontos abordados ao decorrer do projeto ao fim de elucidadar como ocorreu seu andamento.

## Aplicativo Selecionado

Conforme descrito na [Home](../index.md), a seleção do aplicativo contou com alguns contratempos. A priori, o aplicativo a ser avaliado na disciplina seria o **Forest**. Porém, como as políticas de uso do mesmo não permitem a realização da engenharia reversa (o mesmo que ocorre com o aplicativo **HBO Max**), foi decidido em comum acordo que o aplicativo utilizado seria o [**Jitsi Meet**](https://meet.jit.si/), uma ferramenta de vídeochamadas online.

## Planejamento dos Recursos e das Entregas

Conforme consta no [Cronograma](../planejamento/cronograma.md), foi realizado um planejamento de todas as atividades a serem desenvolvidas pela equipe ao decorrer do projeto. O cronograma final das atividades, com o [**Planning Poker**](../planejamento/metodologia.md) realizado, seria: 

![Cronograma Detalhado](../assets/cronograma-detalhado.png)

*Figura 1: Cronograma Detalhado das Sprints e Entregas*

## Execução do Projeto

A execução do projeto também consta no [Cronograma](../planejamento/cronograma.md), sendo este dividido em 6 entregas principais (chamados por **Pontos de Controle**) e uma entrega final (**Apresentação Final do Projeto**).

O cronograma da execução do projeto por etapas seria:

![Cronograma](../assets/cronograma.png)

*Figura 2: Cronograma de sprints*

## Resultados Alcançados

Com o desenvolvimento do projeto, foi possível obter uma documentação alternativa do que seria a engenharia de requisitos para a aplicação [**Jitsi Meet**](https://meet.jit.si/), partindo do [Planejamento](../planejamento/cronograma.md) do projeto, partindo para a [Pré-Rastreabilidade](../preRastreabilidade/richPicture.md), passando pela [Elicitação de Requisitos](../elicitacao/requisitoselicitados.md), pela [Modelagem de Requisitos](../modelagem/agil/historiasDeUsuario.md), pela [Análise de Requisitos](../analiseDeRequisitos/verificacao.md) e chegando à [Pós Rastreabilidade](../posRastreabilidade/backwardFrom.md) dos requisitos elicitados.

Cada etapa do desenvolvimento visou encobrir uma etapa da engenharia de requisitos de um projeto, passando assim por todo o ciclo de vida do desenvolvimento deste. Vale destacar que o atual projeto de requisitos não visa desenvolver uma aplicação a partir do *marco zero*, mas sim estudar uma aplicação já desenvolvida e executar as etapas da engenharia visando simular a construção desta aplicação.

## Técnicas Utilizadas

#### **Legenda**

| Etapa | Metodologias/Técnicas |
| :------------: | :-------------------: |
| Nome da Etapa de Desenvolvimento do Projeto | Descrição da(s) metodologia(s) e/ou técnica(s) utilizadas no desenvolvimento do artefato ou da etapa em questão |

_Tabela 2: Legenda das Técnicas Utilizadas_

As técnicas utilizadas para a gestão da equipe estão descritas no artefato de [**Metodologias**](../planejamento/metodologia.md). As técnicas utilizadas pelas etapas de desenvolvimento do projeto são: 

| Etapa | Metodologias/Técnicas |
| :------------: | --------------------- |
| Planejamento | [SCRUM, Pareamento e _Planning Poker_](../planejamento/metodologia.md) |
| Pré-Rastreabilidade | [Rich Picture](../preRastreabilidade/richPicture.md#metodologia) |
| Elicitação de Requisitos | [Análise de Protocolo](../elicitacao/analiseProtocolo.md), [Brainstorm](../elicitacao/brainstorming.md), [Personas](../elicitacao/personas.md#personas), [Storytelling](../elicitacao/personas.md#elicitação-dos-requisitos), [MoSCoW](../elicitacao/requisitoselicitados.md#moscow) e [Escala de Lickert](../elicitacao/requisitoselicitados.md) |
| Modelagem de Requisitos | [Cenários](../modelagem/cenarios.md), [Léxico](../modelagem/lexico.md), [Caso de Uso](../modelagem/useCase.md), [FURPS+](../modelagem/especificacaoSuplementar.md#metodologia), [NFR Framework](../modelagem/nfr.md) |
| Modelagem Ágil de Requisitos | [Backlog](../modelagem/agil/backlog.md) e [Histórias de Usuário](../modelagem/agil/historiasDeUsuario.md) |
| Análise de Requisitos | [Verificação com Checklists](../analiseDeRequisitos/verificacao.md), [Método de Inspeção de Fagan](../analiseDeRequisitos/verificacao.md#metodologia), [Validação Informal](../analiseDeRequisitos/validacao/validacao-informal.md), [Protótipo](../analiseDeRequisitos/validacao/prototipo.md) e [Viewpoint](../analiseDeRequisitos/validacao/viewpoint.md) |
| Pós-Rastreabilidade | [Meta-Modelo proposto por Toranzo](../posRastreabilidade/backwardFrom.md#metodologia) |

_Tabela 3: Metodologias Utilizadas_

## Artefatos Criados

#### **Legenda**

| Etapa | Artefato | Criadore(s) | Revisor(es) |
| :---: | :---: | :---: | :---: |
| Nome da Etapa de Desenvolvimento do Projeto | Nome do Artefato Criado | Nome do(s) Criador(es) do Artefato | Nome do(s) Revisor(es) do Artefato |

_Tabela 4: Legenda dos Artefatos Criados_

Os artefatos criados ao decorrer do projeto foram: 

| Etapa | Artefato | Criadore(s) | Revisor(es) |
| :---: | :---: | :---: | :---: |
| Planejamento | [Metodologias](../planejamento/metodologia.md) | Gabriel Mariano e Laís Ramos | Gabriel Sabanai |
| Planejamento | [Ferramentas Utilizadas](../planejamento/ferramentas.md) | Samuel Ávila e André Alves | Gabriel Sabanai |
| Planejamento | [Cronograma](../planejamento/cronograma.md) | Gabriel Mariano e Laís Ramos | Felipe Moura |
| Planejamento | [Heatmap](../planejamento/heatmap.md) | Samuel Ávila e Gabriel Sabanai | --- |
| Planejamento | [Políticas de Contribuição](../planejamento/politicas.md) | Gabriel Sabanai | --- |
| Pré-Rastreabilidade | [Rich Picture](../preRastreabilidade/richPicture.md) | Felipe Moura, André Alves e Gabriel Sabanai | Gabriel Mariano |
| Elicitação de Requisitos | [Análise de Protocolo](../elicitacao/analiseProtocolo.md) | Samuel Ávila e Gabriel Sabanai | --- |
| Elicitação de Requisitos | [Brainstorm](../elicitacao/brainstorming.md) | Gabriel Sabanai e Samuel Ávila | --- |
| Elicitação de Requisitos | [Personas e Storytelling](../elicitacao/personas.md) | Gabriel Mariano, Felipe Cândido e Laís Ramos | --- |
| Elicitação de Requisitos | [Requisitos Elicitados](../elicitacao/requisitoselicitados.md) | Grupo | Felipe Moura |
| Modelagem de Requisitos | [Cenários](../modelagem/cenarios.md) | Samuel Ávila e Felipe Moura | Gabriel Mariano e Gabriel Sabanai |
| Modelagem de Requisitos | [Léxico](../modelagem/lexico.md) | Gabriel Sabanai | Gabriel Mariano e Samuel Ávila |
| Modelagem de Requisitos | [Use Case](../modelagem/useCase.md) | Felipe Moura e Gabriel Mariano | Gabriel Sabanai |
| Modelagem de Requisitos | [Especificação Suplementar](../modelagem/especificacaoSuplementar.md) | André Alves e Laís Ramos | Gabriel Mariano |
| Modelagem de Requisitos | [NFR Framework](../modelagem/nfr.md) | Gabriel Sabanai e Samuel Ávila | Gabriel Mariano |
| Modelagem Ágil de Requisitos | [Backlog](../modelagem/agil/backlog.md) | Gabriel Mariano e Felipe Moura | Samuel Ávila |
| Modelagem Ágil de Requisitos | [Histórias de Usuário](../modelagem/agil/historiasDeUsuario.md) | André Alves e Laís Ramos | Gabriel Mariano |
| Análise de Requisitos | [Verificação](../analiseDeRequisitos/verificacao.md) | Felipe Moura, Gabriel Mariano e Laís Ramos | Gabriel Sabanai |
| Análise de Requisitos | [Checklists (Geral)](../analiseDeRequisitos/verificacao.md#planejamento) | Gabriel Mariano, Laís Ramos e Felipe Moura | Grupo |
| Análise de Requisitos | [Validação Informal](../analiseDeRequisitos/validacao/validacao-informal.md) | André Alves | Felipe Moura |
| Análise de Requisitos | [Protótipo](../analiseDeRequisitos/validacao/prototipo.md) | Samuel Ávila | Gabriel Mariano e Gabriel Sabanai |
| Análise de Requisitos | [Viewpoint](../analiseDeRequisitos/validacao/viewpoint.md) | Gabriel Sabanai | Gabriel Mariano |
| Pós-Rastreabilidade | [Backward-From](../posRastreabilidade/backwardFrom.md) | André Alves, Felipe Moura e Gabriel Mariano | Gabriel Sabanai |
| Pós-Rastreabilidade | [Forward-From](../posRastreabilidade/forwardFrom.md) | Samuel Ávila, Gabriel Sabanai e Laís Ramos | Felipe Moura |
| Apresentação Final | [*Post Mortem*](../apresentacoes/postMortem.md) | Gabriel Mariano |  |

_Tabela 5: Artefatos Criados_

# Verificação e Validação

A verificação dos artefatos criados foi realizada utilizando-se do [**Método de Inspeção de Fagan**](../analiseDeRequisitos/verificacao.md#metodologia), sendo criados *Checklists* cujos pontos foram posteriormente inspecionados e, em caso de erro, corrigidos.

#### É importante citar que a correção dos artefatos é de responsabilidade de seus criadores, conforme projetado na [**Tabela 5**](./postMortem.md#artefatos-criados).

Os *checklists* criados, com seus respectivos criadores e inspetores são:

|  Checklist  |  Artefato  |  Criador/Inspetor  |  Revisor  |
|-------------|------------|------------|-----------|
| [C01](../analiseDeRequisitos/checklists/cronograma_cl.md) | [Cronograma](../planejamento/cronograma.md) | Gabriel Mariano | Gabriel Sabanai |
| [C02](../analiseDeRequisitos/checklists/pre_rastreabilidade_cl.md) | [Rich Picture](../preRastreabilidade/richPicture.md) | Gabriel Mariano | Laís Ramos |
| [C03](../analiseDeRequisitos/checklists/elicitacao_cl.md) | [Análise de Protocolo](../elicitacao/analiseProtocolo.md) | Gabriel Mariano | Laís Ramos |
| [C04](../analiseDeRequisitos/checklists/elicitacao_cl.md) | [Brainstorming](../elicitacao/brainstorming.md) | Gabriel Mariano | André Alves |
| [C05](../analiseDeRequisitos/checklists/elicitacao_cl.md) | [Personas e Storytelling](../elicitacao/personas.md) | Gabriel Mariano | Samuel Ávila |
| [C06](../analiseDeRequisitos/checklists/elicitacao_cl.md) | [Requisitos Elicitados](../elicitacao/requisitoselicitados.md) | Laís Ramos | Gabriel Mariano |
| [C07](../analiseDeRequisitos/checklists/modelagem_cl.md) | [Cenários](../modelagem/cenarios.md) | Laís Ramos | Gabriel Sabanai |
| [C08](../analiseDeRequisitos/checklists/modelagem_cl.md) | [Léxico](../modelagem/lexico.md) | Laís Ramos | Felipe Moura |
| [C09](../analiseDeRequisitos/checklists/modelagem_cl.md) | [Use Case](../modelagem/useCase.md) | Laís Ramos | Gabriel Sabanai |
| [C10](../analiseDeRequisitos/checklists/modelagem_cl.md) | [Especificação Suplementar](../modelagem/especificacaoSuplementar.md) | Felipe Moura | Gabriel Mariano |
| [C11](../analiseDeRequisitos/checklists/modelagem_cl.md) | [NFR Framework](../modelagem/nfr.md) | Felipe Moura | Laís Ramos |
| [C12](../analiseDeRequisitos/checklists/modelagem_agil_cl.md) | [Backlog](../modelagem/agil/backlog.md) | Felipe Moura | André Alves |
| [C13](../analiseDeRequisitos/checklists/modelagem_agil_cl.md) | [Histórias de Usuário](../modelagem/agil/historiasDeUsuario.md) | Felipe Moura | Samuel Ávila |
| [C14](../analiseDeRequisitos/checklists/pos_rastreabilidade_cl.md) | [Backward-From](../posRastreabilidade/backwardFrom.md) | Gabriel Mariano | a definir |
| [C15](../analiseDeRequisitos/checklists/pos_rastreabilidade_cl.md) | [Forward-From](../posRastreabilidade/forwardFrom.md) | Felipe Moura | a definir |

_Tabela 6: Checklists com Inspetores_

# Ferramentas Utilizadas

#### **Legenda**

| Ferramenta | Artefatos/Etapas |
| :---: | --- |
| Nome da Ferramenta Utilizada | Nome dos Artefatos (ou etapas do projeto) onde a ferramenta em questão foi utilizada |

_Tabela 7: Legenda das Ferramentas Utilizadas_

Durante a execução do projeto, foram utilizadas diversas ferramentas, estando estas descritas em [**Ferramentas**](../planejamento/ferramentas.md). Abaixo, temos as ferramentas utilizadas e os devidos artefatos/etapas onde estas foram utilizadas.

| Ferramenta | Artefatos/Etapas |
| :---: | --- |
| Discord | Em todas as etapas do projeto. |
| Teams   | Em todas as etapas do projeto. |
| Telegram  | Em todas as etapas do projeto. |
| VsCode | Em todas as etapas do projeto. |
| Github | Em todas as etapas do projeto. |
| Google Drive | Em todas as etapas do projeto. |
| Google Sheets | Nas etapas 1, 2 e 3, nos artefatos: [Planejamento](../planejamento/cronograma.md), [Personas e Storytelling](../elicitacao/personas.md) e [Histórias de Usuário](../modelagem/agil/historiasDeUsuario.md) |
| Google Documents | Na etapa 2, no artefato: [Planejamento](../planejamento/cronograma.md) |
| Trello | Em todas as etapas do projeto.|
| LucidChart | Nas etapas 1 e 3, nos artefatos: [Rich Picture](../preRastreabilidade/richPicture.md) e [Use Case](../modelagem/useCase.md)|
| Youtube | Em todas as etapas do projeto. |
| Figma | Na etapa 5, no artefato: [Protótipo](../analiseDeRequisitos/validacao/prototipo.md) |
| Jitsi Meet | Em todas as etapas do projeto. |
| Notion | Na etapa Final, para organização da equipe. |

_Tabela 8: Ferramentas Utilizadas_