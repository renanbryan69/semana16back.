# semana16back.

 1. Explique com suas palavras por que o CORS é importante em uma API.

O CORS é importante porque permite controlar quais origens podem acessar uma API, ajudando a evitar acessos não autorizados.

2. Liste os três cabeçalhos de CORS estudados e diga a função de cada um.

Access-Control-Allow-Origin:** define as origens permitidas.
Access-Control-Allow-Methods:** define os métodos HTTP permitidos, como GET, POST e DELETE.
Access-Control-Allow-Headers:** define quais cabeçalhos podem ser usados nas requisições.

 3. Explique como uma API pode permitir uma aplicação parceira e impedir uma origem não autorizada.

A API pode permitir o endereço da aplicação parceira no **Access-Control-Allow-Origin**. Assim, a aplicação autorizada pode acessar a API, enquanto uma origem não autorizada terá o acesso bloqueado pelo navegador.

 4. Explique um problema que pode acontecer se o CORS for configurado de forma incorreta.

Pode permitir acessos que deveriam ser bloqueados ou impedir aplicações autorizadas de acessarem a API.

 5. Explique a ideia do OAuth 2.0 no cenário bancário e cite os fluxos apresentados no material.

O **OAuth 2.0** permite controlar e delegar o acesso aos recursos sem precisar compartilhar diretamente a senha do usuário. Os fluxos apresentados são **Authorization Code, Implicit, Password Credentials e Client Credentials**.

 6. Explique o que é armazenado no payload de um JWT e qual a função da signature.

O **payload** armazena informações do token, como dados do usuário, permissões e validade. A **signature** serve para verificar se o token é verdadeiro e se não foi alterado.

7. Descreva um fluxo simples para proteger uma operação financeira usando JWT.

O usuário faz login e recebe um JWT. Depois, envia o token ao solicitar uma operação financeira. A API verifica a validade e a assinatura do token e confere se o usuário tem permissão. Se estiver tudo certo, a operação é liberada.

 8. Cite medidas adicionais de segurança indicadas no material, como HTTPS e políticas de CORS.

Usar **HTTPS**, configurar corretamente o **CORS**, controlar as permissões dos usuários e usar tokens com tempo de validade adequado.

 9. Qual é a principal função de uma ferramenta de monitoramento?

A principal função é acompanhar o desempenho, a disponibilidade e a segurança da aplicação em tempo real, ajudando a identificar problemas.

 10. Qual ferramenta apresentada no material é indicada para análise de logs em tempo real?

A ferramenta indicada é a **ELK Stack**.

 11. Qual a diferença entre log de acesso e log de erro?

O **log de acesso** registra as solicitações recebidas, como IP e endpoint. O **log de erro** registra as falhas que aconteceram durante o processamento.

 12. Como os logs podem ajudar a identificar tentativas de ataque?

Os logs podem mostrar comportamentos suspeitos, como muitas tentativas de acesso, várias requisições de um mesmo IP ou tentativas de acessar áreas protegidas.

 13. Em um período de Black Friday, qual seria a primeira informação que você procuraria no monitoramento e por quê?

Eu procuraria primeiro as **métricas de CPU, memória, tráfego e quantidade de acessos**, porque durante a Black Friday o número de usuários pode aumentar muito e causar lentidão ou sobrecarga.

 14. O que forma uma origem no CORS?

Uma origem é formada por **protocolo, domínio e porta**.

15. Qual cabeçalho define as origens permitidas?

O cabeçalho **Access-Control-Allow-Origin** define as origens permitidas.

16. Qual é a diferença entre autenticação e autorização?

**Autenticação** verifica quem é o usuário. **Autorização** define o que esse usuário pode acessar ou fazer.

 17. Quais são as três partes de um JWT?

As três partes são **Header, Payload e Signature**.

18. Qual é a diferença entre monitoramento e análise de logs?

**Monitoramento** acompanha o sistema enquanto ele está funcionando. Já a **análise de logs** consulta os registros de acessos, erros e outros acontecimentos do sistema.
