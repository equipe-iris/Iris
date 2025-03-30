<div align="center">

# Automação e Extração de Informações em Atendimento Inteligente

## FATEC Prof Jessen Vidal, São José dos Campos - 5º Semestre DSM 2024

[Sobre](#sobre) | [Tecnologias](#tecnologias) | [Equipe](#equipe) | [Entregas](#entregas) | [Backlog](#backlog)

## Sobre

</div>

Esse projeto foi desenvolvidos pelos alunos do sexto semestre de 2025 do curso de Desenvolvimento de Software Multiplataforma da FATEC São José dos Campos - Professor Jessen Vidal.

Ele tem como objetivo desenvolver uma solução que permita a extração automática dos principais pontos de conversas, classificação das interações e geração de insights diários sobre os atendimentos, para melhorar a eficiência do atendimento, reduzir a sobrecarga manual na análise e facilitar a tomada de decisão com base nos dados extraídos.

---

<div align = "center">

## Tecnologias

</div>

![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=next.js&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
![shadcn](https://img.shields.io/badge/shadcn-000000?style=for-the-badge&logo=shadcn&logoColor=white)
![Docker](https://img.shields.io/badge/Docker%20-%20%232496ED?style=for-the-badge&logo=docker&logoColor=white)
![Python](https://img.shields.io/badge/Python%20-%20%233776AB?style=for-the-badge&logo=python&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL%20-%20%234169E1?style=for-the-badge&logo=postgresql&logoColor=white)

---

<div align = "center">

## Equipe

</div>


| Foto | Nome | Função | Github | LinkIdn |
| ---- | ---- | ------ | ------ | ------- |
| ![Foto](docs\images\fotoMurilo.png) | Murilo Henrique Sangi da Silva Lima | Product Owner | [Github](https://github.com/MuriloLima03) | [LinkedIn](https://www.linkedin.com/in/murilo-sangi-944964313/) |
| ![Foto](docs\images\fotoMatheus.png) | Matheus Fernando Vieira de Melo | Scrum Master | [Github](https://github.com/Matheusfvm) | [LinkedIn](https://www.linkedin.com/in/matheusfvmelo/) |
| ![Foto](docs\images\fotoPedro.png) | Pedro Henrique Silva Almeida | Dev Team | [Github](https://github.com/PedroHSdeAlmeida) | [LinkedIn](https://www.linkedin.com/in/pedroalmeidadev/) |
| ![Foto](docs\images\fotoVinicius.png) | Vinicius de Oliveira Laranjeiro| Dev Team | [Github](https://github.com/vdlaranjeiro) | [LinkedIn](https://www.linkedin.com/in/vinicius-laranjeiro-296b371bb/) |

---

## Entregas

O projeto seguiu a metodológia ágil e foi divido em 3 sprits, cada sprint tinha o período de 20 dias.

### Timeline das entregas

![Timeline das entregas](/docs/images/Timeline.png)

### Arquitetura

![Arquitetura do projeto](url-da-imagem-arquitetura)

### Pipeline PLN

![Pipeline PLN](url-da-imagem-pipeline)

### Sprint 1

Nessa sprint nosso focamos em no documentação do sistema, e da pipeline de PNL e da construção dos dashboards usados para demostrar os resultados da análise dos atendimentos.

**Sprint Backlog:**
| USID | Requisito |
| -----| --------- |
| US01 | Dashboards |
| ---- | Pipeline PLN |

**Burndown:**
![Burndown Sprint 1](./docs/sprint1/Burndown.png)

--------


## Backlog

| USID | Sprint | Requisito |
| -----| ------ | --------- |
| US01 | 01 | Dashboards |
| US02 | 02 | Extração de informações dos datasets |
| US03 | 02 | Pré-processamentos dos dados |
| US04 | 02 | Anonimização de dados sensíveis |
| US05 | 02 | Classificação dos atendimentos |
| US06 | 02 | CRUD de usuários |
| US07 | 03 | Sumarização automática dos atendimentos |
| US08 | 03 | Busca Semântica |
| US09 | 03 | Conformidade com a LGPD |
| US10 | 03 | Deploy |
---

## User Stories

| USID | Descrição |
| ---- | --------- |
| US01 | Como usuários quero que o sistema gere dashboards com as informações das classificações e sumarização dos atendimentos para conseguir ter insights rápidos quanto ao estado atual dos atendimentos |
| US02 | Como usuário quero que o sistema extraia informações relevantes do datasets de atendimento para serem analisadas pelos modelos de classificação e sumarização dos atendimentos |
| US03 | Como usuário quero que o sistema aplique técnicas de pré-processamento nos dados após a extração para aumentar a eficácia dos modelos de classificação e sumarização dos atendimentos  |
| US04 | Como usuário quero que o sistema anonimize dados relacionados aos funcionários (Nome, Documentos etc) contidos na base de dados para proteger os dados dos funcionários |
| US05 | Como usuário quero que o sistema consiga classificar o tipo e sentimento dos atendimentos para que consiga extrair informações rápidas e precisas do estado atual dos meus atendimentos |
| US06 | Como administrador quero poder cadastrar novos usuários ao sistema e gerenciar estes usuários para garantir o acesso de outros usuários ao sistema |
| US07 | Como usuário quero que o sistema gere um resumo automático das conversas para conseguir entender os principais pontos abordados naquele atendimento |
| US08 | Como usuário quero buscar informações específicas nas interações passadas, considerando o contexto das conversas para obter informações rápidas sobre um dado atendimento |
| US09 | Como usuário quero que o sistema se adequar a Lei Geral de Proteção de Dados para garantir a integridade e segurança dos dados de cada usuário |
| US10 | Como usuário quero que o sistema esteja hospedado em alguma solução de nuvem para não haver momentos de indisponibilidade do mesmo |