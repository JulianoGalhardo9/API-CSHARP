# 🚀 API REST com C# e .NET — Do Zero ao Avançado com Entidades, Validações e Banco de Dados

---

## 🧭 Visão Geral

Este projeto representa uma jornada completa no **desenvolvimento de APIs REST com C# e .NET**, passando desde os conceitos fundamentais da linguagem até a construção de um back-end robusto, validado e conectado a um banco de dados real.

A aplicação evolui passo a passo:
- Explorando diferenças entre C#, .NET Framework, .NET Core e .NET moderno  
- Entendendo profundamente **programação orientada a objetos**  
- Criando e estruturando uma API profissional no Visual Studio  
- Implementando padrões como controllers, entidades, validações e tratamento de erros  
- Persistindo dados com **Entity Framework + SQLite**  
- Trabalhando com relacionamentos, filtros, rotas, responses padronizados e muito mais  

Este projeto é ideal para quem quer entender **como uma API .NET funciona por dentro**, construir uma base sólida e dominar práticas reais de mercado.

---

## ⚙️ Etapas do Desenvolvimento

### 🧩 1. Fundamentos de C# e do Ecossistema .NET
- Diferenças entre C#, .NET Framework, .NET Core e .NET moderno.  
- C# como linguagem orientada a objetos com tipagem forte, simplicidade e garbage collector.  
- Evolução da plataforma .NET e seus ambientes (Windows, Linux e macOS).  
- Dicas sobre versões, suporte e ciclo de vida da plataforma.

---

### 🧠 2. Programação Orientada a Objetos (POO)
- Entendimento do paradigma orientado a objetos.  
- Combinação de **atributos** (dados) e **métodos** (comportamentos).  
- Os quatro pilares da POO:
  - Herança  
  - Encapsulamento  
  - Abstração  
  - Polimorfismo  
- Exemplos práticos usando objetos como carros, clientes e produtos.

---

### 🛠️ 3. Preparação do Ambiente de Desenvolvimento
- Instalação do **Visual Studio Community**.  
- Diferenças entre **Visual Studio (IDE)** e **VS Code (editor)**.  
- Configuração inicial do ambiente para desenvolvimento de APIs com C#.  

---

### 🌐 4. Fundamentos de APIs e Comunicação HTTP
- O que é uma API e como ela se comunica com outros sistemas.  
- Métodos HTTP essenciais: **GET, POST, PUT, DELETE**.  
- Como o back-end responde e como o front-end consome informações.  
- Interoperabilidade e construção de APIs REST modernas.

---

### 🧱 5. Criação da Primeira API no Visual Studio
- Estruturação da solução com múltiplos projetos:  
  - Camada de comunicação  
  - Camada de exceções  
  - API principal  
- Primeiros controllers e endpoints.  
- Introdução ao **Entity Framework** para relacionar clientes e produtos.

---

### 🗂️ 6. Explorando a Estrutura do Projeto
- Pastas, arquivos e responsabilidades dentro da API.  
- Funcionamento da classe **Program.cs**.  
- Configuração de ambientes (Development, Production).  
- Organização via namespaces e boas práticas.

---

### 🔍 7. Testando a API com Swagger e Postman
- Como executar a API.  
- Uso do **Swagger** para documentar e testar endpoints.  
- Envio de dados, análise de respostas e interpretação do JSON.  
- Uso de breakpoints para depuração.

---

### 👥 8. Criando o Controller de Clientes
- Implementação de endpoints:
  - Registrar cliente  
  - Listar clientes  
  - Buscar por ID  
  - Atualizar  
  - Deletar  
- Parametrização de rotas e boas práticas para evitar conflitos.

---

### 📝 9. Criando Requests e Responses
- Criação de classes específicas para entradas e saídas.  
- Estrutura profissional para organizar dados transferidos pela API.  
- Implementação do método POST com retorno `201 Created`.

---

### ✔️ 10. Validação de Dados com FluentValidation
- Implementação de regras de negócio.  
- Uso de *use cases* para centralizar lógica.  
- Validação de campos como email, nome e formatos específicos.

