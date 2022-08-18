# Pré-Rastreabilidade

## Versionamento

| Versão | Data  |                           Modificação                           |             Autor              |
| ------ | ----- | :-------------------------------------------------------------: | :----------------------------: |
| 1.0    | 16/08 | Criação do Documento | Gabriel Mariano |
| 1.1    | 17/08 | Introdução, Legenda e Referências | Gabriel Mariano |
| 1.2    | 17/08 | Checklist, Melhorias e Conclusão | Gabriel Mariano |
| 1.3    | 17/08 | Revisão | Gabriel Sabanai |

_Tabela 1: Versionamento_

## Introdução

Com enfoque na [Pré-Rastreabilidade](../../preRastreabilidade/richPicture.md), será avaliado o **Rich Picture** produzido, de modo a verificar se este atende aos critérios de aceitação a serem definidos e, mais importante, se este cumpre com seu papel na documentação do projeto, isto é, se este é capaz de expressar uma visão resumida do projeto.

## Checklist e Inspeção

### Legenda

| ID | Questão | Justificativa | Inspeção |
|----|---------|---------------|----------|
| Representa a identificação de cada ponto do Checklist  | Representa o ponto a ser avaliado no artefato | Representa a justificativa do ponto a ser avaliado, isto é, o motivo pelo qual esse aspecto é avaliado | Representa a confirmação ![Simbolo check](../../assets/modelagem/check.png){width="10"} ou negação ![Simbolo check](../../assets/modelagem/wrong.png){width="10"} da avaliação do tópico em questão |

_Tabela 2: Legenda da Tabela 3_ 

### C02 - Rich Picture

| ID | Questão | Justificativa | Inspeção |
|----|---------|---------------|----------|
| 1 | O *rich picture* produzido apresenta autor e versionamento? | Para que a documentação seja válida, os artefatos devem apresentar seus respectivos autores e suas respectivas versões. | ![Simbolo check](../../assets/modelagem/check.png){width="20"}  | 
| 2 | O *rich picture* apresenta atores? | Alguns dos elementos fundamentais de um *rich picture* são os atores que interagem com o sistema em questão. | ![Simbolo check](../../assets/modelagem/check.png){width="20"}  | 
| 3 | O *rich picture* apresenta operações? | Outro elemento fundamental de um *rich picture* são as operações que o sistema pode realizar. | ![Simbolo check](../../assets/modelagem/check.png){width="20"}  | 
| 4 | O *rich picture* representa os locais de armazenamento de dados? | Um sistema geralmente tem como elemento fundamental sua base de dados, que deve ser representada no *rich picture*. | ![Simbolo check](../../assets/modelagem/check.png){width="20"}  | 
| 5 | O *rich picture* apresenta setas que representam o fluxo de informações pelo sistema? | O fluxo de informações de um sistema é fundamental para o entendimento do mesmo. | ![Simbolo check](../../assets/modelagem/check.png){width="20"}  | 
| 6 | O *rich picture* apresenta a fronteira do sistema? | A fronteira de um sistema é fundamental para entender o escopo do mesmo. | ![Simbolo check](../../assets/modelagem/check.png){width="20"}  | 
| 7 | O *rich picture* produzido possui legenda descritiva e com a representação dos elementos visuais utilizados? | Tendo em vista que um *rich picture* representa uma visão que o autor possui do sistema em questão, sem apresentar muitas regras para seu desenvolvimento, deve-se existir legenda descritiva que seja capaz de instruir qualquer usuário sobre o conteúdo apresentado no mesmo. | ![Simbolo check](../../assets/modelagem/check.png){width="20"}  | 
| 8 | A fronteira do sistema está bem definida? | Para que a fronteira de um sistema esteja bem definida, esta deve abranger somente os elementos que realmente são de competência do sistema, definindo bem o escopo do mesmo. | ![Simbolo check](../../assets/modelagem/check.png){width="20"}  | 
| 9 | Os fluxos de dados apresentados através de setas possuem descrição sobre o conteúdo dos dados em questão? | Além de apresentar as setas com os fluxos de dados do sistema, deve-se descrever em linguagem natural o conteúdo dos dados transferidos em cada fluxo. | ![Simbolo check](../../assets/modelagem/check.png){width="20"}  | 
| 10 | Existe uma descrição da motivação para a elaboração do artefato? | Para que o desenvolvimento de um artefato seja justificado, deve-se ser detalhada sua motivação. | ![Simbolo check](../../assets/modelagem/check.png){width="20"}  | 

_Tabela 3: Checklist e Inspeção_

## Melhorias

De acordo com a inspeção realizada acima, percebe-se que o artefato produzido cumpre com seu papel na documentação do projeto. Cabe destacar apenas o ponto de **ID 4** do **Checklist 02 (C02)**, onde é descrito que o *rich picture* produzido deve apresentar os locais de armazenamento de dados. </br>

Apesar de não apresentar exatamente as estruturas de armazenamento de dados internas ao sistema, o autor representa como atores externos os locais de armazenamento de dados, consistindo estes em plataformas de armazenamento de dados em nuvem. Deste modo, entende-se que, de acordo com o *rich picture*, o sistema é passível de armazenamento de dados em outros sistemas externos, o que condiz com o software em questão. </br>

## Conclusão

Portanto, conclui-se que o artefato [*Rich Picture*](../../preRastreabilidade/richPicture.md) é capaz de apresentar o resultado esperado em sua criação, atendendo o que é esperado de seu papel na documentação de um sistema.

## Referências

**CTEC2402.** "Introducing Rich Pictures", por Software Development Project. Disponibilizado em ambiente virtual pelo docente.

**Documento de Requisitos do Duolingo**. "Inspeção". Disponível em: <https://requisitos-de-software.github.io/2019.2-Duolingo/analise/verificacao/inspecao/>. Acesso em 16 ago. 2022.

**Documento de Requisitos do Disney Plus**. "Verificação". Disponível em: <https://requisitos-de-software.github.io/2021.1-DisneyPlus/analise/verificacao/verificacao/>. Acesso em 16 ago. 2022.