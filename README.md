<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=B093F9&height=180&section=header&text=Santander%202026%20%7C%20Back-end%20com%20IA&fontSize=28&fontColor=ffffff&fontAlignY=40&desc=Trilha%20completa%20em%20Java%2021%20%2B%20Spring%20Boot%20%2B%20Intelig%C3%AAncia%20Artificial&descAlignY=62&descSize=14" />

</div>

<div align="center">

![Java](https://img.shields.io/badge/Java%2021-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)
![Spring Security](https://img.shields.io/badge/Spring%20Security-6DB33F?style=for-the-badge&logo=springsecurity&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI%20Whisper-412991?style=for-the-badge&logo=openai&logoColor=white)

</div>

<br/>

Bootcamp **Santander 2026 — Back-end com Inteligência Artificial** pela [DIO](https://dio.me).
Trilha de ~49 horas cobrindo fundamentos de Java, OOP, boas práticas, Spring Boot e integração com IA.
Este repositório documenta os projetos práticos construídos ao longo da trilha.

---

## O que você encontra aqui

Este repositório **não é um caderno de exercícios**. Ele reúne apenas os entregáveis com decisões técnicas reais — projetos e desafios onde há produto, não só prática mecânica.

| Entregável | Tipo | Módulo |
|---|---|---|
| [Programando com OO em Java Na Prática](#code-challenge--oo-na-prática) | Code Challenge | OOP |
| [Design Patterns: GoF ao Spring Framework](#lab-project--design-patterns) | Lab Project | Boas Práticas |
| [API Inteligente com Reconhecimento de Fala](#lab-project--api-com-reconhecimento-de-fala) | Lab Project · Advanced | Spring Boot + IA |

---

## Estrutura do repositório

```
santander-2026-backend-ia/
│
├── oo-challenge/               # Code Challenge — OOP na prática
│   └── src/
│
├── design-patterns-lab/        # Lab Project — GoF ao Spring
│   └── src/
│
├── voice-api-lab/              # Lab Project — API com reconhecimento de fala (projeto final)
│   └── src/
│
└── README.md
```

---

## Code Challenge · OO na Prática

**Módulo:** Programando o Mundo Real com Orientação a Objetos no Java

Desafio prático de OOP aplicando os quatro pilares em um contexto real: abstração, encapsulamento, herança e polimorfismo. A diferença de um Code Challenge para um exercício comum é que o enunciado entrega um problema, não um roteiro — a solução de modelagem é decisão do desenvolvedor.

**Conceitos aplicados:**
- Modelagem de classes e responsabilidades
- Encapsulamento com modificadores de acesso
- Herança e reaproveitamento de comportamento
- Polimorfismo e contratos via interfaces

---

## Lab Project · Design Patterns

**Módulo:** Boas Práticas, Padrões e Dados no Java

Implementação dos padrões clássicos do GoF (Gang of Four) conectando à realidade do Spring Framework — onde muitos desses padrões já existem como abstrações nativas do framework.

**Padrões explorados:**
- Criacionais (Singleton, Builder, Factory)
- Estruturais (Adapter, Facade, Decorator)
- Comportamentais (Strategy, Observer, Template Method)
- Como o Spring encapsula padrões como IoC (Inversion of Control) e DI (Dependency Injection)

---

## Lab Project · API com Reconhecimento de Fala

**Módulo:** Potencializando Sua Produtividade com Spring Boot · Advanced

Projeto principal da trilha. API REST construída com Spring Boot que integra reconhecimento de voz via **OpenAI Whisper**, processa o áudio transcrito e retorna respostas inteligentes — funcionando como um assistente de voz com back-end em Java.

**Stack utilizada:**
- Java 21 + Spring Boot
- Spring Security (autenticação da API)
- Spring Cloud OpenFeign (consumo de APIs externas)
- OpenAI Whisper (transcrição de áudio)
- Spring Data JPA + PostgreSQL (persistência)

**Fluxo da aplicação:**

```
Áudio (input) → Whisper API → Transcrição → Processamento → Resposta (output)
```

> Este é o projeto principal do portfólio desta trilha.

---

## Como navegar pelo repositório

Cada pasta de projeto tem seu próprio `README.md` com contexto, decisões técnicas e como rodar localmente. Se você está aqui para estudar ou entender as escolhas feitas, comece pelo `README.md` do projeto que te interessa.

Se está avaliando o perfil técnico: o projeto de voz (`voice-api-lab`) é o melhor ponto de entrada — é onde todos os conceitos da trilha convergem.

---

## Sobre a trilha

O Santander 2026 Back-end com IA é um bootcamp estruturado em quatro módulos:

1. **Programando o Mundo Real com OO** — Classes, Herança, Interfaces, Lambdas, Collections, Exceptions
2. **Boas Práticas, Padrões e Dados** — Maven/Gradle, Annotations, SOLID, Clean Code, JDBC, Design Patterns
3. **Spring Boot na Prática** — API REST, Spring Data, Spring Security, OpenFeign
4. **Projeto Final** — API inteligente com reconhecimento de fala e Spring Boot

---

## Sobre o autor

**Felipe Visales** · QA Analyst Jr III em transição para Desenvolvimento Back-end

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/fevisales)
[![GitHub](https://img.shields.io/badge/GitHub-262436?style=for-the-badge&logo=github&logoColor=white)](https://github.com/fevisales)

<img src="https://capsule-render.vercel.app/api?type=waving&color=B093F9&height=100&section=footer" />

</div>
