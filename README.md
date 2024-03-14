# Projeto PhotoApp

Este repositório contém um conjunto de microservices relacionados ao aplicativo de fotos (PhotoApp). Cada microservice desempenha um papel específico na arquitetura geral do aplicativo.

## Microservices

- **PhotoAppAPIConfigServer**: Serviço responsável por centralizar a configuração dos demais microservices.
- **PhotoAppApiAccountManagement**: Gerencia contas de usuários no aplicativo.
- **PhotoAppApiAlbums**: Gerencia álbuns de fotos dos usuários.
- **PhotoAppApiUsers**: Gerencia informações e perfis de usuários.
- **PhotoAppApiZuulAPIGateway**: Serviço de gateway API para roteamento e segurança.
- **PhotoAppDiscoveryService**: Serviço de descoberta de instâncias de microservices.

## Como Utilizar

Para utilizar este projeto, siga estas etapas:

1. Clone ou faça o download deste repositório.
2. Importe cada microservice em sua IDE preferida.
3. Certifique-se de ter todas as dependências necessárias configuradas em seu ambiente de desenvolvimento.
4. Execute cada microservice individualmente ou utilize ferramentas de orquestração como Docker e Kubernetes para implantar e gerenciar os microservices.

## Contribuições

Contribuições para este projeto são bem-vindas! Se você tiver sugestões, melhorias ou correções a fazer, sinta-se à vontade para abrir uma issue ou enviar um pull request.
