## Versionamento

| Versão | Data  | Descrição            | Autor        |
| ------ | :---: | -------------------- | ------------ |
| 1.0   | 02/08/2022 | Criação do documento | André Alves e Laís Ramos |
| 1.1   | 02/08/2022 | Introdução, metodologia e épicos | André Alves e Laís Ramos |
| 1.2   | 03/08/2022 | Histórias de usuário | André Alves e Laís Ramos |
| 1.3   | 03/08/2022 | Revisão: Correção de Pequenos Erros | Gabriel Mariano |
| 1.4   | 16/08/2022 | Revisão Informal | André Alves e Laís Ramos |

_Tabela 1: Versionamento_

## Introdução

É um detalhamento curto, informal e em linguagem simples do que o usuário deseja fazer dentro de um produto de software.

## Metodologia

Para o desenvolvimento das Histórias de Usuários, foram desenvolvidos _cards_, seguindo a estrutura abaixo:

| **Id** | **Significado**  |
|:----------|:-------------:|
| USXX |Título da História|
|Descrição|Eu  gostaria de XX|
|Critérios de Aceitação|Necessita abarcar as seguintes opções: <br>>XXX<br>>XXX|

| **Local** | **Data**  |Hora|
|:----------|:-------------:|:-------------:|
| Discord|02/08|21:00|



## Épicos

**Legenda**:

- EXX: Épico de Numeração _XX_.

| **Épico**            |                               **Descrição**                                | **Features**                                                                                                                                                                               |
| :------------------- | :------------------------------------------------------------------------: | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| E01 - Tela Inicial   |   Engloba as necessidades do usuário antes de entrar/criar uma reunião.    | > Sincronização com o calendário; </br> > Criar a reunião; </br> > Visualização do histórico de reuniões.                                                                                  |
| E02 - Videochamada   |           Engloba todas as funcionalidades durante uma reunião.            | > Transmissão de vídeo; </br> > Transmissão de áudio; </br> > Estatísticas da videochamada; </br> > Compartilhamento de tela; </br> > Criação de breakout rooms; </br> > Convidar pessoas. |
| E03 - Chat e Reações |         Engloba funcionalidades de interação por texto e reações.          | > Chat de texto; </br> > Enquetes; </br> > Emotes; </br> > Levantar a mão.                                                                                                                 |
| E04 - Configurações  | Engloba as funcionalidades de configurações do usuário e de videochamadas. | > Perfil; </br> > Idioma; </br> > Áudio; </br> > Moderação.                                                                                                                                |

## Features

**Legenda**:

- US: Histórias de Usuários.

### Feature 1 - Sincronização com o calendário.

| **ID** | **Nome** |
|:-------|:---------|
| US01 | Sincronização com o calendário |
| Descrição | Eu, como usuário, desejo sincronizar as reuniões agendadas |
| Critérios de Aceitação | Deve conter as seguintes opções: </br> > Opção para login com conta Google ou conta Microsoft  </br> > Opção para conectar calendário   |



### Feature 2 - Criar reunião.

| **ID**                 | **Nome**                                                                                                                          |
| :--------------------- | :-------------------------------------------------------------------------------------------------------------------------------- |
| US02                   | Gerar link para reunião                                                                                                           |
| Descrição              | Eu, como usuário, desejo gerar links compartilháveis para que eu possa convidar outras pessoas para a minha reunião               |
| Critérios de Aceitação | Deve conter as seguintes opções: </br> > Botão para sincronizar minhas reuniões agendadas</br> > Opção para agendar reuniões</br> |

| **ID**                 | **Nome**                                                                                                                                                              |
| :--------------------- | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| US03                   | Redirecionamento à videoconferência                                                                                                                                   |
| Descrição              | Eu, como usuário, desejo ser redirecionado à videoconferência após clicar em um link ou logo após criar uma nova videochamada para que eu possa participar da reunião |
| Critérios de Aceitação | Deve conter as seguintes opções: </br> > Redirecionamento para videochamada</br>                                                                                      |

### Feature 3 - Visualização do histórico de reuniões.

