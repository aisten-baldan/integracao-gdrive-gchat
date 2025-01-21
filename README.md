1. Crie um espaco no google chat particular.
2. Em configurações clique em app e integração
3. Clique m Webhooks e adicione um Webhooks
4. Copia a URL do Webhooks para substituir no código.
5. No Google Apps Script clique em serviço e adicione o google drive.
6. Ainda no Google Apps Script clique em Acionadores e configura para roda a cada 1 hora, veja configuração abaixo
  6.1 Escolha a função que será executada = checkForDeletedFiles
  6.2 Implantação a ser executada = Teste
  6.3 Selecione a origem do evento = Baseado no tempo
  6.4 Selecione o tipo de acionador com base no tempo = Contador de horas
  6.5 Selecione o intervalo de horas = A cada 1 hora
  6.6 Configurações de notificação de falha = Receber notificaçõea a cada hora.
