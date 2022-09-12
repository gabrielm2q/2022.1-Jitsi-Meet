# Forward From

## Versionamento

| Versão | Data  |          Modificação           |      Autor      |
| ------ | ----- | :----------------------------: | :-------------: |
| 1.0    | 23/08 |      Criação do Documento      | Gabriel Mariano |
| 1.1    | 23/08 |    Documentação das tabelas    |  Samuel Ávila   |
| 1.2    | 24/08 | Complementação da documentação |  Samuel Ávila   |
| 1.3 | 24/08 | Complementação da documentação e criação da introdução e metodologia | Gabriel Sabanai |
| 1.4    | 24/08 | Complementação da documentação | Laís Ramos      |
| 1.5    | 24/08 |       Revisão do artefato      | Felipe Moura    |
| 1.6    | 25/08 | Refatoração dos requisitos de origem | Laís Ramos    |

_Tabela 1: Versionamento_

## Introdução
  O Forward-From é um framework que visa vincular os requisitos elicitados com os artefatos e meios que foram levantados no projeto (SERRANO; SERRANO, 2020). Dessa forma, melhorando sistematicamente sua rastreabilidade.
## Metodologia
  Os requisitos são vinculados a artefatos criados durante o ciclo de vida de desenvolvimento de sistema, no momento da pós-rastreabilidade. A fim de verificar a pós-rastreabilidade entre os requisitos, elementos de impementação, arquitetura e desenho utilizamos o Forward-From. A implementação dessa rastreabilidade ocorre com a utilização de links entre os requisitos e as fontes que implementam estes (TORANZO, 2002). O artefato foi feito pelos integrantes Gabriel Sabanai, Samuel Avilla e Laís Ramos.

  Na tabela 1, abaixo, mostraremos os requisitos e seus relacionamentos com as telas e seus critérios de aceitação.
## Legenda

| Id              | Descrição              | Artefatos                                | Categoria                     | Elo                                        | Tela                                     |
| --------------- | ---------------------- | ---------------------------------------- | ----------------------------- | ------------------------------------------ | ---------------------------------------- |
| Id do requisito | Descrição do requisito | Artefatos que tem origem nesse requisito | Categoria do elo do requisito | Tipo de elo entre requisito e os artefatos | Referência do destino final do requisito |

_Tabela 2: Legenda para tabela de resultados_

| Código | Significado               |
| :----: | :------------------------ |
|   RF   | Requisitos Funcionais     |
|  RNF   | Requisitos Não Funcionais |
|   FT   | Feature                   |
|   US   | User Story                |
|   C    | Cenário                   |
|   L    | Léxico                    |

_Tabela 3: Legenda de nomenclatura dos artefatos_

## Resultados

