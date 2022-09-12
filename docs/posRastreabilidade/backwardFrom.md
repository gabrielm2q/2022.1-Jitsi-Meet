# Backward From

## Versionamento

| Versão | Data  |                     Modificação                     |                    Autor                    |
| ------ | ----- | :-------------------------------------------------: | :-----------------------------------------: |
| 1.0    | 23/08 |                Criação do Documento                 |               Gabriel Mariano               |
| 1.1    | 23/08 | Introdução, Metodologia e Matriz de Rastreabilidade | André Alves, Felipe Moura e Gabriel Mariano |
| 1.2    | 24/08 | Adicionando Elos dos Requisitos Funcionais | André Alves, Felipe Moura e Gabriel Mariano |
| 1.3    | 24/08 | Adicionando Elos dos Requisitos Não Funcionais | Gabriel Mariano |
| 1.3 | 24/08 | Revisão | Gabriel Sabanai |
| 1.4 | 12/09 | Revisão: Adicionando Introdução aos Elos de Rastreabilidade | Gabriel Mariano |

_Tabela 1: Versionamento_

## Introdução

Segundo Sayão e Leite (2005), "o rastreamento de requisitos é utilizado para prover relacionamentos entre requisitos, arquitetura e implementação final do sistema". Partindo deste preceito, a _pós-rastreabilidade_ visa, segundo Milene e Maurício Serrano, ligar os requisitos elicitados aos artefatos que deles derivam ao decorrer da elaboração do sistema. Dentre as possíveis análises existentes, temos a _rastreabilidade backward-from_, que visa estabelecer a relação dos requisitos com os artefatos que os originam.

## Metodologia

Inicialmente, será desenvolvida uma _matriz de rastreabilidade_ contendo o ID do requisito, a descrição do mesmo e a origem de cada um. A partir disto, utilizando o **Meta-Modelo proposto por Toranzo** e descrito por Sayão e Leite (2005), serão descritos os elos de cada requisito descrito na matriz de rastreabilidade, especificando suas categorias, elementos rastreáveis e o elo de cada um.

## Introdução aos Elos de Rastreabilidade

De acordo com Sayão e Leite (2005), o **Meta-Modelo proposto por Toranzo** prevê alguns Elos de Rastreabilidade, sendo estes, segundo Sayão e Leite (2005)s:

* **Satisfação:** o requisito de origem pode satisfazer o requisito de destino.
* **Recurso:** o requisito de destino depende de recurso proveniente do requisito de destino.
* **Responsabilidade:** um requisito é responsável pelo outro.
* **Representação:** um requisito pode ser representado por outro.
* **Alocado:** o requisito original aloca o requisito de destino.
* **Agregação:** um requisito é composto por outro.

## Matriz de Rastreabilidade

### Legendas

|             ID             | DESCRIÇÃO                                  |                              ORIGEM                              |
| :------------------------: | ------------------------------------------ | :--------------------------------------------------------------: |
| Identificador do requisito | Descreve o que é solicitado pelo requisito | Identifica os artefatos de elicitação que originaram o requisito |

_Tabela 2: Legenda das Matrizes de Rastreabilidade_

| Código | Significado                                      |
| ------ | ------------------------------------------------ |
| STXX   | Requisito XX do método de _Storytelling_         |
| BSXX   | Requisito XX do método de _Brainstorming_        |
| APXX   | Requisito XX do método de _Análise de Protocolo_ |

_Tabela 3: Legenda dos Códigos dos Requisitos_

### Requisitos Funcionais

