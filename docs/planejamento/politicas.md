# Políticas de contribuição
## Versionamento

| Versão | Data | Modificação | Autor |
|-|-|:-:|:-:|
| 1.0 | 29/06/2022 | Adição da política de contribuição | Gabriel Sabanai |
| 1.0 | 12/09/2022 | Revisão | Gabriel Mariano |

*Tabela 1: versionamento*

## Introdução
As políticas de contribuição são essenciais para a padronização e boas praticas no versionamento do projeto, para o mesmo será utilizado a plataforma _GitHub_.

## Política de Branch

As branches serão nomeadas seguindo um padrão para a melhor organização do projeto. Por se tratar de um projeto baseado em documentos, terá apenas um tipo de nomenclatura de branch. Todas as branchs devem ser criadas a partir da **main** e devem estar nomeadas da seguinte maneira:

``` 
X-NomeDocumento 
Exemplo: 4-PoliticaDeContribuicao
```

 Sendo X o número da issue atribuída seguido pelo nome do documento, como destacado anteriormente. Em ocasiões em que não se está trabalhando com nenhum documento em específico, então deve-se colocar o nome da issue correspondente.

## Política de Commit

Os commits devem ser feitos de maneira clara e objetiva respeitando os padrões comentados a seguir: 


* Devem estar escritos em português.
* Os verbos devem estar no gerúndio.
* Devem apresentar o número base da issue.


Portanto a formatação do commit será: ` #4 Corrigindo documento de planejamento `

Nas ocasiões em que o commit foi realizado por duas ou mais pessoas, deve ser acrescentado à mensagem do commit o seguinte texto: 

```
#4 - Corrigindo documento de politicas


Co-authored-by: Paulo Henrique <ph@gmail.com>
```

<b>Observação:</b> O caracter '#' representa, por padrão, um comentário na mensagem de commit. Para evitar problemas basta digitar o comando: `git config --local core.commentChar auto`

## Referências

Git Breakdown. Politicas de Commit. Disponível em: https://fga-eps-mds.github.io/2019.2-Git-Breakdown/docs/commits.