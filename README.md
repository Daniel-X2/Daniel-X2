# Daniel da Silva Pereira

**Backend Developer** · João Pessoa, BR

Construo APIs com foco em segurança, performance e arquitetura limpa.  
Stack principal em `.NET` · `Python` · `C` — com testes de carga, CI/CD e deploy em produção.

---

## Stack

**Linguagens:** `C#` `Python` `C`  
**Frameworks:** `ASP.NET Core` `FastAPI` `SQLAlchemy` `ADO.NET`  
**Banco de dados:** `PostgreSQL` `SQLite`  
**Segurança:** `JWT` `RBAC` `BCrypt` `libsodium`  
**Infra & DevOps:** `Docker` `GitHub Actions` `Railway` `Render`  
**Testes:** `xUnit` `Moq` `Bogus` `Pytest` `Locust`  
**Observabilidade:** `Serilog`  
**Ferramentas:** `Linux` `Git` `CMake` `Valgrind`

---

## Projetos

---

### 🗄️ [Sistema-de-Gestao-com-DOTNET](https://github.com/Daniel-X2/Sistema-de-Gestao-com-DOTNET)

API REST assíncrona para gestão de clientes, funcionários e produtos, com PostgreSQL e arquitetura em camadas.

**Stack:** `ASP.NET Core` `PostgreSQL` `ADO.NET` `Npgsql` `JWT` `BCrypt` `Serilog` `xUnit` `Moq` `Bogus` `Docker` `GitHub Actions`

| Métrica | Valor |
|---|---|
| Requisições testadas (Locust, 50 usuários) | **8.300** |
| Throughput | **~23 req/s** |
| Mediana de latência | **3ms** |
| Tipos de exceção mapeados no middleware | **12** |

**Destaques:**
- Autenticação JWT + RBAC com controle de acesso por perfil (Admin/User)
- BCrypt para hash seguro de senhas
- Rate limiting para proteção contra abuso de endpoints
- Logging estruturado com Serilog
- Middleware centralizado de tratamento de exceções (12 tipos mapeados)
- Arquitetura modular: Controller → Service → Repository
- Paginação em todos os endpoints de listagem
- Testes unitários com Moq + Bogus — sem dependência de banco real
- CI/CD com GitHub Actions e deploy containerizado via Railway
- Validação de CPF com algoritmo próprio
- Atualização parcial — campos inválidos mantêm valor anterior

🌐 [API em produção](https://api-gestao-assincrona.up.railway.app/) · 🔗 [Repositório](https://github.com/Daniel-X2/Sistema-de-Gestao-com-DOTNET)

---

### 🎬 [PeacemakerAPI](https://github.com/Daniel-X2/PeacemakerAPI)

API REST com sistema de votação, ranking dinâmico e busca avançada, rodando em PostgreSQL.

**Stack:** `FastAPI` `PostgreSQL` `SQLAlchemy` `Pydantic` `Pytest` `Locust` `SlowAPI`

| Métrica | Valor |
|---|---|
| Requisições testadas (Locust) | **5.000+** |
| Falhas | **0** |
| Throughput | **14 req/s** |
| Latência média | **265ms** |

**Destaques:**
- Rate limiting com SlowAPI
- Sistema de votação e ranking dinâmico com filtros avançados
- Arquitetura em camadas com DTOs e validação via Pydantic
- CI com GitHub Actions usando PostgreSQL service container
- Testes automatizados com Pytest cobrindo a lógica de negócio
- Deploy no Render

🌐 [API em produção](https://api-pacificador.onrender.com/docs) · 🔗 [Repositório](https://github.com/Daniel-X2/PeacemakerAPI)

---

### 🔐 [Cofre-Criptografado-Gtk](https://github.com/Daniel-X2/Cofre-Criptografado-Gtk)

Gerenciador de notas desktop com criptografia forte e interface gráfica nativa — escrito em C puro.

**Stack:** `C` `libsodium` `GTK+ 3` `SQLite` `CMake` `Valgrind`

**Destaques:**
- Argon2 para derivação de chave + XChaCha20-Poly1305 para criptografia dos dados
- Interface nativa e leve com GTK+ 3
- Armazenamento local com SQLite
- Memory leaks validados e corrigidos com Valgrind
- Build gerenciado com CMake

🔗 [Repositório](https://github.com/Daniel-X2/Cofre-Criptografado-Gtk)

---

## Contato

Atualmente em busca da primeira oportunidade como desenvolvedor backend — aberto a vagas júnior e estágio.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat&logo=linkedin&logoColor=white)](https://linkedin.com/in/daniel-da-silva-32814636b)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white)](https://github.com/Daniel-X2)
[![Email](https://img.shields.io/badge/Email-D14836?style=flat&logo=gmail&logoColor=white)](mailto:danielsilva.dev1@gmail.com)
