<div align="center">

Automação e Extração de Informações em Atendimento Inteligente

## FATEC Prof Jessen Vidal, São José dos Campos - 5º Semestre DSM 2024

[Sobre :memo:](#sobre) | [Tecnologias :computer:](#tecnologias) | [Equipe :busts_in_silhouette:](#equipe) | [Entregas :rocket:](#entregas) | [Backlog :clipboard:](#backlog)

</div>

---

<div align="center">

## :information_source: Sobre

</div>

Esse projeto foi desenvolvido pelos alunos do sexto semestre de 2025 do curso de Desenvolvimento de Software Multiplataforma da FATEC São José dos Campos - Professor Jessen Vidal.

Ele tem como objetivo desenvolver uma solução que permita a extração automática dos principais pontos de conversas, classificação das interações e geração de insights diários sobre os atendimentos, melhorando a eficiência e facilitando a tomada de decisão.

---

<div align="center">

## :computer: Tecnologias

</div>

  
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=next.js&logoColor=white)![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=white)![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)![shadcn](https://img.shields.io/badge/shadcn-000000?style=for-the-badge&logo=shadcn&logoColor=white)![Docker](https://img.shields.io/badge/Docker%20-%20%232496ED?style=for-the-badge&logo=docker&logoColor=white)![Python](https://img.shields.io/badge/Python%20-%20%233776AB?style=for-the-badge&logo=python&logoColor=white)![PostgreSQL](https://img.shields.io/badge/PostgreSQL%20-%20%234169E1?style=for-the-badge&logo=postgresql&logoColor=white)
  

---

<div align="center">

## :busts_in_silhouette: Equipe

</div>

| :camera: Foto                         | :bust_in_silhouette: Nome           | :briefcase: Função | :octocat: Github                              | :link: LinkIdn                                                         |
| ------------------------------------- | ----------------------------------- | ------------------ | --------------------------------------------- | ---------------------------------------------------------------------- |
| ![Foto](docs/images/fotoMurilo.png)   | Murilo Henrique Sangi da Silva Lima | Product Owner      | [Github](https://github.com/MuriloLima03)     | [LinkedIn](https://www.linkedin.com/in/murilo-sangi-944964313/)        |
| ![Foto](docs/images/fotoMatheus.png)  | Matheus Fernando Vieira de Melo     | Scrum Master       | [Github](https://github.com/Matheusfvm)       | [LinkedIn](https://www.linkedin.com/in/matheusfvmelo/)                 |
| ![Foto](docs/images/fotoPedro.png)    | Pedro Henrique Silva Almeida        | Dev Team           | [Github](https://github.com/PedroHSdeAlmeida) | [LinkedIn](https://www.linkedin.com/in/pedroalmeidadev/)               |
| ![Foto](docs/images/fotoVinicius.png) | Vinicius de Oliveira Laranjeiro     | Dev Team           | [Github](https://github.com/vdlaranjeiro)     | [LinkedIn](https://www.linkedin.com/in/vinicius-laranjeiro-296b371bb/) |

---

<div align="center">

## :rocket: Entregas

</div>
  
O projeto seguiu a metodologia ágil e foi dividido em 3 sprints, cada uma com um período de 20 dias


### Timeline das entregas

<div align="center">

![Timeline das entregas](/docs/images/Timeline.png)

</div>

### Pipeline PLN

<div align="center">

![Pipeline PLN](./docs/images/pipeline-pln.png)

</div>

### Sprint 1

<details>
  <summary>Detalhes da Sprint 1</summary>

  <br>

**Objetivo da Sprint:**  
Nessa sprint, nosso foco foi na documentação do sistema, configuração da pipeline de PLN e construção dos dashboards para demonstrar os resultados da análise dos atendimentos.

**Sprint Backlog:**

| USID | Requisito    |
| ---- | ------------ |
| US01 | Dashboards   |
| US02 | Pipeline PLN |

**Burndown:**  
![Burndown Sprint 1](./docs/sprint1/burndownSprint1.png)

</details>

---

<div align="center">

## :clipboard: Backlog

</div>

| USID | Sprint | Requisito                               |
| ---- | ------ | --------------------------------------- |
| US01 | 01     | Dashboards                              |
| US02 | 02     | Extração de informações dos datasets    |
| US03 | 02     | Pré-processamento dos dados             |
| US04 | 02     | Anonimização de dados sensíveis         |
| US05 | 02     | Classificação dos atendimentos          |
| US06 | 02     | CRUD de usuários                        |
| US07 | 03     | Sumarização automática dos atendimentos |
| US08 | 03     | Busca Semântica                         |
| US09 | 03     | Conformidade com a LGPD                 |
| US10 | 03     | Deploy                                  |


<div align="center">

## :scroll: User Stories

</div>

| USID | Descrição                                                                                                                                                                              |
| ---- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| US01 | Como usuário, quero que o sistema gere dashboards com informações das classificações e sumarização dos atendimentos para obter insights rápidos sobre o estado atual dos atendimentos. |
| US02 | Como usuário, quero que o sistema extraia informações relevantes do dataset de atendimento para serem analisadas pelos modelos de classificação e sumarização.                         |
| US03 | Como usuário, quero que o sistema aplique técnicas de pré-processamento nos dados extraídos para aumentar a eficácia dos modelos de classificação e sumarização.                       |
| US04 | Como usuário, quero que o sistema anonimize dados dos funcionários para proteger suas informações.                                                                                     |
| US05 | Como usuário, quero que o sistema classifique o tipo e sentimento dos atendimentos para extrair informações precisas.                                                                  |
| US06 | Como administrador, quero cadastrar e gerenciar usuários para garantir o acesso ao sistema.                                                                                            |
| US07 | Como usuário, quero que o sistema gere um resumo automático das conversas para entender os principais pontos abordados.                                                                |
| US08 | Como usuário, quero buscar informações específicas nas interações passadas para obter dados rapidamente.                                                                               |
| US09 | Como usuário, quero que o sistema se adeque à LGPD para garantir a segurança dos dados.                                                                                                |
| US10 | Como usuário, quero que o sistema esteja hospedado em uma solução de nuvem para evitar indisponibilidade.                                                                              |

