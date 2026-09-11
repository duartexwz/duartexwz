👋 Olá, eu sou Mayckon Duarte
🚀 Sobre mim
Sou estudante de Engenharia de Software e desenvolvedor Full-Stack em formação, com foco em backend (Python) sem perder o frontend de vista. Aprendo construindo: já coloquei um e-commerce real em produção e participei do backend de um sistema institucional de agendamento.

📌 Projetos em Destaque
🛍️ JP CROCO — Loja Online (produção)
E-commerce completo no ar: vitrine, sacola por usuário, checkout e painel admin.

Frontend: React + Vite (SPA, responsiva, code-split)
Backend: FastAPI + PostgreSQL (Neon), deploy serverless na Vercel
Pagamento: Mercado Pago — Pix com confirmação automática (polling + webhook), Brick, baixa de estoque
Frete real: SuperFrete/Melhor Envio (cotação por CEP, etiquetas, rastreio)
Extras: JWT com refresh silencioso, upload no Vercel Blob, push no aparelho do admin, variantes cor × tamanho
📅 Sistema de Reservas Institucionais — COFFITO (backend)
Participei do backend do sistema de solicitação, análise e acompanhamento de reservas de espaços institucionais.

API: FastAPI + PostgreSQL, autenticação por cookie HttpOnly (access + refresh token) com CSRF
Domínio: reservas, espaços, recursos, status, histórico e auditoria, notificações por e-mail
Fluxos público (solicitação sem login) e interno (painel, agenda, administração por perfil)
Ambiente de homologação com Docker Compose (API + frontend + Postgres + Mailpit)
🔗 Repositório: https://github.com/duartexwz/JpCroco



💅 Ana Clara Nails — Sistema de Agendamento (full-stack)
Sistema completo de agendamento para nail designer: catálogo de modelos, reserva de horários com sinal de 50%, painel administrativo e controle de clientes.


Frontend: React + TanStack Start (SSR, responsivo), Tailwind + shadcn
Backend: FastAPI + PostgreSQL (asyncpg), JWT em cookie HttpOnly com CSRF
Pagamento: Mercado Pago Checkout Bricks (Pix com QR Code + cartão), webhook com validação HMAC, conciliação automática do status do agendamento
Qualidade: ~175 testes pytest, ruff, integração front↔back com fallback mockado
🔗 Repositório: https://github.com/duartexwz/nail-appointment


📂 DATASYSTEM — Gestão de Funcionários
Sistema de gerenciamento de dados (CRUD) em Python, focado em segurança e organização.

CRUD completo de funcionários com persistência em JSON
Autenticação com criptografia PBKDF2_SHA256
Arquitetura modular (core, src, utils) e tratamento de exceções
🔗 Repositório: https://github.com/duartexwz/Estudando-CRUD-JSON
🛠️ Tecnologias
Linguagens: Python, JavaScript
Backend: FastAPI, JWT, WebSockets, SMTP
Frontend: React, Vite, Axios, FullCalendar, Bootstrap
Banco de dados: PostgreSQL, SQLite, JSON
Infra: Docker, Vercel, Neon, Git & GitHub
Integrações: Mercado Pago, SuperFrete/Melhor Envio, Correios, ViaCEP, Web Push
📈 O que estou evoluindo
Testes automatizados (pytest) e CI
Conciliação de pagamentos e jobs em background
Arquitetura de APIs maiores (versionamento, paginação, cache)
Boas práticas de segurança em produção (secrets, LGPD, rate limiting)
🤝 Contato
GitHub: https://github.com/duartexwz
⭐ Se gostou de algum projeto, fique à vontade para deixar uma star!