|  ID  |                                                                    DESCRIÇÃO                                                                    |                                                                                               ORIGEM                                                                                               |
| :--: | :---------------------------------------------------------------------------------------------------------------------------------------------: | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: |
| RF01 |                                                   Eu quero me reunir com duas ou mais pessoas                                                   |                                        [ST01](../elicitacao/personas.md), [BS27](../elicitacao/brainstorming.md), [AP01](../elicitacao/analiseProtocolo.md)                                        |
| RF02 |                                                     Eu quero me comunicar via chat de texto                                                     |                                        [ST03](../elicitacao/personas.md), [BS03](../elicitacao/brainstorming.md), [AP10](../elicitacao/analiseProtocolo.md)                                        |
| RF03 |                                   Eu quero compartilhar minha tela com os outros participantes da conferência                                   |                                        [ST04](../elicitacao/personas.md), [BS20](../elicitacao/brainstorming.md), [AP09](../elicitacao/analiseProtocolo.md)                                        |
| RF04 |                                            Eu quero gerar links que direcionem para uma conferência                                             |                                                            [ST05](../elicitacao/personas.md), [AP06](../elicitacao/analiseProtocolo.md)                                                            |
| RF05 |                                        Eu quero fixar minha tela compartilhada para todos os integrantes                                        |                                                                                 [ST06](../elicitacao/personas.md)                                                                                  |
| RF06 |                                  Eu quero que novos participantes sejam automaticamente mutados no chat de voz                                  |                                                                                 [ST07](../elicitacao/personas.md)                                                                                  |
| RF07 |                                                   O Jitsi permite a criação de breakout rooms                                                   |                                        [ST08](../elicitacao/personas.md), [BS19](../elicitacao/brainstorming.md), [AP14](../elicitacao/analiseProtocolo.md)                                        |
| RF08 |                             Eu quero que exista uma restrição para que apenas pessoas permitidas entrem na reunião                              |                                                                                 [ST09](../elicitacao/personas.md)                                                                                  |
| RF09 |                                    O Jitsi permite que o dono da sala tenha funções de moderador na reunião                                     | [ST10](../elicitacao/personas.md), [ST11](../elicitacao/personas.md), [BS14](../elicitacao/brainstorming.md), [AP15](../elicitacao/analiseProtocolo.md), [AP16](../elicitacao/analiseProtocolo.md) |
| RF10 |                                                 Eu quero que seja possível agendar as reuniões                                                  |                                        [ST12](../elicitacao/personas.md), [BS30](../elicitacao/brainstorming.md), [AP03](../elicitacao/analiseProtocolo.md)                                        |
| RF11 |                                         Eu quero que seja possível "levantar a mão" durante as chamadas                                         |                                                             [ST13](../elicitacao/personas.md), [BS04](../elicitacao/brainstorming.md)                                                              |
| RF12 |                                Eu quero que seja possível aplicar filtros no plano de fundo do vídeo transmitido                                |                                        [ST14](../elicitacao/personas.md), [BS18](../elicitacao/brainstorming.md), [AP07](../elicitacao/analiseProtocolo.md)                                        |
| RF13 |                           Eu quero que seja possível escolher a forma de visualização e organização das telas/pessoas                           |                                        [ST15](../elicitacao/personas.md), [BS23](../elicitacao/brainstorming.md), [AP13](../elicitacao/analiseProtocolo.md)                                        |
| RF14 |                                        Eu quero que seja possível se identificar na plataforma com nome                                         |                                        [ST16](../elicitacao/personas.md), [BS25](../elicitacao/brainstorming.md), [AP05](../elicitacao/analiseProtocolo.md)                                        |
| RF15 |                                        Eu quero que seja possível se identificar na plataforma com foto                                         |                                        [ST16](../elicitacao/personas.md), [BS24](../elicitacao/brainstorming.md), [AP05](../elicitacao/analiseProtocolo.md)                                        |
| RF16 |                                        Eu quero que o usuário possa ativar um filtro de ruídos do áudio                                         |                                                                                 [ST18](../elicitacao/personas.md)                                                                                  |
| RF17 |                                  Eu quero que seja possível ver meu próprio vídeo durante o uso da plataforma                                   |                                                                                 [ST21](../elicitacao/personas.md)                                                                                  |
| RF18 |                                           Eu quero que seja possível alternar o idioma da plataforma                                            |                                                                                 [ST22](../elicitacao/personas.md)                                                                                  |
| RF19 |                                             O Jitsi permite a visualização do histórico de reuniões                                             |                                                         [BS32](../elicitacao/brainstorming.md), [AP04](../elicitacao/analiseProtocolo.md)                                                          |
| RF20 |                                         O Jitsi permite que o usuário configure o próprio áudio e vídeo                                         |                                     [BS05](../elicitacao/brainstorming.md), [BS15](../elicitacao/brainstorming.md), [AP02](../elicitacao/analiseProtocolo.md)                                      |
| RF21 |                                       O Jitsi permite a interação entre os participantes por voz e vídeo                                        |                                     [BS06](../elicitacao/brainstorming.md), [BS08](../elicitacao/brainstorming.md), [AP08](../elicitacao/analiseProtocolo.md)                                      |
| RF22 |                                      O Jitsi permite que enquetes sejam feitas e respondidas em tempo real                                      |                                                         [BS12](../elicitacao/brainstorming.md), [AP11](../elicitacao/analiseProtocolo.md)                                                          |
| RF23 |                                                O Jitsi permite reação com emotes pelos usuários                                                 |                                                         [AP12](../elicitacao/analiseProtocolo.md), [BS17](../elicitacao/brainstorming.md)                                                          |
| RF24 |                                             O Jitsi permite alterações no perfil durante a reunião                                              |                                                                             [AP17](../elicitacao/analiseProtocolo.md)                                                                              |
| RF25 |                                        O Jitsi permite que o usuário saia a qualquer momento da reunião                                         |                                                         [AP18](../elicitacao/analiseProtocolo.md), [BS38](../elicitacao/brainstorming.md)                                                          |
| RF26 |         A aplicação deve permitir que o usuário possa parar a transmissão de seu video para que o mesmo não seja visto caso não queira          |                                                                               [BS09](../elicitacao/brainstorming.md)                                                                               |
| RF27 |       A aplicação deve permitir referenciar pessoas no chat da transmissão para que o usuário consiga destacar um usuário em sua mensagem       |                                                                               [BS10](../elicitacao/brainstorming.md)                                                                               |
| RF28 |      A aplicação deve permitir a mensagem privada entre usuários para que os mesmos possam conversar em particular durante uma conferência      |                                                                               [BS11](../elicitacao/brainstorming.md)                                                                               |
| RF29 |  A aplicação deve permitir que um usuário possa compartilhar um quadro de tarefas para que todos os usuários possam visualizar e mexer com ele  |                                                                               [BS16](../elicitacao/brainstorming.md)                                                                               |
| RF30 |                 A aplicação deve permitir que o usuário realize o login para que o mesmo possa acessar suas informações salvas                  |                                                                               [BS26](../elicitacao/brainstorming.md)                                                                               |
| RF31 | A aplicação deve permitir que o usuário faça conexões com outros usuários para que possa ter salvo aqueles que deseja fazer conexões facilmente |                                                                               [BS29](../elicitacao/brainstorming.md)                                                                               |

