# Modelagem de Requisitos

## Versionamento

| Versão | Data  |                           Modificação                           |             Autor              |
| ------ | ----- | :-------------------------------------------------------------: | :----------------------------: |
| 1.0    | 17/08 | Criação do Documento | Felipe Moura |
| 1.1    | 17/08 | Introdução, Legenda e Referências | Felipe Moura |
| 1.2    | 17/08 | Checklist da Especificação Suplementar | Felipe Moura |
| 1.3    | 17/08 | Checklist da NFR Framework | Felipe Moura |
| 1.4    | 17/08 | Elaboração dos Checklists dos Cenários e Léxicos | Laís Ramos |
| 1.5    | 17/08 | Revisão | Gabriel Sabanai |
| 1.6   | 18/08 | Adição do checklist do Use Case | Laís Ramos |
| 1.7   | 18/08 | Revisão e modificação do checklist do Use Case | Laís Ramos |
| 1.8   | 08/09 | Revisão do Checklist C10 | Gabriel Mariano |

_Tabela 1: Versionamento_

## Introdução

Com base nos artefatos produzidos na Modelagem de Requisitos ([Cenários](../../modelagem/cenarios.md), [Lexicos](../../modelagem/lexico.md), [Use Case](../../modelagem/useCase.md), [Especificação Suplementar](../../modelagem/especificacaoSuplementar.md) e [NFR Framework](../../modelagem/nfr.md)) foram produzidos checklists para verificar a qualidade destes com base no que era requerido para o projeto.

## Checklist e Inspeção

### Legenda

| ID | Questão | Justificativa | Inspeção |
|----|---------|---------------|----------|
| Representa a identificação de cada ponto do Checklist  | Representa o ponto a ser avaliado no artefato | Representa a justificativa do ponto a ser avaliado, isto é, o motivo pelo qual esse aspecto é avaliado | Representa a confirmação ![Simbolo check](../../assets/modelagem/check.png){width="10"} ou negação ![Simbolo check](../../assets/modelagem/wrong.png){width="10"} da avaliação do tópico em questão |

_Tabela 2: Legenda dos Checklists_ 


### C07 - Cenários

| ID | Questão                                                        | Justificativa                                                                              | Inspeção |
|----|----------------------------------------------------------------|--------------------------------------------------------------------------------------------|----------|
|  1 | Os cenários possuem uma estrutura padrão?                      | É importante que os cenários sigam um padrão para facilitar o entendimento do artefato.    | ![Simbolo check](../../assets/modelagem/check.png){width="20"}      |
|  2 | Os cenários possuem título?                                    | Os cenários precisam de um título para serem identificados e para entender o seu contexto. | ![Simbolo check](../../assets/modelagem/check.png){width="20"}       |
|  3 | Os cenários possuem objetivo?                                  | Para que se entenda o objetivo de um cenário, esse precisa ser descrito.                   | ![Simbolo check](../../assets/modelagem/check.png){width="20"}       |
|  4 | Os cenários possuem contexto?                                  | Os cenários precisam de um contexto para que façam sentido.                                | ![Simbolo check](../../assets/modelagem/check.png){width="20"}       |
|  5 | Os contextos possuem local?                                    | O contexto precisa de um local para que faça sentido.                                      | ![Simbolo check](../../assets/modelagem/wrong.png){width="20"}       |
|  6 | Os contextos possuem tempo?                                    | O contexto precisa de um tempo para que faça sentido.                                      | ![Simbolo check](../../assets/modelagem/wrong.png){width="20"}       |
|  7 | Os contextos possuem pré-condição?                             | O contexto precisa de uma pré-condição para que faça sentido.                              | ![Simbolo check](../../assets/modelagem/wrong.png){width="20"}       |
|  8 | Os cenários possuem atores?                                    | Os atores são importantes para o entendimento do cenário.                                  | ![Simbolo check](../../assets/modelagem/check.png){width="20"}       |
|  9 | Os cenários possuem episódios?                                 | Os episódios são importantes para o entendimento do cenário.                               | ![Simbolo check](../../assets/modelagem/check.png){width="20"}       |
| 10 | Os cenários possuem recursos?                                  | Os recurso são importantes para o entendimento do cenário.                                 | ![Simbolo check](../../assets/modelagem/check.png){width="20"}       |
| 11 | Os cenários possuem restrições?                                | As restrições são importantes para o entendimento do cenário.                              | ![Simbolo check](../../assets/modelagem/check.png){width="20"}       |
| 12 | Os cenários possuem exceções?                                  | As exceções são importantes para o entendimento do cenário.                                | ![Simbolo check](../../assets/modelagem/check.png){width="20"}       |
| 13 | As referências possuem links para os documentos referenciados? | As referências são essenciais para evitar casos de plágio.                                 | ![Simbolo check](../../assets/modelagem/check.png){width="20"}       |
| 14 | É possível acessar as referências através dos links?           | Os links devem estar funcionais no documento final.                                        | ![Simbolo check](../../assets/modelagem/check.png){width="20"}       |

