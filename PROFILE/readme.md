# Iniciação científica - TRF6 + Dom Helder

Bem-vindo à organização do projeto de uma aplicação mobile para o TRF6 MG, voltada para a denúncia de casos de assédio. Este projeto é realizado como parte de uma iniciativa acadêmica de pesquisa e desenvolvimento, com o objetivo de fornecer uma ferramenta segura e eficiente para a coleta e gerenciamento de denúncias de assédio dentro do próprio TRF6.

<div style="display: inline-block" align="center">
    <img align="center" style="width: 35%; heigth: 25%;" src="/PROFILE/LogoDomHelderDark.png">
    <img align="center" style="width: 20%; heigth: 25%;" src="/PROFILE/Marca-TRF6-branca.png">
</div>

## Visão Geral

A aplicação tem como objetivo criar um canal seguro e acessível para que pessoas possam reportar casos de assédio diretamente pelo aplicativo. O sistema é desenvolvido com o foco em:

- **Segurança e Privacidade:** Proteger os dados dos denunciantes e assegurar que apenas usuários autorizados possam acessar informações sensíveis.
- **Acessibilidade:** Facilitar o uso para todas as pessoas que queiram realizar uma denúncia.
- **Gestão Administrativa:** Prover ferramentas para que profissionais autorizados visualizem e tomem as medidas apropriadas, além de gerarem estatísticas para análise.

## Estrutura do projeto

Esta organização serve como ponto de documentação e coordenação. Ela será utilizada para gerenciar as diretrizes gerais, acompanhamento do progresso edefinições padrões de desenvolvimento. A aplicação será dividida em diferentes serviços para suportar uma arquitetura modular e escalável:

- **notification-service:** Serviço responsável por gerenciar notificações para os usuários, como confirmações de denúncia, atualizações e alertas.
- **report-service:** Gerencia o envio de denúncias pelos usuários. Inclui o processamento e armazenamento seguro dos dados.
- **auth-service:** Serviço de autenticação e autorização, responsável por gerenciar o login e o controle de acesso dos usuários.
- **analytics-service:** Processa os dados das denúncias para gerar estatísticas e análises, mantendo o anonimato dos usuários.
- **gateway-api:** API Gateway que serve como ponto de entrada para todos os serviços, gerenciando o roteamento de requisições entre os microsserviços.
- **mobileapp-frontend:** Interface mobile do aplicativo, acessada pelos usuários para enviar denúncias e pelos administradores para monitoramento.

## Licença

Este projeto é desenvolvido exclusivamente para fins acadêmicos e é de uso restrito.
