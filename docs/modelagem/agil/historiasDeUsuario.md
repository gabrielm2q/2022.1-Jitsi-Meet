## Introdução

É um detalhamento curto, informal e em linguagem simples do que o usuário deseja fazer dentro de um produto de software

## Metodologia

Para o desenvolvimento das Histórias de Usuários, foi desenvolvido _cards_, seguindo a estrutura abaixo:

| **Id** | **Significado**  |
|:----------|:-------------:|
| USXX |Título da História|
|Descrição|Eu  gostaria de XX|
|Critérios de Aceitação|Necessita abarcar as seguintes opções: <br>>XXX<br>>XXX|

| **Local** | **Data**  |Hora|
|:----------|:-------------:|:-------------:|
| Discord|02/08|21:00|
 <br>

## Épicos

**Legenda**:

- E: Épico.

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
| Critérios de Aceitação | Deve conter as seguintes opções: </br> > Qual idioma quero aprender </br> > Por que você está aprendendo um idioma </br> > Quantos minutos por dia eu posso estudar </br> > Começar do básico ou teste de nivelamento |



### Feature 2 - Criar reunião.

| **ID**                 | **Nome**                                                                                                                          |
| :--------------------- | :-------------------------------------------------------------------------------------------------------------------------------- |
| US03                   | Gerar link para reunião                                                                                                           |
| Descrição              | Eu, como usuário, desejo gerar links compartilháveis para que eu possa convidar outras pessoas para a minha reunião               |
| Critérios de Aceitação | Deve conter as seguintes opções: </br> > Botão para sincronizar minhas reuniões agendadas</br> > Opção para agendar reuniões</br> |

| **ID**                 | **Nome**                                                                                                                                                              |
| :--------------------- | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| US04                   | Redirecionamento à videoconferência                                                                                                                                   |
| Descrição              | Eu, como usuário, desejo ser redirecionado à videoconferência após clicar em um link ou logo após criar uma nova videochamada para que eu possa participar da reunião |
| Critérios de Aceitação | Deve conter as seguintes opções: </br> > Redirecionamento para videochamada</br>                                                                                      |

### Feature 3 - Visualização do histórico de reuniões.

| **ID**                 | **Nome**                                                                                                                                  |
| :--------------------- | :---------------------------------------------------------------------------------------------------------------------------------------- |
| US05                   | Visualizar reuniões passadas                                                                                                              |
| Descrição              | Eu, como usuário, desejo Visualizar o meu histórico de reuniões para que eu possa checar as reuniões em que eu participei                 |
| Critérios de Aceitação | Deve conter as seguintes opções: </br> > Seção de histórico </br> > Informações básicas sobre cada reunião (data, horário, pessoas, etc.) |

### Feature 4 - Transmissão de vídeo.

| **ID**                 | **Nome**                                                                                                                           |
| :--------------------- | :--------------------------------------------------------------------------------------------------------------------------------- |
| US06                   | Transmitir vídeo                                                                                                                   |
| Descrição              | Eu, como usuário, desejo transmitir meu vídeo para outros participantes para que eu possa ser visualizado por outros participantes |
| Critérios de Aceitação | Deve conter as seguintes opções: </br> > Transmissão da câmera </br> > Pop-up requisitando o uso da câmera do usuário</br>         |

| **ID**                 | **Nome**                                                                                                                             |
| :--------------------- | :----------------------------------------------------------------------------------------------------------------------------------- |
| US07                   | Visualizar vídeo compartilhado                                                                                                       |
| Descrição              | Eu, como usuário, desejo visualizar a Transmissão da câmera de outros participantes para que eu possa conversar visualmente com eles |
| Critérios de Aceitação | Deve conter as seguintes opções: </br> > Visualizar vídeo de outros participantes</br> > Dar zoom em vídeo de participante</br>      |

### Feature 5 - Transmissão de áudio.

| **ID**                 | **Nome**                                                                                                                                           |
| :--------------------- | :------------------------------------------------------------------------------------------------------------------------------------------------- |
| US08                   | Transmissão áudio                                                                                                                                  |
| Descrição              | Eu, como usuário, desejo transmitir o meu áudio para que eu possa ser ouvido por outros participantes                                              |
| Critérios de Aceitação | Deve conter as seguintes opções: </br> > Botão para ativar e desativar áudio</br> > Controle de volume</br> > Envio em tempo real (sem delay)</br> |

| **ID**                 | **Nome**                                                                                                                                               |
| :--------------------- | :----------------------------------------------------------------------------------------------------------------------------------------------------- |
| US09                   | Ouvir áudio de outros participantes                                                                                                                    |
| Descrição              | Eu, como usuário, desejo ouvir o áudio dos outros participan para que eu possa me comunicar com eles                                                   |
| Critérios de Aceitação | Deve conter as seguintes opções: </br> > Botão para ativar e desativar áudio de outros participantes</br> > Recebimento em tempo real (sem delay)</br> |

### Feature 6 - Estatísticas de videochamada.

| **ID**                 | **Nome**                                                                                                                                                                                  |
| :--------------------- | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| US10                   | Visualizar Estatísticas referente aos participantes                                                                                                                                       |
| Descrição              | Eu, como usuário, desejo visualizar estatísticas informativas sobre outros participantes durante a reunião para que eu saiba o status de cada um                                          |
| Critérios de Aceitação | Deve conter as seguintes opções: </br> > Marcação de quem está falando no momento</br> > Sinalização do nível de conexão de cada participante</br> > Sinalizar participantes mutados</br> |

### Feature 7 - Compartilhamento de tela.