_Tabela 4: Matriz de Rastreabilidade - Requisitos Funcionais_

### Requisitos Não Funcionais

|  ID   |                                                  DESCRIÇÃO                                                   |                                                        ORIGEM                                                        |
| :---: | :----------------------------------------------------------------------------------------------------------: | :------------------------------------------------------------------------------------------------------------------: |
| RNF01 |                                      Eu quero uma interface minimalista                                      |                                          [ST02](../elicitacao/personas.md)                                           |
| RNF02 |                               O Jitsi deve zelar pela privacidade dos usuários                               |                                      [AP01](../elicitacao/analiseProtocolo.md)                                       |
| RNF03 |         Eu quero que a plataforma priorize a estabilidade em detrimento da qualidade da conferência          |     [ST17](../elicitacao/personas.md), [ST19](../elicitacao/personas.md), [BS34](../elicitacao/brainstorming.md)     |
| RNF04 |         O Jitsi deve ter uma interface que facilite a visualização das mudanças de estado na reunião         |                                      [AP02](../elicitacao/analiseProtocolo.md)                                       |
| RNF05 |        Eu quero que o Jitsi seja usado nas principais plataformas (por exemplo, a plataforma mobile)         |                     [ST20](../elicitacao/personas.md), [AP03](../elicitacao/analiseProtocolo.md)                     |
| RNF06 |             Eu quero que as funcionalidades da plataforma possuam indicações visuais intuitivas              | [ST23](../elicitacao/personas.md), [BS37](../elicitacao/brainstorming.md), [AP02](../elicitacao/analiseProtocolo.md) |
| RNF07 | O Jitsi deve permitir que o usuário altere configurações dos dispositivos de áudio e vídeo durante a reunião |                                      [AP04](../elicitacao/analiseProtocolo.md)                                       |
| RNF08 |        A aplicação deve aceitar entrada e saída de som para que o usuário consiga transmitir sua voz         |                                        [BS02](../elicitacao/brainstorming.md)                                        |