_Tabela 3: Checklist 07 - Cenários_ 

### C08 - Léxico

| ID | Questão | Justificativa | Inspeção |
|----|---------|---------------|----------|
| 1 | A definição de Léxico está presente? | É importante que sejam definidos os conceitos utilizados | ![Simbolo check](../../assets/modelagem/check.png){width="20"}  |
| 2 | Os léxicos possuem ligações entre si? | Para facilitar a rastreabilidade e propiciar um melhor entendimento do artefato, é necessário ligar os conceitos com suas definições. | ![Simbolo wrong](../../assets/modelagem/wrong.png){width="20"}  |
| 3 | Os léxicos utilizam a estrutura de dicionário (verbo, objeto, estado)? | Para uma boa estruturação deste artefato, a estrutura de dicionário é importante. | ![Simbolo check](../../assets/modelagem/check.png){width="20"}  |
| 4 | Os léxicos possuem sinônimos? | Os sinônimos auxiliam na identificação dos conceitos quando descritos de outras formas. | ![Simbolo check](../../assets/modelagem/check.png){width="20"}  |
| 5 | Os léxicos possuem classificação? | A classificação dos léxicos é importante para uma boa estruturação do artefato. | ![Simbolo check](../../assets/modelagem/check.png){width="20"}  |
| 6 | Os léxicos possuem noções? | A definição de noções é importante para o entendimento do artefato produzido. | ![Simbolo check](../../assets/modelagem/check.png){width="20"}  |
| 7 | Nas noções de cada léxico há a presença de hiperlinks que interligam o significado das palavras sublinhadas? | A existência de *hiperlinks* permite uma melhor rastreabilidade dentro do artefato. | ![Simbolo wrong](../../assets/modelagem/wrong.png){width="20"}  |
| 8 | Os léxicos possuem impacto? | O impacto dos léxicos é importante para o bom entendimento da importância destes. | ![Simbolo check](../../assets/modelagem/check.png){width="20"}  |
| 9 | ;Todas as referências possuem links para os documentos referenciados? | A existência de *links* nas referências auxilia no processo de identificação da origem das informações contidas no artefato. | ![Simbolo wrong](../../assets/modelagem/check.png){width="20"}  |

_Tabela 4: Checklist 08 - Léxico_ 

### C09 - Use Case

| ID | Questão | Justificativa | Inspeção |
|----|---------|---------------|----------|
| 1 | É apresentado a especificação do diagrama de caso de uso (com Nome, Descrição, Atores, Pré-Condição,Pós-Condição) |Através da especificação do Diagrama de Caso de Uso, o leitor consegue abstrair como é o funcionamento do software | ![Simbolo check](../../assets/modelagem/check.png){width="20"}  |
| 2 | A descrição da Especificação de casos de Uso é clara? | É necessário clareza e objetividade para que o leitor entenda o objetivo de cada componente do diagrama | ![Simbolo check](../../assets/modelagem/check.png){width="20"}  |
| 3 | Os verbos do diagrama se encontram no infinitivo, indicando que é uma ação? | Os verbos devem representar a ação a ser realizada pelo ator  | ![Simbolo check](../../assets/modelagem/check.png){width="20"}  |
| 4 | Há a  presença de fluxos principais? | É importante a representação dos fluxos principais, pois estes tratam da maneira que o ator utilizará primordiamente a funcionalidade. | ![Simbolo check](../../assets/modelagem/check.png){width="20"}  |
| 5 |Há a presença de fluxos alternativos?  | É importante a representação dos fluxos alternativos, pois estes exprimem as escolhas que o usuário poderá fazer na execução da funcionalidade | ![Simbolo check](../../assets/modelagem/check.png){width="20"}  |
| 6 | Há a  presença de fluxos de exceção | É importante a representação clara dos fluxos de exceções pois estes tratam as possíveis exceções que podem aparecer durante a utilização do sistema | ![Simbolo check](../../assets/modelagem/check.png){width="20"}  |
| 7 | Os relacionamentos Include e Extend estão bem representados? | É imprescindível a clara representação dos relacionamentos Include e Extend, pois eles trazem as respectivas noções de obrigatoriedade para os relacionamentos | ![Simbolo check](../../assets/modelagem/check.png){width="20"}  |
| 8 | Há presença de atores principais e atores secundários? | A importância da representação de atores se dá porque estes representam o diversos tipos de usuários que tem contato com o sistema | ![Simbolo check](../../assets/modelagem/check.png){width="20"}  |
| 9 | O ator principal está do lado esquerdo do sistema? | Caso o ator principal não esteja representado do lado esquerdo,sua denominação como ator principal perde o sentido | ![Simbolo check](../../assets/modelagem/check.png){width="20"}  |
| 10 | Os atores estão fora da caixa de limite do sistema? | Os atores devem esta fora da caixa pois os mesmos não fazem parte do sistema | ![Simbolo check](../../assets/modelagem/check.png){width="20"}  |
| 11 | As referências possuem links para os documentos referenciados? | A presença do link nas referências do artefato ajudam na construção da pós-rastreabilidade | ![Simbolo check](../../assets/modelagem/check.png){width="20"}  |
| 12 | É possível acessar as referências através dos links? |O link deve ser usável para a construção da pós-rastreabilidade | ![Simbolo check](../../assets/modelagem/check.png){width="20"}  |


