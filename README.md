## API de Vendas com Node.js e TypeScript

### Descrição

Este projeto consiste em uma API RESTful completa para gerenciar produtos, clientes, pedidos e usuários de um sistema de vendas. Utiliza Node.js com TypeScript e segue os princípios de Domain Driven Design (DDD) e Princípios SOLID para garantir um código flexível, escalável e de fácil manutenção.

### Funcionalidades Principais

-   Gerenciamento de produtos, clientes, pedidos e usuários.
-   Processamento de pedidos com controle de estoque.
-   Autenticação JWT, recuperação de senha, atualização de perfil e avatar de usuários.
-   Upload de arquivos para armazenamento de avatares utilizando Amazon S3.
-   Envio de emails transacionais usando Amazon SES.
-   Cache de dados utilizando Redis para otimização de performance.

### Tecnologias Utilizadas

-   **Node.js**: Ambiente de execução JavaScript para backend.
-   **Express.js**: Framework web minimalista e flexível para Node.js.
-   **TypeScript**: Superset do JavaScript que adiciona tipagem estática e recursos avançados.
-   **TypeORM**: ORM para TypeScript que simplifica a interação com bancos de dados.
-   **PostgreSQL (via Docker)**: Banco de dados relacional robusto e escalável.
-   **Redis (via Docker)**: Armazenamento de dados em memória para cache e otimização de performance.
-   **Amazon S3**: Serviço de armazenamento de objetos escalável para armazenar arquivos de forma segura.
-   **Amazon SES**: Serviço de envio de emails transacionais para comunicação com usuários.
-   **Jest**: Framework de testes automatizados para assegurar a qualidade da aplicação.
-   **CORS**: Configuração para permitir o acesso à API de diferentes origens.
-   **Middlewares**: Funções intermediárias para execução de tarefas antes ou depois das requisições.
-   **Migrations**: Controle de versão do banco de dados para facilitar atualizações.
-   **Deploy em produção na Digital Ocean**: Implantação da API em um ambiente escalável e confiável.

### Arquitetura e Design

-   **Design Patterns**: Utilização de padrões de projeto para soluções elegantes e reutilizáveis.
-   **Domain Driven Design (DDD)**: Modelagem do domínio da aplicação de forma eficiente.
-   **Tratamento de Erros**: Estratégias para lidar com erros de forma eficiente e feedback adequado aos usuários.
-   **Sistema de Roteamento**: Organização clara e intuitiva das rotas da API.
-   **Relacionamento Many-to-Many**: Implementação de relacionamentos complexos entre entidades.

### Segurança e Performance

-   **Proteção contra ataques DDoS**: Medidas para proteger a API contra ataques de negação de serviço.
-   **Cache com Redis**: Otimização de performance através de armazenamento em cache.
-   **Envio de email em diferentes ambientes**: Configuração para envio de emails em ambientes de desenvolvimento e produção.

### Testes

-   **Testes Automatizados**: Utilização do Jest para assegurar a qualidade e o correto funcionamento da aplicação.

### Repositório e Deploy

-   **Deploy**: Implantação da API em ambiente de produção na Digital Ocean.

### Como Usar

1. Clone o repositório e instale as dependências.
2. Configure as variáveis de ambiente necessárias (ex.: credenciais AWS, configurações de banco de dados).
3. Execute as migrations para criar a estrutura inicial do banco de dados.
4. Inicie a API utilizando `npm start`.
5. Acesse a documentação da API para detalhes sobre os endpoints disponíveis e como utilizá-los.

### Documentação da API

Para informações detalhadas sobre os endpoints e como utilizá-los, consulte a documentação da API disponível no endpoint `/docs`.

Este projeto visa fornecer uma solução robusta e escalável para gerenciamento de vendas, utilizando tecnologias modernas e boas práticas de desenvolvimento.
