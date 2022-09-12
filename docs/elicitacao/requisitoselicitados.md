# Requisitos Elicitados

| Versão | Data       |        Modificação        |    Autor     |
| ------ | ---------- | :-----------------------: | :----------: |
| 1.0    | 13/07/2022 | Elicitação dos requisitos |    Grupo     |
| 1.1    | 23/08/2022 | Reestruturando as tabelas | Samuel Ávila |
| 1.2    |   24/08    |   Revisão do artefato     | Felipe Moura    |

_Tabela 01: Versionamento_

## Introdução

Com o objetivo de facilitar futuras consultas, os requisitos elicitados serão compilados nessa página.

## Metodologia

A partir dos métodos utilizados, vários requisitos funcionais e não funcionais foram elicitados. A partir disso, todos foram compilados com sua prioridade e método de origem. Para fazer a priorização dos requisitos nós fizemos uma entrevista com o usuário, fazendo perguntas que seguiam a ideia da Escala de Likert e organizamos a priorização pelo método MoSCoW.

### Entrevista com usuário

Abaixo encontra-se o vídeo usado como referência para a priorização dos requisitos.

| Versão | Data  | Entrevistadores                | Entrevistado(a)   |
| ------ | ----- | ------------------------------ | ----------------- |
| 1.0    | 23/08 | Gabriel Sabanai e Samuel Avila | Fernanda Cordeiro |
| 2.0    | 08/08 | Gabriel Sabanai e Samuel Avila | Fernanda Cordeiro |

