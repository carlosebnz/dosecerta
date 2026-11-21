# Agendamento

Sistema de agendamento full-stack que impede dois atendimentos
no mesmo horário para o mesmo profissional.

## Problema

Agendamentos feitos por vários usuários podem se sobrepor. Este
projeto resolve isso com uma regra de domínio testada e, depois,
com garantias no banco de dados.

## Estrutura

- backend/: API REST em Java 21 e Spring Boot
- frontend/: interface em Angular

## Stack planejada

- Java 21 e Spring Boot
- PostgreSQL com migrations (Flyway)
- Angular
- Docker e GitHub Actions

## Como rodar

Em breve.

## Roadmap

- [ ] Modelagem do domínio
- [ ] Regra de conflito de horários com testes
- [ ] API REST com documentação (Swagger)
- [ ] Autenticação com JWT
- [ ] Front-end em Angular
- [ ] Docker, CI e deploy