_Tabela 5: Checklist 09 - Use Case_ 

### C10 - Especificação Suplementar

#### **Versão 0.1**

| ID |                                                                                                     Questão                                                               | Justificativa                                      | Inspeção |
|----|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------|------------------------------------------------------|----------|
|  1 | Foi feito o versionamento do artefato?                                                                                                                                    | Para o mantenimento da rastreabilidade do artefato, o versionamento é essencial. | ![Simbolo check](../../assets/modelagem/check.png){width="20"}|
|  2 | As referências bibliográficas foram feitas corretamente?                                                                                                                  | A citação das referências bibliográficas é necessária para evitar casos de plágio, dando os devidos créditos para o dententor original do conhecimento.                     | ![Simbolo check](../../assets/modelagem/check.png){width="20"}          |
|  3 | Os requisitos não funcionais possuem rastreabilidade?                                                                                                                     | A rastreabilidade dos requisitos não funcionais é necessária para que se saiba de onde surgiram.                  | ![Simbolo check](../../assets/modelagem/check.png){width="20"}          |
|  4 | Foi utilizado o método FURPS+?                                                                                                                                            | A especificação suplementar, no caso deste projeto, prevê o uso do FURPS+.                     | ![Simbolo check](../../assets/modelagem/check.png){width="20"}         |
|  5 | Os requisitos descritos foram separados em: Funcionality (Funcionalidade), U - Usability (Usabilidade), Reliability (Confiabilidade), Performance (Performance), Supportability (Suportabilidade) e + (Mais)? |O FURPS+ se utiliza dessas cinco categorias para definir os requisitos. | ![Simbolo check](../../assets/modelagem/check.png){width="20"}|
|  6 | Os requisitos descritos como Funcionality (Funcionalidade) estão de acordo com a categoria definida pelo FURPS+?                                                          | Garantir que os requisitos não funcionais de funcionalidade estão na categoria correta.                    | ![Simbolo check](../../assets/modelagem/check.png){width="20"}         |
|  7 | Os requisitos descritos como Usability (Usabilidade) estão de acordo com a categoria definida pelo FURPS+?                                                                 | Garantir que os requisitos não funcionais de usabilidade estão na categoria correta.                   | ![Simbolo check](../../assets/modelagem/check.png){width="20"}         |
|  8 | Os requisitos descritos como Reliability (Confiabilidade) estão de acordo com a categoria definida pelo FURPS+?                                                            | Garantir que os requisitos não funcionais de confiabilidade estão na categoria correta.                   | ![Simbolo check](../../assets/modelagem/check.png){width="20"}         |
|  9 | Os requisitos descritos como Performance (Performance) estão de acordo com a categoria definida pelo FURPS+?                                                               | Garantir que os requisitos não funcionais de performance estão na categoria correta.|  ![Simbolo check](../../assets/modelagem/check.png){width="20"}        |
| 10 | Os requisitos descritos como Supportability (Suportabilidade) estão de acordo com a categoria definida pelo FURPS+?                                                        | Garantir que os requisitos não funcionais de suportabilidade estão na categoria correta.                  |  ![Simbolo check](../../assets/modelagem/check.png){width="20"}        |
| 11 | Os requisitos descritos como + (Mais) estão de acordo com a categoria definida pelo FURPS+?                                                                                | Garantir que os requisitos não funcionais que não se encaixam nas outras categorias estão na categoria correta.                 | ![Simbolo check](../../assets/modelagem/check.png){width="20"}         |

