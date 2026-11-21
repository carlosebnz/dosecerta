# DoseCerta

Controle compartilhado de medicação familiar. Ajuda famílias que cuidam
de idosos ou crianças a registrar os horários dos remédios, sem esquecer
doses e sem que dois cuidadores deem a mesma medicação.

> Status: em construção.

## Aviso

O DoseCerta apenas registra o que foi dado. Ele não recomenda doses nem
substitui orientação médica. Os dados usados em demonstrações são fictícios.

## Problema

Quando mais de uma pessoa cuida do mesmo paciente, é comum duas delas
darem o mesmo remédio sem saber que a outra já deu.

## Regra central

Uma dose (pessoa, medicamento e horário previsto) só pode ser registrada
uma vez, mesmo que dois cuidadores tentem ao mesmo tempo.

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

- [ ] Domínio em Java puro, com testes (JUnit)
- [ ] Regra de dose duplicada, com teste de concorrência
- [ ] API REST com documentação (Swagger)
- [ ] Login e permissões por papel
- [ ] Interface em Angular
- [ ] Docker, CI e deploy