| **ID**                 | **Nome**                                                                                                                                  |
| :--------------------- | :---------------------------------------------------------------------------------------------------------------------------------------- |
| US04                   | Visualizar reuniões passadas                                                                                                              |
| Descrição              | Eu, como usuário, desejo Visualizar o meu histórico de reuniões para que eu possa checar as reuniões em que eu participei                 |
| Critérios de Aceitação | Deve conter as seguintes opções: </br> > Seção de histórico </br> > Informações básicas sobre cada reunião (data, horário, pessoas, etc.) |

### Feature 4 - Transmissão de vídeo.

| **ID**                 | **Nome**                                                                                                                           |
| :--------------------- | :--------------------------------------------------------------------------------------------------------------------------------- |
| US05                   | Transmitir vídeo                                                                                                                   |
| Descrição              | Eu, como usuário, desejo transmitir meu vídeo para outros participantes para que eu possa ser visualizado por outros participantes |
| Critérios de Aceitação | Deve conter as seguintes opções: </br> > Transmissão da câmera </br> > Pop-up requisitando o uso da câmera do usuário</br>         |

| **ID**                 | **Nome**                                                                                                                             |
| :--------------------- | :----------------------------------------------------------------------------------------------------------------------------------- |
| US06                   | Visualizar transmissão de câmera de outro usuário                                                                                                       |
| Descrição              | Eu, como usuário, desejo visualizar a Transmissão da câmera de outros participantes para que eu possa conversar visualmente com eles |
| Critérios de Aceitação | Deve conter as seguintes opções: </br> > Visualizar vídeo de outros participantes</br> > Dar zoom em vídeo de participante</br>      |

### Feature 5 - Transmissão de áudio.

| **ID**                 | **Nome**                                                                                                                                           |
| :--------------------- | :------------------------------------------------------------------------------------------------------------------------------------------------- |
| US07                   | Transmissão áudio                                                                                                                                  |
| Descrição              | Eu, como usuário, desejo transmitir o meu áudio para que eu possa ser ouvido por outros participantes                                              |
| Critérios de Aceitação | Deve conter as seguintes opções: </br> > Botão para ativar e desativar áudio</br> > Controle de volume</br> > Envio em tempo real (sem delay)</br> |

| **ID**                 | **Nome**                                                                                                                                               |
| :--------------------- | :----------------------------------------------------------------------------------------------------------------------------------------------------- |
| US08                   | Ouvir áudio de outros participantes                                                                                                                    |
| Descrição              | Eu, como usuário, desejo ouvir o áudio dos outros participan para que eu possa me comunicar com eles                                                   |
| Critérios de Aceitação | Deve conter as seguintes opções: </br> > Botão para ativar e desativar áudio de outros participantes</br> > Recebimento em tempo real (sem delay)</br> |

### Feature 6 - Estatísticas de videochamada.

| **ID**                 | **Nome**                                                                                                                                                                                  |
| :--------------------- | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| US09                   | Visualizar Estatísticas referente aos participantes                                                                                                                                       |
| Descrição              | Eu, como usuário, desejo visualizar estatísticas informativas sobre outros participantes durante a reunião para que eu saiba o status de cada um                                          |
| Critérios de Aceitação | Deve conter as seguintes opções: </br> > Marcação de quem está falando no momento</br> > Sinalização do nível de conexão de cada participante</br> > Sinalizar participantes mutados</br> |

### Feature 7 - Compartilhamento de tela.

| **ID**                 | **Nome**                                                                                                                      |
| :--------------------- | :---------------------------------------------------------------------------------------------------------------------------- |
| US10                   | Compartilhamento de tela                                                                                                      |
| Descrição              | Eu, como usuário, desejo compartilhar a minha tela para que os outros participantes da reunião vejam o que estou transmitindo |
| Critérios de Aceitação | Deve conter as seguintes opções: </br> > Menu para selecionar tela a ser transmitida</br>                                     |

| **ID**                 | **Nome**                                                                                                                                                       |
| :--------------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| US11                   | Visualização de tela compartilhada                                                                                                                             |
| Descrição              | Eu, como usuário, desejo visualizar a tela de um participante que está transmitindo para que eu possa acompanhar o conteúdo sendo compartilhado                |
| Critérios de Aceitação | Deve conter as seguintes opções: </br> > Ver quais participantes estão transmitindo a tela</br> > Selecionar um participante para dar zoom na transmissão</br> |

