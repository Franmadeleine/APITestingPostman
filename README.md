Este projeto é uma coleção completa de testes de API desenvolvida com Postman, focada na validação de endpoints de uma aplicação fictícia. A estrutura inclui 45 requisições independentes, organizadas em cinco pastas: User, Articles, Profile, Tags e Comments.

Cada requisição foi criada para simular cenários reais, cobrindo fluxos positivos, negativos e casos de borda. Os testes foram implementados na aba Tests do Postman, com validações que incluem:

✅ Verificação do código de status

⏱ Tempo de resposta

📦 Estrutura e propriedades do corpo da resposta

⚠️ Mensagens de erro e validação

🔍 Destaques do projeto
Todas as requisições são independentes, sem dependência de execução anterior.

Scripts de pré-requisito foram utilizados no nível da coleção, simulando ações como cadastro, criação de artigo e postagem de comentário.

Limpeza automatizada: os artigos criados durante os testes são excluídos por funções escritas nos scripts de pré-requisito, evitando acúmulo de dados no banco.

Casos com falhas foram documentados com relatórios de bug no Jira, seguindo boas práticas de QA.

A coleção foi executada diversas vezes sem ambiente selecionado — todas as requisições passaram com sucesso.

📂 Estrutura da Coleção
Código
Postman Practice [Francesca Madeleine]
├── User
├── Articles
├── Profile
├── Tags
└── Comments

📌 Exemplos de Endpoints Testados
POST /users/login – Login com sucesso e cenários de erro

POST /users – Cadastro com diferentes entradas inválidas

GET /articles – Filtros por feed e tags

DELETE /articles/:slug – Validação de autorização e propriedade

POST /profiles/:username/follow – Funcionalidade de seguir/deixar de seguir

POST /articles/:slug/comments – Criação e exclusão de comentários com validação de permissões

🛠 Ferramentas e habilidades aplicadas
Postman (Coleções, Tests, Scripts de pré-requisito)

Princípios RESTful

Testes exploratórios e negativos

Jira (documentação e rastreamento de bugs)

JSON, métodos HTTP, códigos de status

Documentação de testes e design de casos de teste