_Tabela 5: Matriz de Rastreabilidade - Requisitos Não Funcionais_

## Elos de Rastreabilidade

---

### RF01

**Categoria:**

- Desenvolvimento

**Elementos Rastreáveis:**

- Storytelling [ST01](../elicitacao/personas.md)
- Brainstorm [BS27](../elicitacao/brainstorming.md)
- Análise de Protocolo [AP01](../elicitacao/analiseProtocolo.md)

**Elo:**

- Representação: BS28 e AP01 representam ST01

---

### RF02

**Categoria:**

- Desenvolvimento

**Elementos Rastreáveis:**

- Storytelling [ST03](../elicitacao/personas.md)
- Brainstorm [BS03](../elicitacao/brainstorming.md)
- Análise de Protocolo [AP10](../elicitacao/analiseProtocolo.md)

**Elo:**

- Representação: BS03 e AP10 representam ST03

---

### RF03

**Categoria:**

- Desenvolvimento

**Elementos Rastreáveis:**

- Storytelling [ST04](../elicitacao/personas.md)
- Brainstorm [BS20](../elicitacao/brainstorming.md)
- Análise de Protocolo [AP09](../elicitacao/analiseProtocolo.md)

**Elo:**

- Representação: BS20 e AP09 representam ST04

---

### RF04

**Categoria:**

- Desenvolvimento

**Elementos Rastreáveis:**

- Storytelling [ST05](../elicitacao/personas.md)
- Brainstorm [AP06](../elicitacao/analiseProtocolo.md)

**Elo:**

- Representação: AP06 representa ST05

---

### RF05

**Categoria:**

- Desenvolvimento

**Elementos Rastreáveis:**

- Storytelling [ST06](../elicitacao/personas.md)

**Elo:**

- Não há elo entre artefatos

---

### RF06

**Categoria:**

- Desenvolvimento

**Elementos Rastreáveis:**

- Storytelling [ST07](../elicitacao/personas.md)

**Elo:**

- Não há elo entre artefatos

---

### RF07

**Categoria:**

- Desenvolvimento

**Elementos Rastreáveis:**

- Storytelling [ST08](../elicitacao/personas.md)
- Brainstorm [BS19](../elicitacao/brainstorming.md)
- Análise de Protocolo [AP14](../elicitacao/analiseProtocolo.md)

**Elo:**

- Representação: BS19 e AP14 representam ST08

---

### RF08

**Categoria:**

- Desenvolvimento

**Elementos Rastreáveis:**

- Storytelling [ST09](../elicitacao/personas.md)

**Elo:**

- Não há elo entre artefatos

---

### RF09

**Categoria:**

- Desenvolvimento

**Elementos Rastreáveis:**

- Storytelling [ST10](../elicitacao/personas.md)
- Storytelling [ST11](../elicitacao/personas.md)
- Brainstorm [BS14](../elicitacao/brainstorming.md)
- Análise de Protocolo [AP15](../elicitacao/analiseProtocolo.md)
- Análise de Protocolo [AP16](../elicitacao/analiseProtocolo.md)

**Elo:**