_Tabela 6: Checklist 10 - Especificação Suplementar. Produzido por Felipe Moura._ 

#### **Versão 0.2**

| ID |  Questão | Justificativa | Inspeção |
|----|--|-----|------|
|  1 | Foi feito o versionamento do artefato?  | Para a manutenção da rastreabilidade do artefato, o versionamento é essencial. | ![Simbolo check](../../assets/modelagem/check.png){width="20"}|
|  2 | O documento possui referências bibliográficas?  | A citação das referências bibliográficas é necessária para evitar casos de plágio, dando os devidos créditos para o dententor original do conhecimento.   | ![Simbolo check](../../assets/modelagem/check.png){width="20"}          |
|  3 | Foram citadas as origens dos requisitos não funcionais? | A rastreabilidade dos requisitos não funcionais é necessária para que se saiba de onde surgiram.                  | ![Simbolo check](../../assets/modelagem/check.png){width="20"}          |
|  4 | Foi utilizado o método FURPS+? | A especificação suplementar, no caso deste projeto, prevê o uso do FURPS+.   | ![Simbolo check](../../assets/modelagem/check.png){width="20"}         |
|  5 | Os requisitos descritos como Funcionality (Funcionalidade) estão de acordo com a categoria definida pelo FURPS+? | Garantir que os requisitos não funcionais de funcionalidade estão na categoria correta. | ![Simbolo check](../../assets/modelagem/check.png){width="20"}         |
|  6 | Os requisitos descritos como Usability (Usabilidade) estão de acordo com a categoria definida pelo FURPS+? | Garantir que os requisitos não funcionais de usabilidade estão na categoria correta. | ![Simbolo wrong](../../assets/modelagem/wrong.png){width="20"}         |
|  7 | Os requisitos descritos como Usability (Usabilidade) são apenas requisitos não funcionais? | A especificação suplementar abrange apenas requisitos não funcionais. | ![Simbolo wrong](../../assets/modelagem/wrong.png){width="20"}         |
|  8 | Os requisitos descritos como Reliability (Confiabilidade) estão de acordo com a categoria definida pelo FURPS+?  | Garantir que os requisitos não funcionais de confiabilidade estão na categoria correta.                   | ![Simbolo check](../../assets/modelagem/check.png){width="20"}         |
|  9 | Na Confiabilidade há uma previsão do tempo necessário de atividade da aplicação (e possíveis interrupções)? | Um fator importante da confiabilidade é o tempo de operação do aplicativo ininterruptamente. |  ![Simbolo wrong](../../assets/modelagem/wrong.png){width="20"}  |
|  10 | Os requisitos descritos como Performance (Performance) estão de acordo com a categoria definida pelo FURPS+? | Garantir que os requisitos não funcionais de performance estão na categoria correta.|  ![Simbolo check](../../assets/modelagem/check.png){width="20"}  |
|  11 | Na performance é definido o tamanho da aplicação? | Um fator importante de performance/desempenho é o tamanho físico da aplicação. |  ![Simbolo check](../../assets/modelagem/check.png){width="20"}  |
| 12 | Os requisitos descritos como Supportability (Suportabilidade) estão de acordo com a categoria definida pelo FURPS+? | Garantir que os requisitos não funcionais de suportabilidade estão na categoria correta. |  ![Simbolo check](../../assets/modelagem/check.png){width="20"}  |
| 13 | Em suportabilidade, são apresentados exemplos de navegadores web onde a aplicação pode ser acessada? | No quesito suportabilidade é importante citar exemplos de softwares que suportem a execução de suas aplicações. |  ![Simbolo wrong](../../assets/modelagem/wrong.png){width="20"}  |
| 14 | Os requisitos descritos como + (Mais) estão de acordo com a categoria definida pelo FURPS+?  | Garantir que os requisitos não funcionais que não se encaixam nas outras categorias estão na categoria correta.                 | ![Simbolo check](../../assets/modelagem/check.png){width="20"}         |
|  15 | Todos os rastros existentes estão descritos e referenciados?  | Para a rastreabilidade das informações, é importante citar seus rastros e referenciar suas origens. | ![Simbolo check](../../assets/modelagem/check.png){width="20"}|

