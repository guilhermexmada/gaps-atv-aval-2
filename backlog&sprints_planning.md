# SCRUM | GAPS ATV AVAL 2

## Aluno - Semestre

Guilherme Shimada Pereira - DSM3

# Backlog

## Requisitos funcionais

- Front-end
    - Homepage (Vitrine de produtos)
    - Categorias (Listas de produtos filtradas por tipo, preço, etc.)
    - Página do Produto (informações de vendedor, compra, entrega, etc.)
    - Telas de autenticação (Cadastro, Login, Recuperação de Senha, etc.)
    - Perfis de usuários (informações pessoais, métodos de pagamento, histórico de compras, etc.)
    - Página de Q&A (respostas para as perguntas mais frequentes dos clientes)
    - Página de Suporte e Contato (dados de contato e formulário de ajuda)
    - Págoma de Administrador para Produtos (cadastro, consulta, edição e exclusão de produtos e categorias)
    - Página de Administrador para Relatórios (vendas, acessos, movimentações)
    - Dashboard de Administrador (informações gerais e métricas das vendas no site)
- Back-end
    - Criação de API Rest para gerenciamento de requisições e respostas
    - Integração com API de transações financeiras e mecânica de carrinho
    - Conexão com banco de dados da empresa (estoques, clientes, compras, produtos, etc.)
    - Escrita de scripts/procedures para consulta de dados e manutenção do banco
    - Algoritmo de análise dos dados das vendas no site
    - Vitrine de produtos mais populares para Homepage
    - Listagem e filtro de produtos por tipo, preço, localização, etc.
    - CRUD de usuários, produtos, categorias, relatórios, etc.
    - Visualização, filtro e exportação de relatórios em PDF/CSV/TXT

## Requisitos não funcionais

- Desenvolver interfaces responsivas
- Desenvolver fluxo de navegação simples e intuitivo
- Garantir legibilidade e descanso visual das telas
- Implementar recursos de segurança avançada, como criptografia de ponta a ponta
- Preparar planos de contigência para perda de conectividade, apagões do servidor, tentativas de acesso não autorizado, ataques DDoS, etc.
- Emitir alertas visuais para ações importantes do usuário, como adicionar produto ao carrinho ou finalizar pagamento
- Configurações de acessibilidade 
- Backup automático do banco de dados

# Sprint Planning 1

| Requisito                              | T (Tem que ter) | D (Deve ter) | P (Pode ter) | Ñ (Não precisa agora) |
| -------------------------------------- | --------------- | ------------ | ------------ | --------------------- |
| Homepage / vitrine de produtos         | ✔               |              |              |                       |
| Categorias e filtros de produtos       | ✔               |              |              |                       |
| Página do produto                      | ✔               |              |              |                       |
| Cadastro e Login                       | ✔               |              |              |                       |
| Recuperação de senha                   |                 | ✔            |              |                       |
| Perfil do usuário                      |                 | ✔            |              |                       |
| Carrinho e integração financeira       | ✔               |              |              |                       |
| CRUD de produtos e categorias          | ✔               |              |              |                       |
| Dashboard administrativo               | ✔               |              |              |                       |
| Relatórios de vendas por categoria     | ✔               |              |              |                       |
| Exportação de relatórios (PDF/CSV/TXT) |                 | ✔            |              |                       |
| API REST                               | ✔               |              |              |                       |
| Conexão com banco de dados             | ✔               |              |              |                       |
| Scripts/procedures de manutenção       |                 | ✔            |              |                       |
| Algoritmo de análise de vendas         |                 | ✔            |              |                       |
| Produtos populares na homepage         |                 | ✔            |              |                       |
| Página de suporte e contato            |                 | ✔            |              |                       |
| Página de perguntas frequentes (Q&A)   |                 |              | ✔            |                       |
| Responsividade                         | ✔               |              |              |                       |
| Navegação intuitiva                    | ✔               |              |              |                       |
| Acessibilidade                         |                 | ✔            |              |                       |
| Alertas visuais ao usuário             |                 | ✔            |              |                       |
| Backup automático                      | ✔               |              |              |                       |
| Segurança avançada e criptografia      | ✔               |              |              |                       |
| Planos de contingência e proteção DDoS |                 |              | ✔            |                       |
| Histórico de compras                   |                 | ✔            |              |                       |
| Métodos de pagamento salvos            |                 |              | ✔            |                       |
| Localização avançada de produtos       |                 |              | ✔            |                       |
| Funcionalidades extras futuras         |                 |              |              | ✔                     |

# Sprint Planning 2

| Grupo Alvo       | Necessidades                         | Produto                                           | Metas do Negócio                               |
| ---------------- | ------------------------------------ | ------------------------------------------------- | ---------------------------------------------- |
| Dono da loja     | Organizar produtos por categorias    | Sistema de gerenciamento de produtos e categorias | Melhorar organização e controle do estoque     |
| Dono da loja     | Saber quais produtos vendem mais     | Dashboard e relatórios de vendas por categoria    | Apoiar decisões estratégicas de compra e venda |
| Clientes         | Encontrar produtos facilmente        | Homepage com filtros e categorias                 | Melhorar experiência do usuário                |
| Clientes         | Comprar produtos com segurança       | Sistema de autenticação e integração financeira   | Aumentar conversões e confiança                |
| Administradores  | Gerenciar produtos e relatórios      | Painel administrativo completo                    | Facilitar manutenção do sistema                |
| Empresa          | Garantir disponibilidade e segurança | Backup automático e mecanismos de proteção        | Reduzir falhas e perda de dados                |
| Usuários mobile  | Navegação em diferentes dispositivos | Interfaces responsivas                            | Expandir alcance da plataforma                 |
| Equipe de gestão | Acompanhar desempenho das vendas     | Relatórios exportáveis e métricas                 | Melhorar tomada de decisão baseada em dados    |

# Telas do Sistema (Figma)

<img width="1440" height="1024" alt="homepage" src="https://github.com/user-attachments/assets/0d666751-3760-48a4-a56c-d806ad2e17d8" />

<img width="1440" height="1024" alt="categoria" src="https://github.com/user-attachments/assets/10607865-1d96-4c14-989e-f64f9da404c2" />

<img width="1440" height="1024" alt="produto" src="https://github.com/user-attachments/assets/d9d0f9d6-7fb7-4ff6-8c7e-c0d207b00f6b" />

<img width="1440" height="1024" alt="Relatórios" src="https://github.com/user-attachments/assets/f868ce54-2bb3-42e7-8738-21dce56ce1a5" />

<img width="1440" height="1024" alt="Perfil de Usuário" src="https://github.com/user-attachments/assets/87608f06-d5b1-47c0-a241-46bd8b75b2fa" />

<img width="1440" height="1024" alt="Contato Suporte" src="https://github.com/user-attachments/assets/a173ad9a-26ca-466a-9af9-8f38d9fe7188" />





