# SIN142 Comunicacao Indireta
## Comunicação em Grupo :desktop_computer:
Objetivos: nesta aula abordaremos a comunicação em grupo (Multicast) utilizando o JGroups. :chart: \
Requisitos: Sistema Operacional Linux, IntelliJ IDE e Biblioteca JGroups :bulb:

## Passos:

1. Clonar o repositório da aula no PC (de preferência na pasta do usuário)
`git clone https://github.com/romoreira/SIN142-ComunicacaoIndireta-Multicast.git`
2. Extrair e Rodar o IntelliJ IDE (community ou professional)
`tar -zxvf ideaIC-2023.1.tar.gz`
3. Executar o IntelliJ
- `cd ideaIC-2023`
- `ce bin`
- `./idea.sh`
4. Baixar a dependência JGroups via Maven
- Clicar com botão direito no arquivo 'pom.xml' e adicionar como Maven Project.
- Clicar com botão direito no arquivo 'pom.xml' e 'Download Sources'.
5. Rodar o Script (SimpleChar.java)
- Clicar com botão direito sobre o arquivo 'SimpleChat.java' e em seguida 'Run'


## Pergunta-se: :interrobang:

1. Como você pode criar um cluster JGroups?
2. Como você pode configurar JGroups para um caso de uso específico?
3. Como você pode monitorar a saúde e performance de um cluster JGroups?
4. Como você pode integrar o JGroups com outras tecnologias, como Spring Framework ou Apache Camel?


## Proposição: :pencil:

Exercício: Implemente um aplicativo de bate-papo em grupo usando JGroups.

Neste exercício, você implementará um aplicativo simples de bate-papo em grupo usando JGroups. O aplicativo permitirá que vários usuários entrem em uma sala de bate-papo e enviem mensagens uns aos outros em tempo real.

- Implementar envio e recebimento de mensagens: Implemente um mecanismo de envio e recebimento de mensagens usando JGroups. Quando um usuário envia uma mensagem, ela deve ser transmitida para todos os outros nós do cluster. Quando um usuário recebe uma mensagem, ela deve ser exibida em sua tela.

- Implementar a entrada e saída do usuário: implemente um mecanismo para lidar com a entrada e saída do usuário da sala de bate-papo. Quando um usuário entra na sala de bate-papo, ele deve ser adicionado à lista de participantes e receber uma lista de mensagens anteriores. Quando um usuário sai da sala de bate-papo, ele deve ser removido da lista de participantes e seu nome deve ser anunciado no bate-papo.

- Adicionar recursos adicionais: Depois de implementar a funcionalidade básica, considere adicionar recursos adicionais, como mensagens privadas, histórico de mensagens ou autenticação do usuário.

- Teste o aplicativo: teste o aplicativo executando várias instâncias da sala de bate-papo em diferentes máquinas e associando-as ao mesmo cluster. Verifique se as mensagens estão sendo enviadas e recebidas corretamente e se os usuários podem entrar e sair da sala de bate-papo sem problemas.


