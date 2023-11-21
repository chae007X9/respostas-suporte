---
Date Created: 2023-09-15T13:37
Last Updated: 2023-09-15T13:40
Created By: Felipe Tomkiel Malacarne
Last Edited By: Felipe Tomkiel Malacarne
---
Lamentamos informar que não é viável configurar um bearer token ou secret para os webhooks em nosso sistema.

Nossa recomendação é que você utilize uma URL de callback que inclua um caminho longo e caracteres aleatórios, como o exemplo a seguir:

[https://eitaa.free.beeceptor.com/84e1683173ed5574de29c06c77ad1d2afa6297926ceec123b](https://eitaa.free.beeceptor.com/84e1683173ed5574de29c06c77ad1d2afa6297926ceec123b)

Dessa forma, você poderá obter um nível de segurança prático semelhante ao de um bearer token fixo comum.