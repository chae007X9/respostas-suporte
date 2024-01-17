Isso mesmo, o link dos documentos pode ser acessado por qualquer pessoa sem autenticação. Não é possível alterar esse comportamento

  

Esse é um comportamento intencional, o Autentique foi desenvolvido para funcionar dessa forma

  

Todos os documentos precisam ter uma forma de serem auditados por terceiros, para o caso de auditoria judicial e perícia. Dessa forma eles precisam ter um link público de validação que permita esse acesso e auditoria ou outra forma de fazer o mesmo. Esse é o modelo de auditoria que optamos implementar no Autentique, entendemos que pode não ser o ideal para todos os usuários e nesses casos recomendamos buscar uma solução que se adeque melhor ao seu modelo de negócio

  

Os documentos não são públicos nem indexáveis. Apenas as partes do documento possuem o link para acessar ele

  

O ID dos documentos é gerado com uma cifra de 256bits, a chance de colisão testando um ID aleatório é de 4.3*10-60. Embora seja tecnicamente possível que você consiga achar algum documento aleatório preenchendo um número aleatório, há mais possibilidades que estrelas no universo. Além disso a API do Autentique limita a quantidade de documentos que você pode tentar acessar, dessa forma seria inviável realizar algum teste automatizado

  

É estatisticamente mais provável que você ganhe na mega sena do que alguém acesse algum dos seus documentos tentando um ID aleatório =]

  

Os funcionários do Autentique apenas conseguem acessar os documentos tendo o ID do documento. Se você nos chamar no suporte para auxilio em algum documento. O nosso funcionário irá solicitar o ID dele para que possamos conferir o documento caso se trate de algum problema nele