### Feature 8 - Criação de breakout rooms.

| **ID**                 | **Nome**                                                                                                                          |
| :--------------------- | :-------------------------------------------------------------------------------------------------------------------------------- |
| US12                   | Criação de subsalas durante uma reunião                                                                                           |
| Descrição              | Eu, como usuário, desejo criar subsalas durante uma reunião para realizar dinâmicas de breakout rooms e conversas mais reservadas |
| Critérios de Aceitação | Deve conter as seguintes opções: </br> > Criar subsalas dentro de uma reunião</br> > Adicionar participantes à essas salas</br>   |

### Feature 9 - Convidar pessoas.

| **ID**                 | **Nome**                                                                                                             |
| :--------------------- | :------------------------------------------------------------------------------------------------------------------- |
| US13                   | Enviar link para outras pessoas                                                                                      |
| Descrição              | Eu, como usuário, desejo enviar um link que dê acesso à minha reunião para que meus convidados possam participar     |
| Critérios de Aceitação | Deve conter as seguintes opções: </br> > Botão para a criação de link</br> > Permissão de acesso aos convidados</br> |

### Feature 10 - Implementação de um chat de texto.

|**ID** | **Nome** |
|:-------|:---------|
| US14 | Implementação de um chat de texto |
|Descrição | Eu gostaria de me comunicar com outros participantes por texto através de um *chat*  e conseguir mencionar outros usuários por meio do mesmo. 
| Critérios de Aceitação | Deve conter as seguintes opções: </br> > Ícone que indica onde iniciar o chat<br> > Aba prórpia para o *chat* de texto</br> > Campo para digitar as mensagens   </br> > Mecanismo que possibilite mencionar outros usuários no *chat*  de texto |**ID** | **Nome** |:-------|:---------|
| US15 | Mencionar outros usuários em chat de texto |
|Descrição | Eu gostaria de  mencionar outros usuários no chat. 
| Critérios de Aceitação | Deve conter as seguintes opções: </br>  > Mecanismo que possibilite mencionar outros usuários no *chat*  de texto |

### Feature 11 - Enquetes dentro do chat de texto.

|**ID** | **Nome** |
|:-------|:---------|
| US16 | Enquetes dentro do chat de texto |
| Descrição |Eu gostaria de criar enquetes 
|Critérios de Aceitação | Deve conter as seguintes opções: </br> > Aba própria para realizar as enquetes  </br> > Mecanismo para a criação de enquete   </br> > Campos que indiquem a pergunta e as opções da votação </br> > Possibilidade de adicionar mais opções de enquete </br> > Botão para o envio ou o descarte da enquete |
| US17 | Responder enquetes em chat de texto |
| Descrição |Eu gostaria de  responder às enquetes de outros participantes
|Critérios de Aceitação | Deve conter as seguintes opções: </br> > Aba própria para realizar as enquetes  </br> >  Botão para a votação de enquetes |

### Feature 12 - Enviar emotes.

|**ID** | **Nome** |
|:-------|:---------|
| US18 | Enviar emotes |
| Descrição | Enviar emotes
|Critérios de Aceitação | Deve conter as seguintes opções: </br> > Botão na barra de navegação principal para enviar reações durante a chamada  </br> > Integração das reações com o *chat* de texto  </br> > Mecanismo para que as reações apareçam na tela de reunião em tempo real     |

### Feature 13 - Levantar a mão.

|**ID** | **Nome** |
|:-------|:---------|
| US19 | Levantar a mão |
| Descrição | Eu gostaria de ‘levantar a mão’ na chamada 
|Critérios de Aceitação | Deve conter as seguintes opções: </br> > Botão na barra de navegação principal que realize o ato de 'levantar a mão' </br> > Indicação na minha  foto de perfil que indique que estou com a 'mão levantada' </br> > Indicação no canto superior da tela principal que indique o número total de pessoas com a mão levantada   |

### Feature 14 - Configurar perfil.