- Agregação: ST11 agrega ST10
- Agregação: AP16 e BS14 agregam AP15
- Representação: AP15 representa ST10 e ST11

---

### RF10

**Categoria:**

- Desenvolvimento

**Elementos Rastreáveis:**

- Storytelling [ST12](../elicitacao/personas.md)
- Brainstorm [BS30](../elicitacao/brainstorming.md)
- Análise de Protocolo [AP03](../elicitacao/analiseProtocolo.md)

**Elo:**

- Agregação: AP03 agrega BS30
- Recurso: ST12 depende de BS30 e AP03

---

### RF11

**Categoria:**

- Desenvolvimento

**Elementos Rastreáveis:**

- Storytelling [ST13](../elicitacao/personas.md)
- Brainstorm [BS04](../elicitacao/brainstorming.md)

**Elo:**

- Representação: BS04 representa ST13

---

### RF12

**Categoria:**

- Desenvolvimento

**Elementos Rastreáveis:**

- Storytelling [ST14](../elicitacao/personas.md)
- Brainstorm [BS18](../elicitacao/brainstorming.md)
- Análise de Protocolo [AP07](../elicitacao/analiseProtocolo.md)

**Elo:**

- Representação: AP07 e BS18 representam ST14

---

### RF13

**Categoria:**

- Desenvolvimento

**Elementos Rastreáveis:**

- Storytelling [ST15](../elicitacao/personas.md)
- Brainstorm [BS23](../elicitacao/brainstorming.md)
- Análise de Protocolo [AP13](../elicitacao/analiseProtocolo.md)

**Elo:**

- Representação: AP13 e BS23 representam ST15

---

### **RF14**

**Categoria:**

- Desenvolvimento

**Elementos Rastreáveis:**

- Storytelling [ST16](../elicitacao/personas.md)
- Brainstorm [BS25](../elicitacao/brainstorming.md)
- Análise de Protocolo [AP05](../elicitacao/analiseProtocolo.md)

**Elo:**

- Recurso: [AP05](../elicitacao/analiseProtocolo.md) depende do recurso de [BS26](../elicitacao/brainstorming.md).
- Representação: [BS26](../elicitacao/brainstorming.md) representa [ST16](../elicitacao/personas.md) .

---

### **RF15**

**Categoria:**

- Desenvolvimento

**Elementos Rastreáveis:**

- Storytelling [ST16](../elicitacao/personas.md)
- Brainstorm [BS24](../elicitacao/brainstorming.md)
- Análise de Protocolo [AP05](../elicitacao/analiseProtocolo.md)

**Elo:**

- Recurso: [AP05](../elicitacao/analiseProtocolo.md) depende do recurso de [BS24](../elicitacao/brainstorming.md).
- Representação: [BS24](../elicitacao/brainstorming.md) representa [ST16](../elicitacao/personas.md) .

---

### **RF16**

**Categoria:**

- Desenvolvimento

**Elementos Rastreáveis:**

- Storytelling [ST18](../elicitacao/personas.md)

**Elo:**

- Não há elo entre artefatos.

---

### **RF17**

**Categoria:**

- Desenvolvimento

**Elementos Rastreáveis:**

- Storytelling [ST21](../elicitacao/personas.md)

**Elo:**

- Não há elo entre artefatos.

---

### **RF18**

**Categoria:**

- Desenvolvimento

**Elementos Rastreáveis:**

- Storytelling [ST22](../elicitacao/personas.md)

**Elo:**

- Não há elo entre artefatos.

---

### **RF19**

**Categoria:**

- Desenvolvimento

**Elementos Rastreáveis:**

- Brainstorm [BS32](../elicitacao/brainstorming.md)
- Análise de Protocolo [AP04](../elicitacao/analiseProtocolo.md)

**Elo:**

- Representação: [AP04](../elicitacao/analiseProtocolo.md) representa [BS32](../elicitacao/brainstorming.md).

---

### **RF20**

**Categoria:**

- Desenvolvimento

**Elementos Rastreáveis:**

