# MNGR — Gestão de Clubes Desportivos

Aplicação web para gestão de clubes desportivos. Administradores, Gestores de Clube, Treinadores e Atletas podem gerir plantéis, marcar treinos, acompanhar competições, analisar estatísticas e comunicar através de um chat integrado.

Projeto desenvolvido no âmbito da unidade curricular de **Projeto em Aplicações Web (PAW)**.

## Tecnologias

- **Backend:** Node.js, Express, express-session
- **Base de dados:** PostgreSQL (`pg`)
- **Armazenamento de ficheiros:** Supabase
- **Outros:** bcrypt, multer, pdfkit
- **Testes:** Jest + Supertest

## Como correr

```bash
npm install
cp .env.example .env   # preencher com as credenciais da base de dados e do Supabase
npm start
```

A aplicação fica disponível em `http://localhost:3000`.

### Testes

```bash
npm test
```

## Perfis de utilizador

| Perfil | O que pode fazer |
| --- | --- |
| Administrador | Gerir utilizadores e clubes |
| Gestor de Clube | Gerir equipas, competições e membros |
| Treinador | Gerir treinos, calendário e estatísticas da equipa |
| Atleta | Consultar treinos, calendário e estatísticas pessoais |

## Equipa

Desenvolvido pelo grupo:

- Cristiano Saraiva
- Daniel Morais
- Filipe Candeias
- Gonçalo Fonseca
- Juan Gonsalves
