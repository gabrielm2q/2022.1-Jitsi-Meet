# Viewpoint

## Versionamento

| Versão | Data  |                           Modificação                           |             Autor              |
| ------ | ----- | :-------------------------------------------------------------: | :----------------------------: |
| 1.0    | 16/08 | Discovery | Gabriel Sabanai |
| 1.1    | 17/08 | Criação do documento | Gabriel Sabanai |
| 1.2    | 17/08 | Adição dos esquemas de viewpoints | Gabriel Sabanai |

## Introdução

A utilização de viewpoints como forma de validação tem por objetivo realizar uma validação prévia dos requisito de um projeto (Leite; Freeman, 1991). Atuando como uma forma de validação informal, utilizando-a conseguimos prever diferentes contextos do sistema a partir de diferentes pontos de vista, e que a diferença entre a avaliação resultante entre os diferentes casos pode ser usado como uma forma de auxiliar na validação inicial dos requisitos (Messaoudi, 2013).

## Metodologia

Para executar a validação por meio de viewpoints, foi utilizado a metodologia proposta por Julio Cesar Sampaio do Prado Leite e por Peter A. Freeman. Esse modelo consiste, em utilizar 2 viewpoints, tais quais, o de perspectiva de processo e o de perspectiva de usuário, na qual a de processo mostrará o ponto de vista da equipe em relação ao universo do discurso elaborado e o de usuário envolverá a visão do usuário que participou da [Análise de Protocolo](../../elicitacao/analiseProtocolo.md).

Vale ressaltar que a validação será feita levando apenas o domínio dos artefatos produzidos pela equipe e seu escopo irá desconsiderar quaisquer documentos proposto pelo app, visto que não foram elaborados pelos membros do projeto de requisitos.

### Universo do Discurso

Para realizar o viewpoint de perspectiva de processo e entender melhor os requisitos, definimos um universo do discurso que guiou no processo de validação.
Segue o universo a seguir:

***"Criar uma reunião e fazer uma video transmissão. Qualquer usuário pode criar uma reunião, entretando ele pode se cadastrar e realizar login; Ele pode tomar duas ações; Elas são: Nomear uma reunião e cria-lá ou entrar em uma reunião já existente. Dentro da reunião ele pode enviar o link para outros usuários acessa-lá, conversar por chat, compartilhar tela e comversar por voz."***

## Viewpoint Processo

      Perspectiva de Processo:
        ((usuario =id-usuario =nome-usuario =email =imagem-usuario)
         (amigo =id-amigo =nome-amigo =email =imagem-amigo)
         (reuniao =id-reuniao =nome-reuniao =duracao-reuniao =participantes-duracao-reuniao)
         (mensagem-chat =id-mensagem-chat =texto-mensagem-chat =horario-mensagem-chat)
         (enquetes =id-enquete =opcoes-enquete =mais-votado)
         (seguranca =verdadeiro/falso)
         (camera =ligada =desligada)
         (audio =ligada =desligada)
         (compartilhar-tela =ligada =desligada)
         ($add-to wm (camera =ligada =desligada))
         ($delete-from wm (camera =ligada =desligada))
         ($add-to wm (audio =ligada =desligada))
         ($delete-from wm (audio =ligada =desligada))
         ($add-to wm (compartilhar-tela =ligada =desligada))
         ($delete-from wm (compartilhar-tela =ligada =desligada))

      Hierarquia:
        (é-um
          (objeto (reuniao amigo mensagem-chat enquetes seguranca camera audio compartilhar-tela))
          (agente (usuario))
          (acao (add-to delete-from)))


## Viewpoint Usuário
 A autora responsável pela perspectiva é a Fernanda Domenica Gagliardi Cordeiro. [Sua perspectiva](../../elicitacao/analiseProtocolo.md) foi realizada no dia 05/07/2022.

      Perspectiva de Usuário:
        ((usuario =id-usuario =nome-usuario)
         (reuniao =id-reuniao =nome-reuniao =duracao-reuniao =participantes-duracao-reuniao)
         (mensagem-chat =id-mensagem-chat =texto-mensagem-chat =horario-mensagem-chat)
         (enquetes =id-enquete =opcoes-enquete =mais-votado)
         (seguranca =verdadeiro/falso)
         (camera =ligada =desligada)
         (audio =ligada =desligada)
         (compartilhar-tela =ligada =desligada)
         ($add-to wm (camera =ligada =desligada))
         ($delete-from wm (camera =ligada =desligada))
         ($add-to wm (audio =ligada =desligada))
         ($delete-from wm (audio =ligada =desligada))
         ($add-to wm (compartilhar-tela =ligada =desligada))
         ($delete-from wm (compartilhar-tela =ligada =desligada))

      Hierarquia:
        (é-um
          (objeto (reuniao mensagem-chat enquetes seguranca camera audio compartilhar-tela))
          (agente (usuario))
          (acao (add-to delete-from)))

## Conclusão sobre os resultado

O objetivo dessa seção é fazer a identificação e comparação das duas viewpoints e ver se existe alguma inconsistência, fato errado ou faltante dado os dois pontos de vista.

### Inconsistências

**Perspectiva do processo**

* Não aprensenta nenhuma inconsistência.

**Perspectiva do usuário**

* Aplicação as vezes demora para carregar seu conteúdo.

### Fatos Faltantes

**Perspectiva do processo**

* Não apresenta nenhum fato faltante.

**Perspectiva do usuário**

* Não existe a possibilidade de criação de usuário.

## Avaliação e Integração

Percebe-se que os elementos expostos na perspecitiva de processo estão melhor detalhados, já que nesse caso representam uma visão geral sobre o projeto. Logo é importante ressaltar aque as inconsistencias apontadas pelo usuário não são inconsistencias na perspectiva de processo já que acompanham uma visão mais téncica e não de uso do produto em si.

## Bibliografia

Messaoudi M. Requirements Engineering Through Viewpoints. Faculty of Sciences, Imam University, Riyadh, Saudi Arabia. 2013.

Leite, J. C. S. P.; Freeman, P. A. Requirements Validation Through Viewpoint Resolution. IEEE TRANSACTIONS ON SOFTWARE ENGINEERING. vol. 17, no. 12, dezembro 1991.

INGRESSO.COM. Disponível em: (https://requisitos-de-software.github.io/2021.1-Ingresso.com/validacao/viewpoint/)[https://requisitos-de-software.github.io/2021.1-Ingresso.com/validacao/viewpoint/]. Acessado em: 16 de agosto de 2022.