# Especificação Suplementar

## Versionamento

| Versão | Data  |               Modificação                |          Autor           |
| ------ | ----- | :--------------------------------------: | :----------------------: |
| 1.0    | 19/07 | Realização da Especificação Suplementar  | André Alves e Laís Ramos |
| 1.1    | 20/07 |            Versão definitiva             |        Laís Ramos        |
| 1.2    | 20/07 |         Criação da Documentação          |       André Alves        |
| 1.3    | 20/07 |         Revisão da Documentação          |     Gabriel Mariano      |
| 1.4    | 12/09 | Correção de pontos listados na checklist |       André Alves e Laís Ramos        |
| 1.5    | 12/09 | Revisão do Artefato |       Gabriel Mariano        |

_Tabela 1: Versionamento_

## Introdução

Especificação Suplementar é um documento em linguagem natural, onde são descritos os Requisitos Não Funcionais. Os requisitos capturados pela Especificação Suplementar não são prontamente capturados nos casos de uso do Modelo de Caso de Uso, e por isso, é considerado um importante complemento para o mesmo. Juntos, capturam todos os requisitos de software (funcionais e não funcionais) que precisam ser descritos para servir como uma Especificação de Requisitos de Software completa.

Entre os requisitos capturados, de acordo com o [**CIn - UFPE**](https://www.cin.ufpe.br/~gta/rup-vc/core.base_rup/workproducts/rup_supplementary_specification_F5ACAA22.html), estão incluídos:

- Requisitos legais e de regulamentação e padrões de aplicativo;
- Atributos de qualidade do sistema a ser desenvolvido, incluindo requisitos de usabilidade, confiabilidade, desempenho e suportabilidade;
- Outros requisitos, tais quais aqueles para os sistemas e ambientes operacionais, compatibilidade com outros software e restrições de design.

## Metodologia

Para a classificação dos requisitos não funcionais do projeto foi utilizados o modelo FURPS+. O acrônimo FURPS+ descreve as principais categorias de requisitos, sendo descritas, de acordo com o [**CIn - UFPE**](https://www.cin.ufpe.br/~gta/rup-vc/core.base_rup/guidances/concepts/requirements_62E28784.html), como:

### F - Funcionality (Funcionalidade)

Os requisitos funcionais podem incluir:

1. Conjunto de recursos
2. Habilidades
3. segurança

### U - Usability (Usabilidade)

Os requisitos de usabilidade lidão com os requisitos relacionado a facilidade do usuário de interagir com a aplicação, e podem incluir :

1. Fatores humanos;
2. Estética;
3. Consistência na interface com o usuário
4. Ajuda on-line e sensível ao contexto
5. Assistentes e agentes
6. Documentação de usuário
7. Materiais de treinamento

### R - Reliability (Confiabilidade)

Os requisitos deste tópico estão relacionados ao grau de confiabilidade da aplicação, conceito que abarca :

1. Frequência e gravidade de falha
2. Possibilidade de recuperação
3. Possibilidade de previsão, exatidão, e etc.

### P - Performance (Performance)

Esta seção visa especificar as características do sistema relacionadas ao desempenho.Um requisito de performance, ou, desempenho, pode incluir:

1. Velocidade
2. Eficiência
3. Produtividade
4. Tempo de resposta
5. Tempo de Recuperação
6. Uso de recurso

### S - Supportability (Suportabilidade)

Os requisitos deste tópico estão relacionados à :

1. Possibilidade de teste
1. Extensibilidade
1. Adaptabilidade
1. Manutenção
1. Compatibilidade
1. Possibilidade de configuração, serviço, instalação e localização (internacionalização).

### + (Mais)

O “+” no modelo FURPS inclui requisitos como:

1. Requisitos de Design - Comumente intitulado como restrições de design, específica ou restringe o design do sistema.
1. Requisitos de implementação - Especifica ou restringe o código ou a construção de um sistema.
1. Requisitos de interface - Especifica um item externo com o qual o sistema deve interagir bem como restrições de formatos, tempos ou outros fatores utilizados por tal interação.
1. Requisitos físicos - Esta categoria de requisito pode ser utilizado para representar requisitos de hardware (como as configurações fíicas de rede obrigatórias).

## Resultado

Por resultado da categorização dos requisitos não funcionais elencados na etapa de elicitação de requisitos:

### Funcionalidade

Tendo sido modelados os requisitos funcionais - por meio das técnicas de Brainstorming, Personas e Análise de Protocolo - de forma categórica, estes podem ser encontrados nestes documentos: [Elicitação de Requisitos](../elicitacao/requisitoselicitados.md) e [Use Case](./useCase.md).

### Usabilidade/Utilidade

#### Usabilidade intuitiva e interface minimalista

O Jits Meet terá uma interface minimalista e intuitiva a fim de reduzir o tempo requerido para que os usuários se tornem produtivos na plataforma, visando facilitar a interação tanto para aqueles mais experientes quanto para os menos experientes ou recentes na aplicação.

Rastro: [Análise de Protocolo](https://requisitos-de-software.github.io/2022.1-Jitsi-Meet/elicitacao/analiseProtocolo/) e [Personas e Storytelling](https://requisitos-de-software.github.io/2022.1-Jitsi-Meet/elicitacao/personas/)

#### Resposta instantânea em vídeo chamadas

Durante as reuniões, a resposta das interações entre os usuários deve ser instantânea, para que haja uma troca de informações flúida e imediata entre os usuários, sem delays e travamentos.

Rastro: [Brainstorming](https://requisitos-de-software.github.io/2022.1-Jitsi-Meet/elicitacao/brainstorming/)

#### Indicações visuais

A aplicação deverá possuir indicações visuais claras e intuitivas que ilustrem as funcionalidades disponíveis na plataforma.

Rastro: [Personas e Storytelling](https://requisitos-de-software.github.io/2022.1-Jitsi-Meet/elicitacao/personas/)

### Confiabilidade

#### Estabilidade

O Jitsi prioriza a estabilidade da reunião em detrimento à qualidade do vídeo.

#### Privacidade

O Jitsi zela pela privacidade dos usuários, não tornando obrigatório a entrada do participante com a câmera aberta, com o áudio aberto ,ou com alguma foto de perfil. Além disso, permite que esse coloque um filtro de fundo. Também não exige email, ou conta logada para a participação de reuniões.

#### Disponibilidade

Como o  Jitse Meet é basicamente stateless, isso é, não guarda estado (com uma possível exceção para o método de autenticação escolhido), ele possui uma elasticidade muito grande, um ponto que ajuda bastante na parte de custos em especial em ambientes em clound. Logo, o software fica disponível na maioria do tempo. Caso haja indisponibilidade, geralmente o usuário é avisado prevamente.

### Performance/ Desempenho

#### Comunicação em tempo real

A aplicação deverá ser capaz de suportar várias pessoas se comunicando simultaneamente e o envio/recebimento de áudio e vídeo entre os participantes deverá ocorrer instantaneamente.

#### Armazenamento da aplicação (mobile)

O usuário deverá possuir um espaço de 52MB para instalar o aplicativo em um dispositivo mobile.

#### Capacidade

O servidor do Jitsi Meet deverá ser capaz de suportar milhares de usuários se comunicando simultaneamente e em diferentes reuniões ao redor do mundo.

### Suportabilidade

#### Web

O Jitsi pode ser acessado através de navegadores em Desktop, SmartPhone e Microcomputadores portáteis.

Browsers suportados:

- Desktop browsers
    - Chrome - Versão >= 72
    - Firefox -Versão >= 68
    - Safari -Versão >=14
    - Edge - Versão >=79
    - Internet Explorer - Não

- Mobile browsers Android
    - Chrome
    - Firefox

- Mobile browsers IOS
    - Chrome
    - Firefox
    - Safari
    - Edge

#### IOS

O Jitsi pode ser acessado por dispositivos Apple, entretanto para sistemas IPhone 12.0 ou superiores, IPad 12.0 ou superiores e IPod touch 12.0 ou superiores.

#### Android

O Jitsi pode ser acessado por dispositivos Android, entretanto para sistemas 6.0 ou superiores.

#### F-Droid

O Jitsi pode ser acessado por dispositivos F-Droid, entretanto para sistemas 6.0 ou superiores.

#### Windows

O Jitsi pode ser acessado por dispositivos desktop Windows, entretanto para sistemas Windows 10 ou superiores.

#### Mac OS

O Jitsi pode ser acessado por dispositivos desktop Mac OS, entretanto para sistemas Mac OS 10.9.

#### Ubuntu

O Jitsi pode ser acessado por dispositivos desktop Ubuntu, entretanto para sistemas Ubuntu 20.04 ou superiores.

#### Debian

O Jitsi pode ser acessado por dispositivos desktop Debian, entretanto para sistemas Debian 10 ou superiores.

### Restrições de Design

O Design do sistema deverá seguir as regras de contribuição disponíveis no repositório do Jitsi Meet. Além disso, as tecnologias utilizadas deverão ser mantidas, como o Javascript, e para o design do frontend, deverá ser mantido o padrão de estilização.

Rastro: [Regras de Contribuição](https://github.com/jitsi/jitsi-meet/blob/master/CONTRIBUTING.md)

### Requisitos de Licença

#### Termos de Uso

O Jitsi Meet disponibiliza os termos de uso para que o usuário concorde com os serviços que o sistema irá oferecer, os componentes da máquina do usuário que serão utilizados e informações sobre privacidade durante o uso da aplicação.

Rastro: [Termos de Uso](https://jitsi.org/meet-jit-si-terms-of-service/)

#### Licença Apache

Como o Jitsi Meet é um software open source, ele utiliza a Licença Apache, que permite que desenvolvedores utilizem o software para qualquer propósito, distribuir, modificar e distribuir versões modificadas.

Rastro: [Licença Apache](https://github.com/jitsi/jitsi-meet/blob/master/LICENSE)

## Referências Bibliográficas

**SERRANO, Maurício; SERRANO, Milene.** "Requisitos - Aula 11".

**CIn - UFPE**. "Artefato: Especificações Suplementares". Disponível em: <https://www.cin.ufpe.br/~gta/rup-vc/core.base_rup/workproducts/rup_supplementary_specification_F5ACAA22.html>.

**CIn - UFPE**. "Conceito: Requisitos". Disponível em: <https://www.cin.ufpe.br/~gta/rup-vc/core.base_rup/guidances/concepts/requirements_62E28784.html>.

**Suportabilidade web:** Disponível em: <https://meet.jit.si/>

**Suportabilidade mobile:** Disponível em: <https://jitsi.org/downloads/>

**Suportabilidade desktop:** Disponível em: <https://desktop.jitsi.org/Main/Download.html>

**Restrições de Design do Jitsi:** Disponível em: <https://github.com/jitsi/jitsi-meet/blob/master/CONTRIBUTING.md>

**Requisitos de Licença do Jitsi:** Disponível em: <https://jitsi.org/meet-jit-si-terms-of-service/>

**Licença Apache do Jitsi:** Disponível em: <https://github.com/jitsi/jitsi-meet/blob/master/LICENSE>

**Blog 4Linus:** Disponível em: <https://blog.4linux.com.br/jitsi-solucao-aberta-completa-para-videoconferencias/>