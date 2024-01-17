...plano ativo no Iugu e não no painel adm...

Nós sabemos o que houve, mas ainda não temos certeza da causa. Foi um problema de comunicação entre o sistema de pagamentos e a nossa API. O sistema de pagamentos nos comunica do pagamento das faturas por callbacks, nós recebemos a notificação de pagamento da fatura, mas não a de criação da fatura, então do nosso lado chegou como se fosse paga uma fatura que não existia cadastrada do nosso lado, o que fez com que o nosso servidor não liberasse o plano

Disponha, desculpe pelo problema! Nós estamos criando uma forma de mitigar ele internamente caso ocorra novamente