_Tabela 6: Checklist 10 - Especificação Suplementar. Revisado por Gabriel Mariano._ 

### C11 - NFR Framework

| ID |                                             Questão                                        |Justificativa    | Inspeção |
|----|--------------------------------------------------------------------------------------------|----------------|----------|
|  1 | Foi feito o versionamento do artefato?                                                       | Para o mantenimento da rastreabilidade do artefato, o versionamento é essencial.|  ![Simbolo check](../../assets/modelagem/check.png){width="20"} |
|  2 | As referências bibliográficas foram feitas corretamente?                                     | A citação das referências bibliográficas é necessária para evitar casos de plágio, dando os devidos créditos para o dententor original do conhecimento.  | ![Simbolo check](../../assets/modelagem/check.png){width="20"} |
|  3 | A representação dos tipos de softgoals está de acordo com o padrão usado na NFR Framework?   | A NFR Framework prevê que os softgoals serão representados por nuvens de borda clara, nuvens de borda escura e nuvens de borda pontilhada. | ![Simbolo check](../../assets/modelagem/check.png){width="20"} |
|  4 | As contribuições utilizadas entre os softgoals seguem o padrão da NFR Framework?             | A NFR Framework prevê que as contribuições entre os softgoals serão representadas por AND, OR, MAKE, HELP e HURT. | ![Simbolo check](../../assets/modelagem/check.png){width="20"} |
|  5 | Os rótulos utilizados para avaliação dos softgoals seguem o padrão da NFR Framework?          | A NFR Framework prevê que os softgoals serão avaliados em Satisfeito, Fracamente Satisfeito, Negado, Fracamente Negado, Conflitante e Indeterminado.| ![Simbolo check](../../assets/modelagem/check.png){width="20"} |
|  6 | Foram feitas SIGs para cada uma das categorias do FURPS+ descritas na especifição suplementar? | Garantir que cada categoria do FURPS+ realizado na especificação suplementar recebeu uma SIG referente.| ![Simbolo check](../../assets/modelagem/check.png){width="20"} |
|  7 | Os softgoals foram devidamente refinados?                                                      | Para uma melhor visualização e entendimento dos softgoals, estes devem ser devidamente refinados. | ![Simbolo check](../../assets/modelagem/check.png){width="20"} |
|  8 | As SIGs feitas foram devidamente propagadas?                                                   | Sem uma propagação correta da SIG, o entendimento da NFR Framework fica comprometido.| ![Simbolo check](../../assets/modelagem/wrong.png){width="20"} |
|  9 | O artefato possui legenda correspondente para cada uma das representações usadas?              | Legendas são essenciais para que o leitor entenda o que está sendo representado.| ![Simbolo check](../../assets/modelagem/wrong.png){width="20"} |
| 10 | Os autores das SIGs são descritos?                                                             | Os autores das SIGs devem ser devidamente creditados, para evitar, principalmentem casos de plágio.|![Simbolo check](../../assets/modelagem/wrong.png){width="20"} |

_Tabela 7: Checklist 11 - NFR Framework_ 




## Melhorias

Com base na *checklist* referente aos cenários, identificamos que é necessária uma melhor definição do contexto para cada um deles.

Já pela *checklist* dos léxicos, verificamos que faltou ligação entre os léxicos, e hyperlinks que direcionam as palavras sublinhadas a seus respectivos signigicados.

De acordo com a *checklist* da NFR Framwork, faltou creditar os autores de cada uma das SIGs e propagar-las corretamente, além de melhorar a legenda. 

## Conclusão

Concluimos então, que os artefatos no geral estão de acordo, faltando apenas algumas correções relacionadas a referências, navegação no artefato e documentos com falhas.

## Referências

**Documento de Requisitos do Duolingo**. "Inspeção". Disponível em: <https://requisitos-de-software.github.io/2019.2-Duolingo/analise/verificacao/inspecao/>. Acesso em 16 ago. 2022.

**Documento de Requisitos do Disney Plus**. "Verificação". Disponível em: <https://requisitos-de-software.github.io/2021.1-DisneyPlus/analise/verificacao/verificacao/>. Acesso em 16 ago. 2022.