# Pós-Rastreabilidade

## Versionamento

| Versão | Data  |                           Modificação                           |             Autor              |
| ------ | ----- | :-------------------------------------------------------------: | :----------------------------: |
| 1.0    | 08/09 | Criação do Documento | Gabriel Mariano |
| 1.1    | 09/09 | Elaboração do Checklist C14 | Gabriel Mariano |
| 1.2    | 09/09 | Elaboração do Checklist C15 | Felipe Moura |

_Tabela 1: Versionamento_

## Introdução

Com enfoque na [Pós-Rastreabilidade](../../posRastreabilidade/matrizGeral.md), serão avaliados os artefatos produzidos de acordo com as diferentes avaliações de pós-rastreabilidade realizadas ([Backward-From](../../posRastreabilidade/backwardFrom.md) e [Forward-From](../../posRastreabilidade/forwardFrom.md)), verificando se estes artefatos produzidos atendem seus papéis no projeto e se são desenvolvidos de acordo com o que prevê cada avaliação.

## Checklist e Inspeção

### Legenda

| ID | Questão | Justificativa | Inspeção |
|----|---------|---------------|----------|
| Representa a identificação de cada ponto do Checklist  | Representa o ponto a ser avaliado no artefato | Representa a justificativa do ponto a ser avaliado, isto é, o motivo pelo qual esse aspecto é avaliado | Representa a confirmação ![Simbolo check](../../assets/modelagem/check.png){width="10"} ou negação ![Simbolo check](../../assets/modelagem/wrong.png){width="10"} da avaliação do tópico em questão |

_Tabela 2: Legenda dos Checklists_ 

### C14 - Backward-From

#### **Versão 0.1**

| ID | Questão | Justificativa | Inspeção |
|----|---------|---------------|----------|
|  1  | O artefato possui versionamento? | O versionamento é essencial para o acompanhamento da evolução do projeto e de seus artefatos. | ![Simbolo check](../../assets/modelagem/check.png){width="20"} |
|  2  | É utilizado algum Meta-Modelo (Toranzo ou Ramesh & Jarke) no artefato? | Existem Meta-Modelos que guiam a boa elaboração do artefato. | ![Simbolo check](../../assets/modelagem/check.png){width="20"} |
|  3  | O documento possui uma matriz de rastreabilidade? | A matriz de rastreabilidade permite ligar os requisitos às suas origens. | ![Simbolo check](../../assets/modelagem/check.png){width="20"} |
|  4  | As matrizes de rastreabilidade encobrem os requisitos funcionais e não funcionais? | Todos os requisitos, sejam funcionais ou não funcionais, devem ser ligados às suas origens. | ![Simbolo check](../../assets/modelagem/check.png){width="20"} |
|  5  | A origens dos requisitos é disponibilizada com _links_? | Os links permitem o fácil acesso aos documentos que originam os requisitos. | ![Simbolo check](../../assets/modelagem/check.png){width="20"} |
|  6  | O artefato possui Elos de Rastreabilidade? | Na análise Backward-From, os elos de rastreabilidade são importantes para a elaboração do artefato. | ![Simbolo check](../../assets/modelagem/check.png){width="20"} |
|  7  | Os elos são divididos em diferentes tipos (satisfação, recurso, responsabilidade, representação, alocado e agregação)? | O Meta-Modelo de Toranzo prevê a diferenciação de alguns elos de rastreabilidade. | ![Simbolo check](../../assets/modelagem/check.png){width="20"} |
|  8  | O artefato possui as referências utilizadas? | As referências são essenciais no processo de elaboração de quaisquer atividades, sendo fundamentais para evitar plágio e permitir a verificação das fontes. | ![Simbolo check](../../assets/modelagem/check.png){width="20"} |
|  9  | Todas as tabelas e figuras possuem legenda? | Na produção do conhecimento científico, a documentação deve identificar tabelas e figuras. | ![Simbolo check](../../assets/modelagem/check.png){width="20"} |
|  10  | O projeto possui introdução coerente e significativa? | A introdução de um artefato é essencial para guiar o desenvolvimento do projeto e auxiliar no entendimento do mesmo. | ![Simbolo check](../../assets/modelagem/check.png){width="20"} |
|  11  | Todas as siglas apresentadas possuem legenda? | Para o uso de siglas, é essencial a identificação clara do significado das mesmas. | ![Simbolo check](../../assets/modelagem/check.png){width="20"} |

_Tabela 3: Checklist 14 - Backward-From. Produzido por Gabriel Mariano._ 


### C15 - Forward-From

#### **Versão 0.1**

| ID | Questão | Justificativa | Inspeção |
|----|---------|---------------|----------|
| 1 | Foi feito o versionamento do artefato?    | Para o mantenimento da rastreabilidade do artefato, o versionamento é essencial. | ![Simbolo check](../../assets/modelagem/check.png){width="20"}  |
| 2 | As referências bibliográficas foram feitas corretamente? | A citação das referências bibliográficas é necessária para evitar casos de plágio, dando os devidos créditos para o dententor original do conhecimento. | ![Simbolo check](../../assets/modelagem/check.png){width="20"}  |
| 3 | As tabelas possuem legendas?  | As legendas são de extrema importância para o entendimento do leitor sobre o que está sendo abordado.   | ![Simbolo check](../../assets/modelagem/check.png){width="20"}  |
| 4 | Todos os requisitos, principalmente os não implementados, foram abordados?  | Todos os requisitos, em especial os ainda não implementados devem ser abordados, para que se verifique o que foi produzido e o que ainda será, baseado em todo o processo de levantamento de requisitos. | ![Simbolo check](../../assets/modelagem/check.png){width="20"}  |
| 5 | É possível verificar todos os artefatos de origem de cada requisito abordado? | Para que a pós-rastreabilidade seja bem feita, deve ser possível verificar a origem dos requisitos elicitados. | ![Simbolo check](../../assets/modelagem/wrong.png){width="20"}   |
| 6 | Foram desenvolvidos protótipos ou outras evidências para tudo que foi e ainda será produzido, com base nos requisitos elicitados?  | Evidências são necessárias para comprovar o andamento do projeto. | ![Simbolo check](../../assets/modelagem/wrong.png){width="20"}   |

_Tabela 4: Checklist 15 - Backward-From. Produzido por Felipe Moura_
## Melhorias

Com base na checklist C14, verificamos que nenhuma melhoria aparente será necessária.

Já com base na checklist C15, identificamos que falta indicar os artefatos de orgiem de um requisito; e que faltam evidências e protótipos para vários requisitos abordados.

## Conclusão

Concluímos, com base nas checklists desenvolvidas, que serão necessárias correções no artefato [Forward-From](../../posRastreabilidade/forwardFrom.md).

## Referências

**SERRANO, Milene; SERRANO, Maurício**. "Requisitos - Aula 26", 44 slides. Disponibizado em ambiente virtual pelo docente.

**Documento de Requisitos do Duolingo**. "Inspeção". Disponível em: <https://requisitos-de-software.github.io/2019.2-Duolingo/analise/verificacao/inspecao/>. Acesso em 08 set. 2022.

**Documento de Requisitos do Disney Plus**. "Verificação". Disponível em: <https://requisitos-de-software.github.io/2021.1-DisneyPlus/analise/verificacao/verificacao/>. Acesso em 08 set. 2022.