---

### ⚠️ 11. Tratamento de Erros e Respostas Padronizadas
- Retorno de erros claros e JSON amigáveis.  
- Status code apropriados (ex.: 400 Bad Request).  
- Classe para formatar mensagens de erro.  
- Melhorando a experiência para o consumidor da API.

---

### 🔧 12. Exceções Personalizadas
- Criação de uma exceção base confiável.  
- Exceções específicas como **ErrorOnValidationException**.  
- Testes para garantir o funcionamento adequado.  

---

### 🛡️ 13. Filtro Global de Exceções
- Remoção de try-catch repetitivos nos controllers.  
- Centralização do tratamento de exceções.  
- Padronização de códigos de status para cada tipo de erro.  
- Melhor organização e legibilidade do projeto.

---

### 🗃️ 14. Fundamentos de Bancos de Dados
- Diferença entre bancos **relacionais** e **não-relacionais**.  
- Tabelas, tipos de dados e chaves primárias.  
- Introdução a entidades no .NET para representar tabelas.

---

### 🧰 15. Configurando o Entity Framework (ORM)
- Instalação de pacotes necessários.  
- Criação do **DbContext**.  
- Integração com **SQLite**.  
- Entendimento da tradução de objetos <-> SQL (ORM).

---

### 💾 16. Persistência de Clientes no Banco
- Instanciação do contexto.  
- Salvando clientes via `SaveChanges()`.  
- Organização de código com métodos menores.  
- Testes no Swagger.

---

### 📄 17. Retornando Todos os Clientes
- Endpoint GET estruturado.  
- Retorno JSON com lista de clientes.  
- Evitando envio de dados sensíveis (como senhas).  
- Boas práticas de performance.

---

### ✏️ 18. Editando Clientes (PUT)
- Alteração de dados usando ID como referência.  
- Validações aplicadas também na edição.  
- Tratamento de exceções personalizadas.  
- Lógica para lidar com campos opcionais.  
- Testes completos no Swagger.

---

### 📦 19. Criando Produtos e Ajustando Endpoints
- Correção do endpoint PUT anterior (inclusão do 400).  
- Novo endpoint para registrar produtos.  
- Validação de dados dos produtos.  
- Uso de herança para simplificar entidades.  
- Testes finais no Swagger.

---

### ❌ 20. Exclusão de Clientes e Produtos
- Implementação de deleção de produtos.  
- Tratamento para verificar existência antes de remover.  
- Exclusão de clientes com cuidado à integridade referencial.  
- Explicação do **on delete cascade** e seus impactos.

---

### 🔎 21. Recuperação de Clientes por ID
- Retorno de dados completos do cliente.  
- Relação com produtos usando Entity Framework.  
- Execução de joins e inclusão de entidades relacionadas.  
- Tratamento de exceções como "cliente não encontrado".

---

## 🧰 Tecnologias Utilizadas

- C#
- .NET 7+  
- Visual Studio Community  
- Entity Framework Core  
- SQLite  
- FluentValidation  
- Swagger / Swashbuckle  
- Postman  
- Arquitetura REST  

---

## 🧠 Conceitos Principais Dominados

- Estrutura de APIs REST em C#  
- POO aplicada à arquitetura de projetos  
- Validação eficiente com FluentValidation  
- Entity Framework e ORM na prática  
- Consultas, inserções, edições e exclusões com banco relacional  
- Tratamento de erros profissional  
- Controllers, rotas e responses padronizados  
- Uso de DTOs (requests/responses)  
- Integração com Swagger  

---

## 🏁 Conclusão

Este projeto proporciona uma experiência completa e prática no desenvolvimento de APIs com C#.  
Você aprende desde os fundamentos da linguagem e do .NET até práticas profissionais como:
- Camadas bem definidas  
- Validações  
- Mapeamentos  
- Entidades  
- Banco de dados  
- Exceções  
- Filtros globais  

Uma jornada essencial para qualquer desenvolvedor back-end que deseja construir aplicações escaláveis, modernas e robustas.