| Id    | Descrição                                                                                                                                       | Artefatos                             | Tela |
| ----- | ----------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------- | ---- |
| RF01  | Eu quero me reunir com duas ou mais pessoas                                                                                                     | C01, C02, L08, FT02, FT04, FT05, FT09 |      |
| RF02  | Eu quero me comunicar via chat de texto                                                                                                         | C07, L14, FT10                        |      |
| RF03  | Eu quero compartilhar minha tela com os outros participantes da conferência                                                                     | C03, L20, FT07                        |      |
| RF04  | Eu quero gerar links que direcionem para uma conferência                                                                                        | C01, C02, L08, L15, FT09              |      |
| RF05  | Eu quero fixar minha tela compartilhada para todos os integrantes                                                                               | C03, FT07                             |      |
| RF06  | Eu quero que novos participantes sejam automaticamente mutados no chat de voz                                                                   | C04, C16, FT18                        |      |
| RF07  | O Jitsi permite a criação de breakout rooms                                                                                                     | C06, L17, FT08, US13                  |      |
| RF08  | Eu quero que exista uma restrição para que apenas pessoas permitidas entrem na reunião                                                          | C02, FT02, FT09                       |      |
| RF09  | O Jitsi permite que o dono da sala tenha funções de moderador na reunião                                                                        | C16, FT18                             |      |
| RF10  | Eu quero que seja possível agendar as reuniões                                                                                                  | C01, FT01, US02                       |      |
| RF11  | Eu quero que seja possível "levantar a mão" durante as chamadas                                                                                 | C10, FT13, US20                       |      |
| RF12  | Eu quero que seja possível aplicar filtros no plano de fundo do vídeo transmitido                                                               | C13, FT14                             |      |
| RF13  | Eu quero que seja possível escolher a forma de visualização e organização das telas/pessoas                                                     | L18, E04                              |      |
| RF14  | Eu quero que seja possível se identificar na plataforma com nome                                                                                | C01, C02, C14, FT14 |      |
| RF15  | Eu quero que seja possível se identificar na plataforma com foto                                                                                | C01, C02, C14, FT14 |      |
| RF16  | Eu quero que o usuário possa ativar um filtro de ruídos do áudio                                                                                | C15, FT17, FT05 |      |
| RF17  | Eu quero que seja possível ver meu próprio vídeo durante o uso da plataforma                                                                    | C01, C02, C13, C15, FT04, FT16 |      |
| RF18  | Eu quero que seja possível alternar o idioma da plataforma                                                                                      | C14, FT15 |      |
| RF19  | O Jitsi permite a visualização do histórico de reuniões                                                                                         | C08,FT03 |      |
| RF20  | O Jitsi permite que o usuário configure o próprio áudio e vídeo                                                                                 | C15, FT16, FT17, FT18 |      |
| RF21  | O Jitsi permite a interação entre os participantes por voz e vídeo                                                                              | C01, C02, FT04, FT05 |      |
| RF22  | O Jitsi permite que enquetes sejam feitas e respondidas em tempo real                                                                           | C11, C12, FT11 |      |
| RF23  | O Jitsi permite reação com emotes pelos usuários                                                                                                | C07, FT12 |      |
| RF24  | O Jitsi permite alterações no perfil durante a reunião                                                                                          | C14, FT14 |      |
| RF25  | O Jitsi permite que o usuário saia a qualquer momento da reunião                                                                                | C05 |      |
| RF26  | A aplicação deve permitir que o usuário possa parar a transmissão de seu video para que o mesmo não seja visto caso não queira                  |     [F04](../modelagem/agil/historiasDeUsuario.md),[US05](../modelagem/agil/historiasDeUsuario.md)                                   | [RF26](../assets/posRastreabilidade/RF026.jpeg)    |
| RF27  | A aplicação deve permitir referenciar pessoas no chat da transmissão para que o usuário consiga destacar um usuário em sua mensagem             |     [F10](../modelagem/agil/historiasDeUsuario.md),[US15](../modelagem/agil/historiasDeUsuario.md)                                 | [RF027](../assets/posRastreabilidade/RF28_03.png)     |
| RF28  | A aplicação deve permitir a mensagem privada entre usuários para que os mesmos possam conversar em particular durante uma conferência           |     [C07](../modelagem/cenarios.md)                                    |   [RF028](../assets/posRastreabilidade/mensagemPivado.jpg)   |
| RF29  | A aplicação deve permitir que um usuário possa compartilhar um quadro de tarefas para que todos os usuários possam visualizar e mexer com ele   |  [C11](../modelagem/cenarios.md)                                     |   [RF29 Figura 01](../assets/posRastreabilidade/RF29_01.png)<br>[RF029 Figur 02](../assets/posRastreabilidade/RF29_02.png)   |
| RF30  | A aplicação deve permitir que o usuário realize o login para que o mesmo possa acessar suas informações salvas                                  |                    [C02](../modelagem/cenarios.md)                   |  [RF30](../assets/posRastreabilidade/RF30_01.png)    |
| RF31  | A aplicação deve permitir que o usuário faça conexões com outros usuários para que possa ter salvo aqueles que deseja fazer conexões facilmente |  [F03](../modelagem/cenarios.md)                                      |  [RF31](../assets/posRastreabilidade/RF31_1.png)    |
| RNF01 | Eu quero uma interface minimalista                                                                                                              |                 [F05](../modelagem/agil/historiasDeUsuario.md),[US06](../modelagem/agil/historiasDeUsuario.md),[F05](../modelagem/agil/historiasDeUsuario.md),[US08](../modelagem/agil/historiasDeUsuario.md),[F07](../modelagem/agil/historiasDeUsuario.md),[US011](../modelagem/agil/historiasDeUsuario.md)                      |    [RNF01](../assets/posRastreabilidade/RFN01.jpeg)  |
| RNF02 | O Jitsi deve zelar pela privacidade dos usuários                                                                                                |    [C16](../modelagem/cenarios.md)                             | [RNF02](../assets/posRastreabilidade/seguranca.png)     |
| RNF03 | Eu quero que a plataforma priorize a estabilidade em detrimento da qualidade da conferência                                                     |    [F06](../modelagem/agil/historiasDeUsuario.md),[US10](../modelagem/agil/historiasDeUsuario.md)                                      |  [RNF03](../assets/posRastreabilidade/performance.jpg)    |
| RNF04 | O Jitsi deve ter uma interface que facilite a visualização das mudanças de estado na reunião                                                    |  []()       |                                     |   [RNF04](../assets/posRastreabilidade/mudancaDeEstado.png)    |
| RNF05 | Eu quero que o Jitsi seja usado nas principais plataformas (por exemplo, a plataforma mobile)                                                   |        [L01](../modelagem/lexico.md),[L06](../modelagem/lexico.md)                           | [RNF05](../assets/posRastreabilidade/mobile.jpg)     |
| RNF06 | Eu quero que as funcionalidades da plataforma possuam indicações visuais intuitivas                                                             |     [F05](../modelagem/agil/historiasDeUsuario.md),[US06](../modelagem/agil/historiasDeUsuario.md),[F05](../modelagem/agil/historiasDeUsuario.md),[US08](../modelagem/agil/historiasDeUsuario.md),[F07](../modelagem/agil/historiasDeUsuario.md),[US011](../modelagem/agil/historiasDeUsuario.md)                                |  [RNF05](../assets/posRastreabilidade/intuitivo.png)    |
| RNF07 | O Jitsi deve permitir que o usuário altere configurações dos dispositivos de áudio e vídeo durante a reunião                                    |      [C15](../modelagem/cenarios.md),[F16](../modelagem/agil/historiasDeUsuario.md),[US24](../modelagem/agil/historiasDeUsuario.md),[US26](../modelagem/agil/historiasDeUsuario.md),[F17](../modelagem/agil/historiasDeUsuario.md)                             | [RNF07](../assets/posRastreabilidade/configuracoesAudio.jpg)     |
| RNF08 | A aplicação deve aceitar entrada e saída de som para que o usuário consiga transmitir sua voz                                                   |      [F05](../modelagem/agil/historiasDeUsuario.md),[F17](../modelagem/agil/historiasDeUsuario.md),[US27](../modelagem/agil/historiasDeUsuario.md)                                |[RNF08](../assets/posRastreabilidade/configuracoesCamera.jpg)

_Tabela 4: Resultados Forward-From_


## Referências

SERRANO, Maurício; SERRANO, Milene. Requisitos - Aula 26. Acesso em: 24 de Agosto de 2022.


TORANZO, M.; CASTRO, J.; MELLO, E. Uma proposta para melhorar o rastreamento de requisitos. In: WORKSHOP DE ENGENHARIA DE REQUISITOS, 2002, Valência, Espanha. Anais... [S.l.]: [S.n.], 2002. p. 194–209. ISBN 84–96023–01–X. 19, 29, 44, 45, 47, 51, 55, 61.