[![Entrevista da Priorização](../assets/elicitacao/priorizacao-thumb.jpg)
](https://youtu.be/LOdaob7c1Bc)

_Imagem 01: Vídeo da entrevista com usuário_

# MoSCoW

## Introdução

Tendo base no repositório da aplicação Triagil,é possível se constatar que o MoSCoW é um método de priorização utilizado para especificar os requisitos de acordo com a sua criticidade e seu valor de negócio. Facilita a priorização do escopo de forma a dividir quais tarefas são de suma importância para o sucesso do projeto e quais poderiam ser descartadas caso o mesmo sofra algum tipo de mudança de prazo e/ou perda de recursos. MoSCoW é um aconimo para as 4 categorias de requisitos utilizados na predileção: **M** de _must have_, **S** de _should have_, **C** de _could have_ e **W** de _wont't have ou would like_, como comumente é usado. Portanto, a criticidade e relevância dos requisitos são classificados por:

-  **Must** : Requisitos de extremo interesse para o projeto; sem essas funcionalidades, o produto perde sentido e valor. **Têm** de ser implementados.
-  **Should**: Possuem importância equivalente ao Must, entretanto o seu nível de criticidade para o projeto é menor, ou seja, se não forem desenvolvidos não haverá perda do valor de negócio. **Devem** ser desenvolvidos.

-  **Could**: São requisitos ligados À desejos do cliente, que **poderiam**, mas não precisam se desenvolvidos. Geralmente estão relacionados à aperfeiçoamento da experiência do usuário.
-  **Won't/Would Like**: Requisitos inseridos nessa categoria não são necessários para o projeto além de não gerarem tanto valor de negócio. Serão desenvolvidos **talvez** em próximas versões a apenas depois de todos os requisitos das categorias acima serem desenvolvidos.
   Para a priorização dos requisitos do projeto Jitsi Meet foram utilizados apenas as classificações Must, Could e Would para facilitar o processo de primazia dos requisitos.

## Legenda

| Código | Significado               |
| :----: | :------------------------ |
|   RF   | Requisitos Funcionais     |
|  RNF   | Requisitos Não Funcionais |
|   ST   | Personas e Storytelling   |
|   BS   | Brainstorming             |
|   AP   | Análise de Protocolo      |

_Tabela 02:Legenda para artefatos_

Os requisitos elicitados da análise de protocolo possuí tabelas separadas de Funcionais e Não funcionais. Para melhor entendimento ao agruparmos, levamos em consideração os seguimentos de cada tabela para enumeração com seus respectivos tipos de requisitos.

## Requisitos Funcionais


| ID   | DESCRIÇÃO                                                                                                                                       | ORIGEM                       | PRIORIZAÇÃO |
| ---- | ----------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------- | ----------- |
| RF01 | Eu quero me reunir com duas ou mais pessoas                                                                                                     | ST01, BS28, AP01             | MUST        |
| RF02 | Eu quero me comunicar via chat de texto                                                                                                         | ST03, BS04, AP10             | SHOULD      |
| RF03 | Eu quero compartilhar minha tela com os outros participantes da conferência                                                                     | ST04, BS21, AP09             | SHOULD      |
| RF04 | Eu quero gerar links que direcionem para uma conferência                                                                                        | ST05, AP06                   | MUST        |
| RF05 | Eu quero fixar minha tela compartilhada para todos os integrantes                                                                               | ST06                         | COULD       |
| RF06 | Eu quero que novos participantes sejam automaticamente mutados no chat de voz                                                                   | ST07                         | COULD       |
| RF07 | O Jitsi permite a criação de breakout rooms                                                                                                     | ST08, BS20, AP14             | COULD       |
| RF08 | Eu quero que exista uma restrição para que apenas pessoas permitidas entrem na reunião                                                          | ST09                         | WOULDN'T    |
| RF09 | O Jitsi permite que o dono da sala tenha funções de moderador na reunião                                                                        | ST10, ST11, BS15, AP15, AP16 | MUST        |
| RF10 | Eu quero que seja possível agendar as reuniões                                                                                                  | ST12, BS31, AP03             | COULD       |
| RF11 | Eu quero que seja possível "levantar a mão" durante as chamadas                                                                                 | ST13, BS05                   | SHOULD      |
| RF12 | Eu quero que seja possível aplicar filtros no plano de fundo do vídeo transmitido                                                               | ST14, BS19, AP07             | COULD       |
| RF13 | Eu quero que seja possível escolher a forma de visualização e organização das telas/pessoas                                                     | ST15, BS24, AP13             | SHOULD      |
| RF14 | Eu quero que seja possível se identificar na plataforma com nome                                                                                | ST16, BS26, AP05             | MUST        |
| RF15 | Eu quero que seja possível se identificar na plataforma com foto                                                                                | ST16, BS25, AP05             | SHOULD      |
| RF16 | Eu quero que o usuário possa ativar um filtro de ruídos do áudio                                                                                | ST18                         | SHOULD      |
| RF17 | Eu quero que seja possível ver meu próprio vídeo durante o uso da plataforma                                                                    | ST21                         | MUST        |
| RF18 | Eu quero que seja possível alternar o idioma da plataforma                                                                                      | ST22                         | MUST        |
| RF19 | O Jitsi permite a visualização do histórico de reuniões                                                                                         | BS33, AP04                   | SHOULD      |
| RF20 | O Jitsi permite que o usuário configure o próprio áudio e vídeo                                                                                 | BS06, BS16, AP02             | MUST        |
| RF21 | O Jitsi permite a interação entre os participantes por voz e vídeo                                                                              | BS07, BS10, AP08             | MUST        |
| RF22 | O Jitsi permite que enquetes sejam feitas e respondidas em tempo real                                                                           | BS13, AP11                   | COULD       |
| RF23 | O Jitsi permite reação com emotes pelos usuários                                                                                                | AP12, BS18                   | COULD       |
| RF24 | O Jitsi permite alterações no perfil durante a reunião                                                                                          | AP17                         | COULD       |
| RF25 | O Jitsi permite que o usuário saia a qualquer momento da reunião                                                                                | AP18, BS39                   | MUST        |
| RF26 | A aplicação deve permitir que o usuário possa parar a transmissão de seu video para que o mesmo não seja visto caso não queira                  | BS10                         | MUST        |
| RF27 | A aplicação deve permitir referenciar pessoas no chat da transmissão para que o usuário consiga destacar um usuário em sua mensagem             | BS11                         | SHOULD      |
| RF28 | A aplicação deve permitir a mensagem privada entre usuários para que os mesmos possam conversar em particular durante uma conferência           | BS12                         | WOULDN'T    |
| RF29 | A aplicação deve permitir que um usuário possa compartilhar um quadro de tarefas para que todos os usuários possam visualizar e mexer com ele   | BS17                         | WOULDN'T    |
| RF30 | A aplicação deve permitir que o usuário realize o login para que o mesmo possa acessar suas informações salvas                                  | BS27                         | WOULDN'T    |
| RF31 | A aplicação deve permitir que o usuário faça conexões com outros usuários para que possa ter salvo aqueles que deseja fazer conexões facilmente | BS30                         | WOULDN'T    |

_Tabela 03: Requisitos Funcionais e priorização de acordo com o MoSCoW_

## Requisitos Não Funcionais

| Id    | Descrição                                                                                                    | Origem           | Prioridade |
| ----- | ------------------------------------------------------------------------------------------------------------ | ---------------- | ---------- |
| RNF01 | Eu quero uma interface minimalista                                                                           | ST02             | SHOULD     |
| RNF02 | O Jitsi deve zelar pela privacidade dos usuários                                                             | AP01             | MUST       |
| RNF03 | Eu quero que a plataforma priorize a estabilidade em detrimento da qualidade da conferência                  | ST17, ST19, BS35 | SHOULD     |
| RNF04 | O Jitsi deve ter uma interface que facilite a visualização das mudanças de estado na reunião                 | AP02             | SHOULD     |
| RNF05 | Eu quero que o Jitsi seja usado nas principais plataformas (por exemplo, a plataforma mobile)                | ST20, AP03       | SHOULD     |
| RNF06 | Eu quero que as funcionalidades da plataforma possuam indicações visuais intuitivas                          | ST23, BS38, AP02 | MUST       |
| RNF07 | O Jitsi deve permitir que o usuário altere configurações dos dispositivos de áudio e vídeo durante a reunião | AP04             | MUST       |
| RNF08 | A aplicação deve aceitar entrada e saída de som para que o usuário consiga transmitir sua voz                | BS03             | MUST       |

_Tabela 04: Requisitos Não Funcionais e priorização de acordo com o MoSCoW_

## Considerações finais

|           Tipo            | Quantidade |
| :-----------------------: | :--------- |
|   Requisitos Funcionais   | 31         |
| Requisitos Não Funcionais | 08         |

_Tabela 05: Quantidade de Requisitos_

| MoSCoW  | Quantidade |
| :-----: | :--------- |
|  MUST   | 14         |
| SHOULD  | 12         |
|  COULD  | 8          |
| WOULDNT | 5          |

_Tabela 06: Detalhamento da quantidade de requisitos e priorização_

## Referências

SERRANO, Maurício; SERRANO, Milene. Requisitos - Aula 07. 1º/2022. 50 slides. Material apresentado para a disciplina de Requisitos de Software no curso de Engenharia de Software da UnB, FGA.

**Técnica MoSCoW**. Disponível em: <https://unbarqdsw.github.io/2020.1_G1_Triagil/modelagem/extra/priorizacao/moscow/>