| **ID**                 | **Nome**                                                                                                                      |
| :--------------------- | :---------------------------------------------------------------------------------------------------------------------------- |
| US11                   | Compartilhamento de tela                                                                                                      |
| Descrição              | Eu, como usuário, desejo compartilhar a minha tela para que os outros participantes da reunião vejam o que estou transmitindo |
| Critérios de Aceitação | Deve conter as seguintes opções: </br> > Menu para selecionar tela a ser transmitida</br>                                     |

| **ID**                 | **Nome**                                                                                                                                                       |
| :--------------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| US12                   | Visualização de tela compartilhada                                                                                                                             |
| Descrição              | Eu, como usuário, desejo visualizar a tela de um participante que está transmitindo para que eu possa acompanhar o conteúdo sendo compartilhado                |
| Critérios de Aceitação | Deve conter as seguintes opções: </br> > Ver quais participantes estão transmitindo a tela</br> > Selecionar um participante para dar zoom na transmissão</br> |

### Feature 8 - Criação de breakout rooms.

| **ID**                 | **Nome**                                                                                                                          |
| :--------------------- | :-------------------------------------------------------------------------------------------------------------------------------- |
| US13                   | Criação de subsalas durante uma reunião                                                                                           |
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
| **US15** | Implementação de um chat de texto |
|Descrição | Eu gostaria de me comunicar com outros participantes por texto através de um *chat*  e conseguir mencionar outros usuários por meio do mesmo. 
| Critérios de Aceitação | Deve conter as seguintes opções: </br> > Ícone que indica onde iniciar o chat<br> > Aba prórpia para o *chat* de texto</br> > Campo para digitar as mensagens   </br> > Mecanismo que possibilite mencionar outros usuários no *chat*  de texto |

### Feature 11 - Enquetes dentro do chat de texto.

|**ID** | **Nome** |
|:-------|:---------|
| **US16** | Enquetes dentro do chat de texto |
| Descrição |Eu gostaria de criar enquetes e de  responder às enquetes de outros participantes
|Critérios de Aceitação | Deve conter as seguintes opções: </br> > Aba própria para realizar as enquetes  </br> >  </br> > Mecanismo para a criação de enquete   </br> > Campos que indiquem a pergunta e as opções da votação </br> > Possibilidade de adicionar mais opções de enquete </br> > Botão para o envio ou o descarte da enquete |

### Feature 12 - Enviar emotes.

|**ID** | **Nome** |
|:-------|:---------|
| **US17** | Enviar emotes |
| Descrição | Enviar emotes
|Critérios de Aceitação | Deve conter as seguintes opções: </br> > Botão na barra de navegação principal para enviar reações durante a chamada  </br> > Integração das reações com o *chat* de texto  </br> > Mecanismo para que as reações apareçam na tela de reunião em tempo real     |

### Feature 13 - Levantar a mão.

|**ID** | **Nome** |
|:-------|:---------|
| **US18** | Levantar a mão |
| Descrição | Eu gostaria de ‘levantar a mão’ na chamada 
|Critérios de Aceitação | Deve conter as seguintes opções: </br> > Botão na barra de navegação principal que realize o ato de 'levantar a mão' </br> > Indicação na minha  foto de perfil que indique que estou com a 'mão levantada' </br> > Indicação no canto superior da tela principal que indique o número total de pessoas com a mão levantada   |

### Feature 14 - Configurar perfil.

|**ID** | **Nome** |
|:-------|:---------|
| **US19** |Configurar perfil  |
| Descrição |Eu gostaria de me identificar com nome e de me identificar com foto 
|Critérios de Aceitação | Deve conter as seguintes opções: </br> > Opção de login na plataforma Gravatar que sincronize a conta da plataforma ao Jitsi, sincronizando assim a foto de perfil também       |

### Feature 15 - Configurar idioma.

|**ID** | **Nome** |
|:-------|:---------|
| **US20** | Configurar idioma|
| Descrição |Eu gostaria de poder selecionar o idioma da plataforma 
|Critérios de Aceitação | Deve conter as seguintes opções: </br> > Campo de configurações do idioma dentro da aba de configurações  </br> > Campo para escolher o idioma pretendido    |

### Feature 16 - Configuração de vídeo.

|**ID** | **Nome** |
|:-------|:---------|
| **US21** | Configuração de vídeo|
| Descrição |Eu gostaria de poder selecionar a entrada de vídeo que será mostrada e de desabilitar ou habilitar o meu vídeo
|Critérios de Aceitação | Deve conter as seguintes opções: </br> > Ícone que indique as configurações de vídeo </br> > Aba que indique a câmera que gravará o vídeo     |

### Feature 17 - Configuração de áudio.

|**ID** | **Nome** |
|:-------|:---------|
| **US22** | Configuração de áudio|
| Descrição |Eu gostaria de poder selecionar a entrada de áudio e de selecionar entre áudio mutado ou não-mutado
|Critérios de Aceitação | Deve conter as seguintes opções: </br> > Ícone que  indique as configurações de áudio  </br> > Campo que possua as configurações de microfone e que permita a escolha entre configurações padrão ou áudio interno estéreo  </br> > Campo que possua as configurações de alto-falante e que permita a escolha entre configurações padrão ou áudio interno estéreo   |

### Feature 18 - Configuração e moderação da vídeo chamada.

|**ID** | **Nome** |
|:-------|:---------|
| **US23** |Configuração e moderação da videochamada|
| Descrição |Eu gostaria de silenciar outros participantes e de expulsar  participantes indesejados da chamada|Critérios de Aceitação | Deve conter as seguintes opções: </br> > Opção para silenciar todos os participantes  </br> > Opção para parar o vídeo de todos os participantes  </br> > Opção para permitir que os participantes reativem seus sons   </br> > Opção para que os participantes reativem seus vídeos  </br> > Opção para remover participantes indesejados da reunião |