- Brainstorm [BS05](../elicitacao/brainstorming.md) e [BS15](../elicitacao/brainstorming.md)
- Análise de Protocolo [AP02](../elicitacao/analiseProtocolo.md)

**Elo:**

- Agregação: [BS15](../elicitacao/brainstorming.md) agrega [BS05](../elicitacao/brainstorming.md).
- Representação: [AP02](../elicitacao/analiseProtocolo.md) representa [BS15](../elicitacao/brainstorming.md).
- Representação: [AP02](../elicitacao/analiseProtocolo.md) representa [BS05](../elicitacao/brainstorming.md).

---

### **RF21**

**Categoria:**

- Desenvolvimento

**Elementos Rastreáveis:**

- Brainstorm [BS06](../elicitacao/brainstorming.md) e [BS08](../elicitacao/brainstorming.md)
- Análise de Protocolo [AP08](../elicitacao/analiseProtocolo.md)

**Elo:**

- Agregação: [BS06](../elicitacao/brainstorming.md) agrega [BS08](../elicitacao/brainstorming.md).
- Representação: [AP08](../elicitacao/analiseProtocolo.md) representa [BS06](../elicitacao/brainstorming.md).
- Representação: [AP08](../elicitacao/analiseProtocolo.md) representa [BS08](../elicitacao/brainstorming.md).

---

### **RF22**

**Categoria:**

- Desenvolvimento

**Elementos Rastreáveis:**

- Brainstorm [BS12](../elicitacao/brainstorming.md)
- Análise de Protocolo [AP11](../elicitacao/analiseProtocolo.md)

**Elo:**

- Representação: [AP11](../elicitacao/analiseProtocolo.md) representa [BS12](../elicitacao/brainstorming.md).

---

### **RF23**

**Categoria:**

- Desenvolvimento

**Elementos Rastreáveis:**

- Brainstorm [BS17](../elicitacao/brainstorming.md)
- Análise de Protocolo [AP12](../elicitacao/analiseProtocolo.md)

**Elo:**

- Representação: [AP12](../elicitacao/analiseProtocolo.md) representa [BS17](../elicitacao/brainstorming.md).

---

### **RF24**

**Categoria:**

- Desenvolvimento

**Elementos Rastreáveis:**

- Análise de Protocolo [AP17](../elicitacao/analiseProtocolo.md)

**Elo:**

- Não há elo entre artefatos.

---

### **RF25**

**Categoria:**

- Desenvolvimento

**Elementos Rastreáveis:**

- Brainstorm [BS38](../elicitacao/brainstorming.md)
- Análise de Protocolo [AP18](../elicitacao/analiseProtocolo.md)

**Elo:**

- Representação: [AP18](../elicitacao/analiseProtocolo.md) representa [BS38](../elicitacao/brainstorming.md).

---

### **RF26**

**Categoria:**

- Desenvolvimento

**Elementos Rastreáveis:**

- Brainstorm [BS09](../elicitacao/brainstorming.md)

**Elo:**

- Não há elo entre artefatos.

---

### **RF27**

**Categoria:**

- Desenvolvimento

**Elementos Rastreáveis:**

- Brainstorm [BS10](../elicitacao/brainstorming.md)

**Elo:**

- Não há elo entre artefatos.

---

### **RF28**

**Categoria:**

- Desenvolvimento

**Elementos Rastreáveis:**

- Brainstorm [BS11](../elicitacao/brainstorming.md)

**Elo:**

- Não há elo entre artefatos.

---

### **RF29**

**Categoria:**

- Desenvolvimento

**Elementos Rastreáveis:**

- Brainstorm [BS16](../elicitacao/brainstorming.md)

**Elo:**

- Não há elo entre artefatos.

---

### **RF30**

**Categoria:**

- Desenvolvimento

**Elementos Rastreáveis:**

- Brainstorm [BS26](../elicitacao/brainstorming.md)

**Elo:**

- Não há elo entre artefatos.

---

### **RF31**

**Categoria:**

- Desenvolvimento

