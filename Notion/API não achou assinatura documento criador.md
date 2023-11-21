---
Date Created: 2023-04-17T14:12
Last Updated: 2023-04-17T14:12
Created By: Cristian Scopel
Last Edited By: Cristian Scopel
---
Esse documento foi criado pela API na verdade, então para assinar teria que ser enviado a mutation da assinatura do documento.

O Autentique não envia os documentos caso o signatário seja o criador do documento. A assinatura do criador pode ocorrer de duas formas:

01- quando ele cria o documento pelo painel, ele pode assinar diretamente pela plataforma, após o envio do documento;

02- quando o documento é criado pela API, onde a mutation deve conter a assinatura do criador diretamente (isso é feito na sua integração com o Autentique), isso pode ser conferido na nossa documentação:

Vc teria que contatar o pessoal responsável pela sua integração para conferir o que está acontecendo

O Autentique apenas recebe a mutation, nós não enviamos ela