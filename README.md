<h1 align="center">Eduardo Monteiro Moura</h1>

<h3 align="center">Backend Developer | C#/.NET</h3>

<p align="center">
Profissional de TI com mais de 7 anos de experiência em suporte corporativo, ERP, banco de dados e infraestrutura, em transição para Desenvolvimento Backend.
</p>

<p align="center">
Atualmente focado em <strong>C#/.NET</strong>, <strong>ASP.NET Core</strong>, <strong>APIs REST</strong>, <strong>Entity Framework Core</strong>, <strong>SQL Server</strong>, <strong>Azure</strong> e <strong>Docker</strong>.
</p>

<p align="center">
<a href="https://www.linkedin.com/in/eduardo-monteiro-moura">
<img src="https://img.shields.io/badge/LinkedIn-Eduardo%20Monteiro-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/>
</a>

<a href="mailto:eduardo.monteiro.moura1@gmail.com">
<img src="https://img.shields.io/badge/Email-Contato-1D3557?style=for-the-badge&logo=gmail&logoColor=white"/>
</a>
</p>

---

# 💻 Stack Principal

<p align="left">

<img src="https://img.shields.io/badge/C%23-68217A?style=for-the-badge&logo=csharp&logoColor=white"/>

<img src="https://img.shields.io/badge/.NET-512BD4?style=for-the-badge&logo=dotnet&logoColor=white"/>

<img src="https://img.shields.io/badge/ASP.NET_Core-5C2D91?style=for-the-badge&logo=dotnet&logoColor=white"/>

<img src="https://img.shields.io/badge/Entity_Framework_Core-68217A?style=for-the-badge"/>

<img src="https://img.shields.io/badge/REST_API-005571?style=for-the-badge"/>

<img src="https://img.shields.io/badge/SQL_Server-CC2927?style=for-the-badge&logo=microsoftsqlserver&logoColor=white"/>

<img src="https://img.shields.io/badge/Azure-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white"/>

<img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white"/>

<img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white"/>

</p>

---

# 🏗️ Projeto em destaque — Portal Corporativo IMPAKTO

Portal web corporativo **em produção**, construído do zero para substituir um sistema desktop (WinForms + SQLite) usado na portaria da empresa. Um login central dá acesso só aos departamentos autorizados para cada usuário, e o módulo **Portaria** foi migrado por inteiro para a web.

<p align="left">
<img src="https://img.shields.io/badge/Next.js_15-000000?style=flat-square&logo=nextdotjs&logoColor=white"/>
<img src="https://img.shields.io/badge/React_19-20232A?style=flat-square&logo=react&logoColor=61DAFB"/>
<img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white"/>
<img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white"/>
<img src="https://img.shields.io/badge/Supabase-3FCF8E?style=flat-square&logo=supabase&logoColor=white"/>
<img src="https://img.shields.io/badge/Tailwind_CSS_4-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white"/>
<img src="https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white"/>
</p>

**O que foi feito**

- 🔐 **Autorização em três camadas** — middleware de sessão, guardas no servidor em cada página e Server Action, e **Row Level Security** no PostgreSQL como barreira final. Permissões por departamento e por nível (administrador / operador).
- 🗄️ **Regras de negócio no banco** — entrada, saída, mercadorias e agendamento em **funções PL/pgSQL** atômicas, com trilha de auditoria *append-only* e a regra de "hoje" sempre no fuso da portaria.
- ⚡ **Otimização de desempenho** — reescrita das policies de RLS para serem avaliadas uma vez por consulta (InitPlan) em vez de uma vez por linha, eliminando consultas que estouravam o timeout.
- 🌐 **API REST para sistemas externos** (ERP, Power BI) — somente leitura, autenticada por chave guardada apenas como hash SHA-256, presa a um módulo e com **rate limit** de 120 req/min controlado no banco.
- 🔄 **Atualização em tempo real** da tela da portaria com Supabase Realtime (`postgres_changes`).
- 🚚 **Migração de dados do SQLite legado** — script transacional com modo de ensaio (rollback), normalização de placas e documentos, conferências automáticas e relatório de pendências.
- 📷 **Fotos de motoristas e mercadorias** em WebP (com fallback em WebAssembly), bucket privado e URLs assinadas de curta duração; histórico de fotos preservado.
- 🔗 **Integração com API externa** de cadastro de motoristas, com dados sensíveis filtrados no servidor conforme o perfil do usuário.
- 📊 Relatórios em **PDF e CSV**, agendamento de visitas entre setores, controle de mercadorias, recuperação de senha por e-mail e tema claro/escuro.
- ☁️ Deploy na **Vercel** e banco no **Supabase**, ambos na região de São Paulo; 20 migrations versionadas de banco.

> Repositório privado (sistema interno da empresa).

---

# 🚀 Sobre mim

- 💼 Analista de Suporte Sênior com experiência em ambientes corporativos e varejo.
- 👨‍💻 Desenvolvendo projetos em C#/.NET para fortalecer minha carreira como Desenvolvedor Backend.
- 🏭 Desenvolvi e coloquei em produção o portal corporativo da empresa, migrando um sistema desktop para a web.
- 🗄️ Experiência com SQL Server, PostgreSQL, consultas, modelagem de banco de dados, segurança por RLS e integrações.
- 🌐 Desenvolvimento de APIs REST utilizando ASP.NET Core.
- ☁️ Estudando Microsoft Azure e arquitetura de aplicações em nuvem.
- 📚 Aprendizado contínuo em boas práticas, Clean Code e SOLID.

---

# 📌 Tecnologias

### Backend

- C#
- .NET
- ASP.NET Core
- Entity Framework Core
- REST APIs

### Full Stack (Portal IMPAKTO)

- TypeScript
- Next.js / React
- Tailwind CSS

### Banco de Dados

- SQL Server
- PostgreSQL (PL/pgSQL, RLS)
- SQLite
- MySQL

### Cloud

- Microsoft Azure
- Docker
- Supabase
- Vercel

### Ferramentas

- Visual Studio
- VS Code
- Git
- GitHub
- Postman

---

# 📈 Atualmente estudando

- Arquitetura de Software
- Clean Architecture
- Microsserviços
- Docker
- Azure
- Testes Unitários
- Design Patterns

---

# 🎯 Objetivo

Busco uma oportunidade como **Desenvolvedor Backend C#/.NET Júnior**, onde possa aplicar minha experiência em tecnologia, desenvolver soluções escaláveis e evoluir continuamente como engenheiro de software.