|**ID** | **Nome** |
|:-------|:---------|
| US20 |Usar foto no perfil  |
| Descrição |Eu gostaria de me identificar com foto  
|Critérios de Aceitação | Deve conter as seguintes opções: </br> > Opção de login na plataforma Gravatar que sincronize a conta da plataforma ao Jitsi       |
| US21 |Configurar perfil  |
| Descrição |Eu gostaria de me identificar com meu nome 
|Critérios de Aceitação | Deve conter as seguintes opções: </br> > Opção de identificação ao entrar na reunião      |

### Feature 15 - Configurar idioma.

|**ID** | **Nome** |
|:-------|:---------|
| US22 | Configurar idioma|
| Descrição |Eu gostaria de poder selecionar o idioma da plataforma 
|Critérios de Aceitação | Deve conter as seguintes opções: </br> > Campo de configurações do idioma dentro da aba de configurações  </br> > Campo para escolher o idioma pretendido    |

### Feature 16 - Configuração de vídeo.

|**ID** | **Nome** |
|:-------|:---------|
| US23 | Configuração de entrada vídeo|
| Descrição |Eu gostaria de poder selecionar a entrada de vídeo que será mostrada 
|Critérios de Aceitação | Deve conter as seguintes opções: </br> > Ícone que indique as configurações de vídeo </br> > Aba que indique a câmera que gravará   |
| US24 | Habilitar ou desabilitar vídeo|
| Descrição |Eu gostaria de desabilitar ou habilitar o meu vídeo
|Critérios de Aceitação | Deve conter as seguintes opções: </br> > Ícone que indique as configurações de vídeo </br> > Opção de desabilitar o meu vídeo     |

### Feature 17 - Configuração de áudio.

|**ID** | **Nome** |
|:-------|:---------|
| US25 | Configuração de entrada áudio|
| Descrição |Eu gostaria de poder selecionar a entrada de áudio 
|Critérios de Aceitação | Deve conter as seguintes opções: </br> > Ícone que  indique as configurações de áudio   </br> > Campo que possua as configurações de alto-falante e que permita a escolha entre configurações padrão ou áudio interno estéreo   |
| US26 | Mutar ou desmutar áudio|
| Descrição |Eu gostaria de poder selecionar entre áudio mutado ou não-mutado
|Critérios de Aceitação | Deve conter as seguintes opções: </br> > Ícone que  indique as configurações de áudio  </br> > Campo que possua as configurações de microfone e que permita a escolha entre configurações padrão ou áudio interno estéreo    |
### Feature 18 - Configuração e moderação da vídeo chamada.

|**ID** | **Nome** |
|:-------|:---------|
| US27 |Moderação d videochamada|
| Descrição |Eu gostaria de silenciar outros participantes
|Critérios de Aceitação| Deve conter as seguintes opções: </br> > Opção para silenciar todos os participantes  </br> > Opção para parar o vídeo de todos os participantes  </br> > Opção para permitir que os participantes reativem seus sons   </br> > Opção para que os participantes reativem seus vídeos|
| US28 |Expulsar usuários de videochamada|
| Descrição |Eu gostaria de  expulsar  participantes indesejados da chamada
|Critérios de Aceitação | Deve conter as seguintes opções:  </br> > Opção para remover participantes indesejados da reunião |


## Referências

**SERRANO, Maurício; SERRANO, Milene**. Requisitos - Aula 15. Material apresentado para a disciplina de Requisitos de Software no curso de Engenharia de Software da UnB - FGA. Acesso em: 02 ago. 2022

**Duolingo**. "Histórias de usuário". Disponível em: <https://requisitos-de-software.github.io/2019.2-Duolingo/modelagem/agil/HistoriasDoUsuarios/>. Acesso em 02 ago. 2022.

**Tembici**. "Histórias de usuário". Disponível em: <https://requisitos-de-software.github.io/2021.2-Tembici/modelagem/backlog/historias_de_usuario/>. Acesso em 02 ago. 2022.

**SEVOCAB**. "Backlog". Disponível em: <https://pascal.computer.org/sev_display/printSearch.action?term=userstories&source=>. Acesso em 02 ago. 2022.