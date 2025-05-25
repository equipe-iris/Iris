<div align="center">

Automação e Extração de Informações em Atendimento Inteligente

## FATEC Prof Jessen Vidal, São José dos Campos - 5º Semestre DSM 2024

[Sobre :memo:](#sobre) | [Tecnologias :computer:](#tecnologias) | [Equipe :busts_in_silhouette:](#equipe) | [Entregas :rocket:](#entregas) | [Backlog :clipboard:](#backlog)

</div>

---

<div align="center">

<span id="sobre"></span>

## :information_source: Sobre

</div>

Esse projeto foi desenvolvido pelos alunos do sexto semestre de 2025 do curso de Desenvolvimento de Software Multiplataforma da FATEC São José dos Campos - Professor Jessen Vidal.

Este projeto tem como objetivo desenvolver uma solução para analisar automaticamente grandes volumes de interações textuais geradas em sistemas automatizados de atendimento ao cliente, neste caso, CRM (Jira). A nossa solução visa extrair automaticamente os principais pontos discutidos nas conversas, classificar essas interações por sentimento e categoria, sumarizá-las e gerar insights diários que apoiem decisões estratégicas.

Dessa forma, o projeto busca melhorar a eficiência geral dos processos de atendimento, diminuir o esforço manual atualmente necessário na análise de dados, e facilitar a tomada de decisão com base em informações sintetizadas e relevantes obtidas das interações dos clientes.

---

<div align="center">

<span id="tecnologias"></span>

## :computer: Tecnologias

</div>

  
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=next.js&logoColor=white)![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=white)![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)![shadcn](https://img.shields.io/badge/shadcn-000000?style=for-the-badge&logo=shadcn&logoColor=white)![Docker](https://img.shields.io/badge/Docker%20-%20%232496ED?style=for-the-badge&logo=docker&logoColor=white)![Python](https://img.shields.io/badge/Python%20-%20%233776AB?style=for-the-badge&logo=python&logoColor=white)![PostgreSQL](https://img.shields.io/badge/PostgreSQL%20-%20%234169E1?style=for-the-badge&logo=postgresql&logoColor=white)
  

---

<div align="center">

<span id="equipe"></span>

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

<span id="entregas"></span>


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


### Sprint 2

<details>
  <summary>Detalhes da Sprint 2</summary>

  <br>

**Objetivo da Sprint:**  
Nessa sprint, dividimos nosso foco em duas frentes Classificação dos atendimentos e Gerenciamento dos usuários.

**Sprint Backlog:**

| USID | Requisito    |
| ---- | ------------ |
| US02 | Extração de informações dos datasets |
| US03 | Pré-processamento dos dados |
| US04 | Classificação dos atendimentos |
| US05 | CRUD de usuários |

**Burndown:**  
![Burndown Sprint 1](./docs/sprint2/burndownSprint2.png)

</details>

### Sprint 3

<details>
  <summary>Detalhes da Sprint 3</summary>

  <br>

**Objetivo da Sprint:**  
Nessa sprint, nosso foco foi as correções e atualizações dos dashboards e na entrega dos modelos de sumarização e busca semântica.

**Sprint Backlog:**

| USID | Requisito    |
| ---- | ------------ |
| US06 | Sumarização  |
| US07 | Busca semântica |

**Burndown:**  
![Burndown Sprint 3](./docs/sprint3/burndownSprint3.png)

</details>

---

<div align="center">

<span id="backlog"></span>

## :clipboard: Backlog

</div>

| USID | Sprint | Requisito                               |
| ---- | ------ | --------------------------------------- |
| US01 | 01     | Dashboards                              |
| US02 | 02     | Extração de informações dos datasets    |
| US03 | 02     | Pré-processamento dos dados             |
| US04 | 02     | Classificação dos atendimentos          |
| US05 | 02     | CRUD de usuários                        |
| US06 | 03     | Sumarização automática dos atendimentos |
| US07 | 03     | Busca Semântica                         |


<div align="center">

## :scroll: User Stories

</div>

| USID | Descrição                                                                                                                                                                              |
| ---- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| US01 | Como usuário, quero que o sistema gere dashboards com informações das classificações e sumarização dos atendimentos para obter insights rápidos sobre o estado atual dos atendimentos. |
| US02 | Como usuário, quero que o sistema extraia informações relevantes do dataset de atendimento para serem analisadas pelos modelos de classificação e sumarização.                         |
| US03 | Como usuário, quero que o sistema aplique técnicas de pré-processamento nos dados extraídos para aumentar a eficácia dos modelos de classificação e sumarização.                       |
| US04 | Como usuário, quero que o sistema classifique o tipo e sentimento dos atendimentos para extrair informações precisas.                                                                  |
| US05 | Como administrador, quero cadastrar e gerenciar usuários para garantir o acesso ao sistema.                                                                                            |
| US06 | Como usuário, quero que o sistema gere um resumo automático das conversas para entender os principais pontos abordados.                                                                |
| US07 | Como usuário, quero buscar informações específicas nas interações passadas para obter dados rapidamente.                                                                               |                       |