**Elementos Rastreáveis:**

- Brainstorm [BS29](../elicitacao/brainstorming.md)

**Elo:**

- Não há elo entre artefatos.

---

### **RNF01**

**Categoria:**

- Desenvolvimento

**Elementos Rastreáveis:**

- Storytelling [ST02](../elicitacao/personas.md)

**Elo:**

- Não há elo entre artefatos.

---

### **RNF02**

**Categoria:**

- Desenvolvimento

**Elementos Rastreáveis:**

- Análise de Protocolo [AP01](../elicitacao/analiseProtocolo.md)

**Elo:**

- Não há elo entre artefatos.

---

### **RNF03**

**Categoria:**

- Desenvolvimento

**Elementos Rastreáveis:**

- Storytelling [ST17](../elicitacao/personas.md)
- Storytelling [ST19](../elicitacao/personas.md)
- Brainstorming [BS34](../elicitacao/brainstorming.md)

**Elo:**

- Recurso: ST17 depende de um recurso de BS34
- Satisfação: ST17 satisfaz ST19

---

### **RNF04**

**Categoria:**

- Desenvolvimento

**Elementos Rastreáveis:**

- Análise de Protocolo [AP02](../elicitacao/analiseProtocolo.md)

**Elo:**

- Não há elo entre artefatos.

---

### **RNF05**

**Categoria:**

- Desenvolvimento

**Elementos Rastreáveis:**

- Storytelling [ST20](../elicitacao/personas.md)
- Análise de Protocolo [AP03](../elicitacao/analiseProtocolo.md)

**Elo:**

- Agregação: AP03 agrega ST20

---

### **RNF06**

**Categoria:**

- Desenvolvimento

**Elementos Rastreáveis:**

- Storytelling [ST23](../elicitacao/personas.md)
- Brainstorming [BS37](../elicitacao/brainstorming.md)
- Análise de Protocolo [AP02](../elicitacao/analiseProtocolo.md)

**Elo:**

- Agregação: ST23 agrega BS37 e AP02
- Satisfação: AP02 satisfaz BS37

---

### **RNF07**

**Categoria:**

- Desenvolvimento

**Elementos Rastreáveis:**

- Análise de Protocolo [AP04](../elicitacao/analiseProtocolo.md)

**Elo:**

- Não há elo entre artefatos.

---

### **RNF08**

**Categoria:**

- Desenvolvimento

**Elementos Rastreáveis:**

- Brainstorming [BS02](../elicitacao/brainstorming.md)

**Elo:**

- Não há elo entre artefatos.

---

## Referências

**SERRANO, Milene; SERRANO, Maurício**. "Requisitos - Aula 26", 44 slides. Disponibizado em ambiente virtual pelo docente.

SAYÃO, Miriam; LEITE, Julio Cesar Sampaio do Prado. **Rastreabilidade de Requisitos**. 2005. 22 f. Monografia (Especialização) - Curso de Ciência da Computação, Departamento de Informática, Pontifícia Universidade Católica do Rio de Janeiro, Rio de Janeiro, 2005.

**Projeto de Requisitos - Ingresso.com**. "Backward From". Disponível em: <https://requisitos-de-software.github.io/2021.1-Ingresso.com/pos_rastreabilidade/backward_from/#rf01>. Acesso em 23 ago. 2022.

**Projeto de Requisitos - TemBici**. "Backward-From". Disponível em: <https://requisitos-de-software.github.io/2021.2-Tembici/pos-rastreabilidade/backward-from/>. Acesso em 23 ago. 2022.

**Projeto de Requisitos - Disney Plus**. "Backward-from". Disponível em: <https://requisitos-de-software.github.io/2021.1-DisneyPlus/pos_rastreabilidade/backward_from/>. Acesso em 23 ago. 2022.

**Projeto de Requisitos - Duolingo**. "Backward From". Disponível em: <https://requisitos-de-software.github.io/2019.2-Duolingo/posrastreabilidade/BackwardFrom/#ef01>. Acesso em 23 ago. 2022.
