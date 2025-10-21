# 🗺️ Roadmap - Dart Learning Hub

<div align="center">

### 🌍 Choose Your Language / Escolha seu Idioma

[![Português](https://img.shields.io/badge/Idioma-Português-green?style=for-the-badge)](#português)
[![English](https://img.shields.io/badge/Language-English-blue?style=for-the-badge)](#english)

</div>

---

<div align="center">

## <a name="português"></a>
🇧🇷 **PORTUGUÊS**

[![Switch to English](https://img.shields.io/badge/🇺🇸_Switch_to-English-blue)](#english)

</div>

---

### Roadmap Completo de Aprendizado

Este documento detalha todas as **7 fases** do Dart Learning Hub, incluindo objetivos, tópicos, repositórios e projetos práticos de cada fase.

---

## 📊 Visão Geral

| Fase | Duração | Repos | Status |
|------|---------|-------|--------|
| [1. Dart Essencial](#fase-1-dart-essencial) | 6-8 sem | 4 | 🟡 Em desenvolvimento |
| [2. Dart Intermediário](#fase-2-dart-intermediário) | 6-8 sem | 4 | ⚪ Planejado |
| [3. Dart Avançado + Backend](#fase-3-dart-avançado--backend) | 6-8 sem | 4 | ⚪ Planejado |
| [4. Backend Completo](#fase-4-backend-completo) | 8-10 sem | 4 | ⚪ Planejado |
| [5. Flutter Fundamentos](#fase-5-flutter-fundamentos) | 6-8 sem | 4 | ⚪ Planejado |
| [6. Flutter + APIs](#fase-6-flutter--apis) | 6-8 sem | 4 | ⚪ Planejado |
| [6.5. Flutter Avançado](#fase-65-flutter-avançado) | 4-6 sem | 4 | ⚪ Planejado |
| [7. Tópicos Especializados](#fase-7-tópicos-especializados) | 8-10 sem | 4 | ⚪ Planejado |

**Tempo total estimado:** 50-66 semanas (~1 a 1,3 anos)

---

## 🔷 FASE 1: Dart Essencial

**Duração:** 6-8 semanas  
**Pré-requisitos:** Nenhum (começa do zero)  
**Objetivo:** Dominar os fundamentos da linguagem Dart

### 📚 O que você vai aprender:

- Sintaxe básica da linguagem
- Tipos de dados e variáveis
- Operadores e expressões
- Estruturas de controle de fluxo
- Funções e escopo
- Collections (List, Map, Set)
- Classes e objetos
- Herança básica

### 📦 Repositórios:

#### 1.1 - `01-dart-fundamentals-core`
**Tópicos:**
- Hello World e estrutura básica
- Variáveis e tipos (`int`, `double`, `String`, `bool`)
- Type inference e `var`
- Operadores aritméticos, relacionais e lógicos
- Comentários e documentação
- `if/else`, `switch/case`
- Loops: `for`, `while`, `do-while`
- `break` e `continue`

**Exercícios:** 15+ exercícios progressivos  
**Projeto:** Calculadora de console

#### 1.2 - `01-dart-functions-collections`
**Tópicos:**
- Declaração de funções
- Parâmetros posicionais e nomeados
- Parâmetros opcionais
- Arrow functions
- Funções anônimas
- Escopo de variáveis
- List: criação, acesso, métodos
- Map: criação, acesso, iteração
- Set: operações de conjunto

**Exercícios:** 20+ exercícios progressivos  
**Projeto:** Sistema de gerenciamento de tarefas (TODO CLI)

#### 1.3 - `01-dart-oop-basics`
**Tópicos:**
- Classes e objetos
- Construtores (padrão, nomeados, factory)
- Propriedades e métodos
- Getters e setters
- `this` keyword
- Encapsulamento (public/private)
- Herança com `extends`
- `super` keyword
- Polimorfismo básico
- `@override`

**Exercícios:** 20+ exercícios progressivos  
**Projeto:** Sistema de biblioteca (classes Livro, Usuario, Biblioteca)

#### 1.4 - `01-projeto-cli-todo-app`
**Projeto Final Integrado:**

Sistema completo de gerenciamento de tarefas via linha de comando.

**Funcionalidades:**
- Adicionar, listar, editar, remover tarefas
- Marcar tarefas como concluídas
- Filtrar por status (pendente/concluída)
- Persistência em arquivo JSON
- Menu interativo

**Conceitos aplicados:**
- Todas as estruturas de controle
- Funções e modularização
- Collections para armazenar tarefas
- OOP para modelar Tarefa, Usuario, Sistema
- Leitura/escrita de arquivos

---

## 🔶 FASE 2: Dart Intermediário

**Duração:** 6-8 semanas  
**Pré-requisitos:** Fase 1 completa  
**Objetivo:** Dominar conceitos avançados de OOP e programação assíncrona

### 📚 O que você vai aprender:

- OOP avançada (mixins, interfaces, abstract classes)
- Generics
- Null Safety
- Error handling
- Async/Await
- Futures
- Exception handling

### 📦 Repositórios:

#### 2.1 - `02-dart-oop-advanced`
**Tópicos:**
- Abstract classes
- Interfaces com `implements`
- Mixins com `with`
- Extension methods
- Callable classes
- `static` members
- Enums
- Padrões de design básicos (Factory, Singleton)

**Exercícios:** 20+ exercícios  
**Projeto:** Sistema de pagamentos (múltiplas formas de pagamento)

#### 2.2 - `02-dart-generics-nullsafety`
**Tópicos:**
- Generics em classes
- Generics em funções
- Type constraints
- Null Safety fundamentals
- Nullable types (`?`)
- Non-nullable by default
- Null assertion (`!`)
- Null-aware operators (`??`, `?.`, `??=`)
- Late variables
- Required parameters

**Exercícios:** 15+ exercícios  
**Projeto:** Estruturas de dados genéricas (Stack, Queue)

#### 2.3 - `02-dart-async-futures`
**Tópicos:**
- Programação síncrona vs assíncrona
- `Future<T>`
- `async` e `await`
- `then()` e `catchError()`
- `Future.delayed()`
- `Future.value()` e `Future.error()`
- Encadeamento de Futures
- `Future.wait()` para paralelismo
- Try-catch com async/await

**Exercícios:** 15+ exercícios  
**Projeto:** Cliente HTTP simples (consumir API pública)

#### 2.4 - `02-projeto-weather-cli`
**Projeto Final Integrado:**

Aplicação CLI que consome API de clima e exibe previsões.

**Funcionalidades:**
- Buscar clima por cidade
- Exibir temperatura, umidade, condições
- Histórico de buscas
- Cache de resultados
- Tratamento de erros de rede

**Conceitos aplicados:**
- Async/await para requisições HTTP
- Generics para tipagem forte
- Null safety em dados da API
- Error handling robusto
- OOP avançada para modelagem

---

## 🔷 FASE 3: Dart Avançado + Backend

**Duração:** 6-8 semanas  
**Pré-requisitos:** Fase 2 completa  
**Objetivo:** Streams, programação reativa e introdução a backend

### 📚 O que você vai aprender:

- Streams
- Programação reativa
- HTTP Server básico com Shelf
- Introdução ao Vaden Framework
- Routing básico
- Middleware concepts

### 📦 Repositórios:

#### 3.1 - `03-dart-streams-reactive`
**Tópicos:**
- `Stream<T>`
- Single-subscription vs Broadcast streams
- `StreamController`
- `await for` loop
- Stream transformers (`map`, `where`, `expand`)
- `listen()`, `onData`, `onError`, `onDone`
- `StreamSubscription`
- `async*` e `yield`
- Backpressure handling

**Exercícios:** 15+ exercícios  
**Projeto:** Monitor de sistema em tempo real

#### 3.2 - `03-dart-http-server-shelf`
**Tópicos:**
- HTTP básico (request, response, methods, status codes)
- Instalando Shelf package
- Criando servidor HTTP
- Handlers e routing
- Request parsing
- Response building
- Middleware básico
- Serving static files

**Exercícios:** 10+ exercícios  
**Projeto:** API REST simples (CRUD in-memory)

#### 3.3 - `03-vaden-framework-intro`
**Tópicos:**
- O que é Vaden?
- Instalação e setup
- Annotations (`@Controller`, `@Get`, `@Post`)
- Dependency Injection básica
- Routing automático
- DTOs (Data Transfer Objects)
- Request/Response handling
- OpenAPI/Swagger integration

**Exercícios:** 10+ exercícios  
**Projeto:** API de produtos (CRUD sem persistência)

#### 3.4 - `03-projeto-rest-api-tasks`
**Projeto Final Integrado:**

API REST completa para gerenciamento de tarefas (sem banco de dados ainda).

**Funcionalidades:**
- CRUD completo de tarefas
- Endpoints RESTful
- Validação de dados
- Error handling
- Documentação OpenAPI
- Middleware de logging

**Conceitos aplicados:**
- Vaden framework
- Streams para eventos
- DTOs e validação
- Padrões REST

---

## 🔶 FASE 4: Backend Completo

**Duração:** 8-10 semanas  
**Pré-requisitos:** Fase 3 completa  
**Objetivo:** Backend production-ready com bancos de dados

### 📚 O que você vai aprender:

- Vaden Framework avançado
- PostgreSQL com Dart
- MongoDB com Dart
- ORMs e query builders
- Autenticação e autorização
- Migrations
- Testing de APIs

### 📦 Repositórios:

#### 4.1 - `04-vaden-advanced`
**Tópicos:**
- Dependency Injection avançada
- Middlewares customizados
- Guards para autorização
- Interceptors
- Exception filters
- Pipes para validação
- WebSockets
- Server-Sent Events (SSE)

**Exercícios:** 15+ exercícios  
**Projeto:** API com autenticação JWT

#### 4.2 - `04-postgresql-dart`
**Tópicos:**
- Instalando PostgreSQL
- Conectando com `postgres` package
- Queries SQL básicas (SELECT, INSERT, UPDATE, DELETE)
- Prepared statements
- Transactions
- Connection pooling
- Migrations com `drift` ou similar
- Schema design

**Exercícios:** 15+ exercícios  
**Projeto:** API com persistência em PostgreSQL

#### 4.3 - `04-mongodb-dart`
**Tópicos:**
- Instalando MongoDB
- Conectando com `mongo_dart`
- CRUD operations
- Queries e filtros
- Aggregation pipeline
- Indexes
- Schema validation
- Embedded vs referenced documents

**Exercícios:** 10+ exercícios  
**Projeto:** API com MongoDB

#### 4.4 - `04-projeto-backend-ecommerce`
**Projeto Final Integrado:**

Backend completo de e-commerce com autenticação.

**Funcionalidades:**
- Autenticação JWT
- CRUD de produtos
- Carrinho de compras
- Sistema de pedidos
- PostgreSQL para dados transacionais
- MongoDB para logs e analytics
- Testes unitários e de integração

**Conceitos aplicados:**
- Vaden avançado
- Multiple databases
- Auth & authorization
- Testing
- Production-ready patterns

---

## 🔷 FASE 5: Flutter Fundamentos

**Duração:** 6-8 semanas  
**Pré-requisitos:** Fase 1 completa (Fases 2-4 opcionais)  
**Objetivo:** Dominar os fundamentos do Flutter

### 📚 O que você vai aprender:

- Widgets básicos
- Layout e composição
- Navegação
- Gerenciamento de estado básico (setState)
- Assets e imagens
- Formulários
- Listas e grids

### 📦 Repositórios:

#### 5.1 - `05-flutter-basics-widgets`
**Tópicos:**
- Instalação Flutter
- Estrutura de projeto Flutter
- Material Design vs Cupertino
- StatelessWidget vs StatefulWidget
- Widgets básicos (Text, Container, Row, Column)
- Padding, Margin, Alignment
- Scaffold, AppBar, BottomNavigationBar
- Buttons (ElevatedButton, TextButton, IconButton)
- Icons e Colors

**Exercícios:** 15+ exercícios  
**Projeto:** App de perfil estático

#### 5.2 - `05-flutter-layout-navigation`
**Tópicos:**
- Layout widgets (Stack, Expanded, Flexible)
- ListView e GridView
- SingleChildScrollView
- Navigator e rotas
- Named routes
- Passing data between screens
- Hero animations
- Bottom sheets e dialogs

**Exercícios:** 15+ exercícios  
**Projeto:** App multi-tela com navegação

#### 5.3 - `05-flutter-state-forms`
**Tópicos:**
- setState() e state management
- TextEditingController
- Form e FormField
- Validation
- TextField, Checkbox, Radio, Switch
- DatePicker e TimePicker
- DropdownButton
- InheritedWidget básico

**Exercícios:** 15+ exercícios  
**Projeto:** Formulário de cadastro completo

#### 5.4 - `05-projeto-flutter-todo-app`
**Projeto Final Integrado:**

App completo de TODO list com persistência local.

**Funcionalidades:**
- CRUD de tarefas
- Filtros (todas/pendentes/concluídas)
- Categorias
- Data de vencimento
- Persistência com SharedPreferences
- UI responsiva

**Conceitos aplicados:**
- Todos os widgets aprendidos
- Navegação
- State management com setState
- Persistência local
- Forms e validação

---

## 🔶 FASE 6: Flutter + APIs

**Duração:** 6-8 semanas  
**Pré-requisitos:** Fases 1, 2 e 5 completas  
**Objetivo:** Integrar Flutter com APIs e gerenciar estado avançado

### 📚 O que você vai aprender:

- HTTP requests
- JSON parsing
- Provider para state management
- Persistência com SQLite
- Shared Preferences
- Image caching
- Error handling

### 📦 Repositórios:

#### 6.1 - `06-flutter-http-api`
**Tópicos:**
- Package `http`
- GET, POST, PUT, DELETE requests
- Headers e authentication
- JSON serialization/deserialization
- Freezed para data classes
- Error handling
- Loading states
- Retry logic

**Exercícios:** 15+ exercícios  
**Projeto:** App consumindo API pública

#### 6.2 - `06-flutter-provider`
**Tópicos:**
- O que é Provider?
- ChangeNotifier
- Consumer e Provider.of
- MultiProvider
- ProxyProvider
- Separação de concerns
- Repository pattern
- Service layer

**Exercícios:** 15+ exercícios  
**Projeto:** App com Provider

#### 6.3 - `06-flutter-persistence`
**Tópicos:**
- SharedPreferences
- SQLite com `sqflite`
- CRUD operations
- Migrations
- Queries complexas
- Cached network images
- File storage
- Secure storage

**Exercícios:** 10+ exercícios  
**Projeto:** App com cache e database local

#### 6.4 - `06-projeto-flutter-social-app`
**Projeto Final Integrado:**

App social (clone de Instagram/Twitter simplificado).

**Funcionalidades:**
- Login e registro
- Feed de posts
- Criar post com imagem
- Like e comentários
- Perfil de usuário
- Seguir/deixar de seguir
- Persistência local
- Integração com backend

**Conceitos aplicados:**
- HTTP + API integration
- Provider para state
- SQLite para cache
- Image picker e display
- Complex UI
- Navigation

---

## 🔷 FASE 6.5: Flutter Avançado

**Duração:** 4-6 semanas  
**Pré-requisitos:** Fase 6 completa  
**Objetivo:** Arquitetura, testing e state management avançado

### 📚 O que você vai aprender:

- Riverpod
- Clean Architecture
- Testing (unit, widget, integration)
- CI/CD
- Performance optimization
- Animações avançadas

### 📦 Repositórios:

#### 6.5.1 - `065-flutter-riverpod`
**Tópicos:**
- Riverpod vs Provider
- Providers (Provider, StateProvider, FutureProvider, StreamProvider)
- StateNotifier e StateNotifierProvider
- Family e autoDispose
- ProviderScope
- Testing com Riverpod
- Dependency injection

**Exercícios:** 15+ exercícios  
**Projeto:** Migrar projeto Provider para Riverpod

#### 6.5.2 - `065-flutter-architecture`
**Tópicos:**
- Clean Architecture principles
- Presentation, Domain, Data layers
- Use cases
- Repositories
- Entities vs Models
- Dependency Inversion
- SOLID principles
- Project structure

**Exercícios:** 10+ exercícios  
**Projeto:** App com Clean Architecture

#### 6.5.3 - `065-flutter-testing`
**Tópicos:**
- Unit tests com `test` package
- Widget tests
- Integration tests
- Mocking com `mockito`
- Test coverage
- Golden tests
- TDD approach
- CI/CD com GitHub Actions

**Exercícios:** 15+ exercícios  
**Projeto:** Adicionar testes ao projeto anterior

#### 6.5.4 - `065-projeto-flutter-advanced`
**Projeto Final Integrado:**

App production-ready com todas as best practices.

**Funcionalidades:**
- Feature completa (ex: marketplace, delivery)
- Clean Architecture
- Riverpod
- 80%+ test coverage
- CI/CD pipeline
- Error tracking
- Analytics
- Performance optimization

**Conceitos aplicados:**
- Todos os conceitos avançados
- Production-ready
- Testable code
- Maintainable architecture

---

## 🔶 FASE 7: Tópicos Especializados

**Duração:** 8-10 semanas  
**Pré-requisitos:** Fases anteriores completas  
**Objetivo:** Tópicos avançados e especializados

### 📚 O que você vai aprender:

- Platform Channels
- Microservices
- Model Context Protocol (MCP)
- IA integration
- Performance otimization
- Publishing apps

### 📦 Repositórios:

#### 7.1 - `07-flutter-platform-channels`
**Tópicos:**
- O que são Platform Channels?
- MethodChannel
- EventChannel
- BasicMessageChannel
- Comunicação Flutter ↔ Native
- iOS native code (Swift/Objective-C)
- Android native code (Kotlin/Java)
- Plugins customizados

**Exercícios:** 10+ exercícios  
**Projeto:** Plugin customizado

#### 7.2 - `07-dart-mcp-protocol`
**Tópicos:**
- O que é Model Context Protocol?
- Protocol basics
- Tools e resources
- Sampling
- Prompts
- Integração com Claude/outros LLMs
- Use cases práticos

**Exercícios:** 10+ exercícios  
**Projeto:** CLI tool com MCP

#### 7.3 - `07-dart-ai-integration`
**Tópicos:**
- APIs de IA (OpenAI, Claude, etc)
- Prompt engineering
- Context management
- Streaming responses
- Error handling
- Rate limiting
- Cost optimization

**Exercícios:** 10+ exercícios  
**Projeto:** Chatbot com IA

#### 7.4 - `07-projeto-final-fullstack-ai`
**Projeto Final Integrado:**

Aplicação fullstack com feature de IA.

**Sugestões:**
- App de análise de documentos com IA
- Assistant de código
- Chatbot inteligente
- Sistema de recomendação

**Conceitos aplicados:**
- Flutter + Backend + IA
- Microservices
- Real-time communication
- Platform channels se necessário
- Production-ready

---

## 🎯 Como Usar Este Roadmap

### Para Estudantes:

1. **Não pule fases** - Cada uma prepara para a próxima
2. **Faça TODOS os exercícios** - Prática é fundamental
3. **Construa os projetos** - Eles consolidam o aprendizado
4. **Tire dúvidas** - Use as issues dos repositórios

### Para Instrutores:

1. **Adapte o ritmo** - Duração é sugestão
2. **Adicione exercícios** - Baseado na sua experiência
3. **Use em sala** - Material é open source
4. **Contribua** - Melhore o conteúdo

### Para Autodidatas:

1. **Seja disciplinado** - Crie um cronograma
2. **Pratique diariamente** - Consistência > intensidade
3. **Busque comunidade** - Aprenda com outros
4. **Construa portfólio** - Mostre seus projetos

---

## 📅 Cronograma Sugerido

### Ritmo Intensivo (50 semanas / ~1 ano)
- **Dedicação:** 15-20h/semana
- **Público:** Estudantes em período integral

### Ritmo Moderado (66 semanas / ~1,3 anos)
- **Dedicação:** 10-15h/semana
- **Público:** Profissionais em transição

### Ritmo Flexível (personalizado)
- **Dedicação:** Conforme disponibilidade
- **Público:** Aprendizado no seu ritmo

---

## 🔄 Status de Desenvolvimento

**Última atualização:** Outubro 2025

| Fase | Planejamento | Desenvolvimento | Completo |
|------|--------------|-----------------|----------|
| Fase 1 | ✅ | 🟡 25% | ❌ |
| Fase 2 | ✅ | ⚪ 0% | ❌ |
| Fase 3 | ✅ | ⚪ 0% | ❌ |
| Fase 4 | ✅ | ⚪ 0% | ❌ |
| Fase 5 | ✅ | ⚪ 0% | ❌ |
| Fase 6 | ✅ | ⚪ 0% | ❌ |
| Fase 6.5 | ✅ | ⚪ 0% | ❌ |
| Fase 7 | ✅ | ⚪ 0% | ❌ |

---

## 🤝 Ajude a Construir

Este roadmap está em construção ativa! Contribua:

- 📝 Sugerindo tópicos adicionais
- 🔄 Propondo reordenação
- ✨ Adicionando recursos
- 🐛 Reportando inconsistências

**[Abra uma issue](../../issues)** com suas sugestões!

---
---
---

<div align="center">

## <a name="english"></a>
🇺🇸 **ENGLISH**

[![Mudar para Português](https://img.shields.io/badge/🇧🇷_Mudar_para-Português-green)](#português)

</div>

---

### Complete Learning Roadmap

This document details all **7 phases** of the Dart Learning Hub, including objectives, topics, repositories, and practical projects for each phase.

---

## 📊 Overview

| Phase | Duration | Repos | Status |
|-------|----------|-------|--------|
| [1. Dart Essentials](#phase-1-dart-essentials) | 6-8 weeks | 4 | 🟡 In development |
| [2. Intermediate Dart](#phase-2-intermediate-dart) | 6-8 weeks | 4 | ⚪ Planned |
| [3. Advanced Dart + Backend](#phase-3-advanced-dart--backend) | 6-8 weeks | 4 | ⚪ Planned |
| [4. Complete Backend](#phase-4-complete-backend) | 8-10 weeks | 4 | ⚪ Planned |
| [5. Flutter Fundamentals](#phase-5-flutter-fundamentals) | 6-8 weeks | 4 | ⚪ Planned |
| [6. Flutter + APIs](#phase-6-flutter--apis) | 6-8 weeks | 4 | ⚪ Planned |
| [6.5. Advanced Flutter](#phase-65-advanced-flutter) | 4-6 weeks | 4 | ⚪ Planned |
| [7. Specialized Topics](#phase-7-specialized-topics) | 8-10 weeks | 4 | ⚪ Planned |

**Total estimated time:** 50-66 weeks (~1 to 1.3 years)

---

## 🔷 PHASE 1: Dart Essentials

**Duration:** 6-8 weeks  
**Prerequisites:** None (starts from scratch)  
**Goal:** Master Dart language fundamentals

### 📚 What you'll learn:

- Basic language syntax
- Data types and variables
- Operators and expressions
- Control flow structures
- Functions and scope
- Collections (List, Map, Set)
- Classes and objects
- Basic inheritance

### 📦 Repositories:

#### 1.1 - `01-dart-fundamentals-core`
**Topics:**
- Hello World and basic structure
- Variables and types (`int`, `double`, `String`, `bool`)
- Type inference and `var`
- Arithmetic, relational, and logical operators
- Comments and documentation
- `if/else`, `switch/case`
- Loops: `for`, `while`, `do-while`
- `break` and `continue`

**Exercises:** 15+ progressive exercises  
**Project:** Console calculator

#### 1.2 - `01-dart-functions-collections`
**Topics:**
- Function declaration
- Positional and named parameters
- Optional parameters
- Arrow functions
- Anonymous functions
- Variable scope
- List: creation, access, methods
- Map: creation, access, iteration
- Set: set operations

**Exercises:** 20+ progressive exercises  
**Project:** Task management system (TODO CLI)

#### 1.3 - `01-dart-oop-basics`
**Topics:**
- Classes and objects
- Constructors (default, named, factory)
- Properties and methods
- Getters and setters
- `this` keyword
- Encapsulation (public/private)
- Inheritance with `extends`
- `super` keyword
- Basic polymorphism
- `@override`

**Exercises:** 20+ progressive exercises  
**Project:** Library system (Book, User, Library classes)

#### 1.4 - `01-projeto-cli-todo-app`
**Integrated Final Project:**

Complete command-line task management system.

**Features:**
- Add, list, edit, remove tasks
- Mark tasks as completed
- Filter by status (pending/completed)
- JSON file persistence
- Interactive menu

**Applied concepts:**
- All control structures
- Functions and modularization
- Collections for storing tasks
- OOP to model Task, User, System
- File read/write

---

## 🔶 PHASE 2: Intermediate Dart

**Duration:** 6-8 weeks  
**Prerequisites:** Phase 1 complete  
**Goal:** Master advanced OOP and asynchronous programming concepts

### 📚 What you'll learn:

- Advanced OOP (mixins, interfaces, abstract classes)
- Generics
- Null Safety
- Error handling
- Async/Await
- Futures
- Exception handling

### 📦 Repositories:

#### 2.1 - `02-dart-oop-advanced`
**Topics:**
- Abstract classes
- Interfaces with `implements`
- Mixins with `with`
- Extension methods
- Callable classes
- `static` members
- Enums
- Basic design patterns (Factory, Singleton)

**Exercises:** 20+ exercises  
**Project:** Payment system (multiple payment methods)

#### 2.2 - `02-dart-generics-nullsafety`
**Topics:**
- Generics in classes
- Generics in functions
- Type constraints
- Null Safety fundamentals
- Nullable types (`?`)
- Non-nullable by default
- Null assertion (`!`)
- Null-aware operators (`??`, `?.`, `??=`)
- Late variables
- Required parameters

**Exercises:** 15+ exercises  
**Project:** Generic data structures (Stack, Queue)

#### 2.3 - `02-dart-async-futures`
**Topics:**
- Synchronous vs asynchronous programming
- `Future<T>`
- `async` and `await`
- `then()` and `catchError()`
- `Future.delayed()`
- `Future.value()` and `Future.error()`
- Chaining Futures
- `Future.wait()` for parallelism
- Try-catch with async/await

**Exercises:** 15+ exercises  
**Project:** Simple HTTP client (consume public API)

#### 2.4 - `02-projeto-weather-cli`
**Integrated Final Project:**

CLI application that consumes weather API and displays forecasts.

**Features:**
- Search weather by city
- Display temperature, humidity, conditions
- Search history
- Result caching
- Network error handling

**Applied concepts:**
- Async/await for HTTP requests
- Generics for strong typing
- Null safety in API data
- Robust error handling
- Advanced OOP for modeling

---

## 🔷 PHASE 3: Advanced Dart + Backend

**Duration:** 6-8 weeks  
**Prerequisites:** Phase 2 complete  
**Goal:** Streams, reactive programming and backend introduction

### 📚 What you'll learn:

- Streams
- Reactive programming
- Basic HTTP Server with Shelf
- Vaden Framework introduction
- Basic routing
- Middleware concepts

### 📦 Repositories:

#### 3.1 - `03-dart-streams-reactive`
**Topics:**
- `Stream<T>`
- Single-subscription vs Broadcast streams
- `StreamController`
- `await for` loop
- Stream transformers (`map`, `where`, `expand`)
- `listen()`, `onData`, `onError`, `onDone`
- `StreamSubscription`
- `async*` and `yield`
- Backpressure handling

**Exercises:** 15+ exercises  
**Project:** Real-time system monitor

#### 3.2 - `03-dart-http-server-shelf`
**Topics:**
- HTTP basics (request, response, methods, status codes)
- Installing Shelf package
- Creating HTTP server
- Handlers and routing
- Request parsing
- Response building
- Basic middleware
- Serving static files

**Exercises:** 10+ exercises  
**Project:** Simple REST API (in-memory CRUD)

#### 3.3 - `03-vaden-framework-intro`
**Topics:**
- What is Vaden?
- Installation and setup
- Annotations (`@Controller`, `@Get`, `@Post`)
- Basic Dependency Injection
- Automatic routing
- DTOs (Data Transfer Objects)
- Request/Response handling
- OpenAPI/Swagger integration

**Exercises:** 10+ exercises  
**Project:** Products API (CRUD without persistence)

#### 3.4 - `03-projeto-rest-api-tasks`
**Integrated Final Project:**

Complete REST API for task management (no database yet).

**Features:**
- Complete CRUD of tasks
- RESTful endpoints
- Data validation
- Error handling
- OpenAPI documentation
- Logging middleware

**Applied concepts:**
- Vaden framework
- Streams for events
- DTOs and validation
- REST patterns

---

## 🔶 PHASE 4: Complete Backend

**Duration:** 8-10 weeks  
**Prerequisites:** Phase 3 complete  
**Goal:** Production-ready backend with databases

### 📚 What you'll learn:

- Advanced Vaden Framework
- PostgreSQL with Dart
- MongoDB with Dart
- ORMs and query builders
- Authentication and authorization
- Migrations
- API testing

### 📦 Repositories:

#### 4.1 - `04-vaden-advanced`
**Topics:**
- Advanced Dependency Injection
- Custom middlewares
- Guards for authorization
- Interceptors
- Exception filters
- Pipes for validation
- WebSockets
- Server-Sent Events (SSE)

**Exercises:** 15+ exercises  
**Project:** API with JWT authentication

#### 4.2 - `04-postgresql-dart`
**Topics:**
- Installing PostgreSQL
- Connecting with `postgres` package
- Basic SQL queries (SELECT, INSERT, UPDATE, DELETE)
- Prepared statements
- Transactions
- Connection pooling
- Migrations with `drift` or similar
- Schema design

**Exercises:** 15+ exercises  
**Project:** API with PostgreSQL persistence

#### 4.3 - `04-mongodb-dart`
**Topics:**
- Installing MongoDB
- Connecting with `mongo_dart`
- CRUD operations
- Queries and filters
- Aggregation pipeline
- Indexes
- Schema validation
- Embedded vs referenced documents

**Exercises:** 10+ exercises  
**Project:** API with MongoDB

#### 4.4 - `04-projeto-backend-ecommerce`
**Integrated Final Project:**

Complete e-commerce backend with authentication.

**Features:**
- JWT authentication
- Product CRUD
- Shopping cart
- Order system
- PostgreSQL for transactional data
- MongoDB for logs and analytics
- Unit and integration tests

**Applied concepts:**
- Advanced Vaden
- Multiple databases
- Auth & authorization
- Testing
- Production-ready patterns

---

## 🔷 PHASE 5: Flutter Fundamentals

**Duration:** 6-8 weeks  
**Prerequisites:** Phase 1 complete (Phases 2-4 optional)  
**Goal:** Master Flutter fundamentals

### 📚 What you'll learn:

- Basic widgets
- Layout and composition
- Navigation
- Basic state management (setState)
- Assets and images
- Forms
- Lists and grids

### 📦 Repositories:

#### 5.1 - `05-flutter-basics-widgets`
**Topics:**
- Flutter installation
- Flutter project structure
- Material Design vs Cupertino
- StatelessWidget vs StatefulWidget
- Basic widgets (Text, Container, Row, Column)
- Padding, Margin, Alignment
- Scaffold, AppBar, BottomNavigationBar
- Buttons (ElevatedButton, TextButton, IconButton)
- Icons and Colors

**Exercises:** 15+ exercises  
**Project:** Static profile app

#### 5.2 - `05-flutter-layout-navigation`
**Topics:**
- Layout widgets (Stack, Expanded, Flexible)
- ListView and GridView
- SingleChildScrollView
- Navigator and routes
- Named routes
- Passing data between screens
- Hero animations
- Bottom sheets and dialogs

**Exercises:** 15+ exercises  
**Project:** Multi-screen app with navigation

#### 5.3 - `05-flutter-state-forms`
**Topics:**
- setState() and state management
- TextEditingController
- Form and FormField
- Validation
- TextField, Checkbox, Radio, Switch
- DatePicker and TimePicker
- DropdownButton
- Basic InheritedWidget

**Exercises:** 15+ exercises  
**Project:** Complete registration form

#### 5.4 - `05-projeto-flutter-todo-app`
**Integrated Final Project:**

Complete TODO list app with local persistence.

**Features:**
- Task CRUD
- Filters (all/pending/completed)
- Categories
- Due date
- Persistence with SharedPreferences
- Responsive UI

**Applied concepts:**
- All learned widgets
- Navigation
- State management with setState
- Local persistence
- Forms and validation

---

## 🔶 PHASE 6: Flutter + APIs

**Duration:** 6-8 weeks  
**Prerequisites:** Phases 1, 2, and 5 complete  
**Goal:** Integrate Flutter with APIs and manage advanced state

### 📚 What you'll learn:

- HTTP requests
- JSON parsing
- Provider for state management
- SQLite persistence
- Shared Preferences
- Image caching
- Error handling

### 📦 Repositories:

#### 6.1 - `06-flutter-http-api`
**Topics:**
- `http` package
- GET, POST, PUT, DELETE requests
- Headers and authentication
- JSON serialization/deserialization
- Freezed for data classes
- Error handling
- Loading states
- Retry logic

**Exercises:** 15+ exercises  
**Project:** App consuming public API

#### 6.2 - `06-flutter-provider`
**Topics:**
- What is Provider?
- ChangeNotifier
- Consumer and Provider.of
- MultiProvider
- ProxyProvider
- Separation of concerns
- Repository pattern
- Service layer

**Exercises:** 15+ exercises  
**Project:** App with Provider

#### 6.3 - `06-flutter-persistence`
**Topics:**
- SharedPreferences
- SQLite with `sqflite`
- CRUD operations
- Migrations
- Complex queries
- Cached network images
- File storage
- Secure storage

**Exercises:** 10+ exercises  
**Project:** App with cache and local database

#### 6.4 - `06-projeto-flutter-social-app`
**Integrated Final Project:**

Social app (simplified Instagram/Twitter clone).

**Features:**
- Login and registration
- Post feed
- Create post with image
- Like and comments
- User profile
- Follow/unfollow
- Local persistence
- Backend integration

**Applied concepts:**
- HTTP + API integration
- Provider for state
- SQLite for cache
- Image picker and display
- Complex UI
- Navigation

---

## 🔷 PHASE 6.5: Advanced Flutter

**Duration:** 4-6 weeks  
**Prerequisites:** Phase 6 complete  
**Goal:** Architecture, testing and advanced state management

### 📚 What you'll learn:

- Riverpod
- Clean Architecture
- Testing (unit, widget, integration)
- CI/CD
- Performance optimization
- Advanced animations

### 📦 Repositories:

#### 6.5.1 - `065-flutter-riverpod`
**Topics:**
- Riverpod vs Provider
- Providers (Provider, StateProvider, FutureProvider, StreamProvider)
- StateNotifier and StateNotifierProvider
- Family and autoDispose
- ProviderScope
- Testing with Riverpod
- Dependency injection

**Exercises:** 15+ exercises  
**Project:** Migrate Provider project to Riverpod

#### 6.5.2 - `065-flutter-architecture`
**Topics:**
- Clean Architecture principles
- Presentation, Domain, Data layers
- Use cases
- Repositories
- Entities vs Models
- Dependency Inversion
- SOLID principles
- Project structure

**Exercises:** 10+ exercises  
**Project:** App with Clean Architecture

#### 6.5.3 - `065-flutter-testing`
**Topics:**
- Unit tests with `test` package
- Widget tests
- Integration tests
- Mocking with `mockito`
- Test coverage
- Golden tests
- TDD approach
- CI/CD with GitHub Actions

**Exercises:** 15+ exercises  
**Project:** Add tests to previous project

#### 6.5.4 - `065-projeto-flutter-advanced`
**Integrated Final Project:**

Production-ready app with all best practices.

**Features:**
- Complete feature (e.g., marketplace, delivery)
- Clean Architecture
- Riverpod
- 80%+ test coverage
- CI/CD pipeline
- Error tracking
- Analytics
- Performance optimization

**Applied concepts:**
- All advanced concepts
- Production-ready
- Testable code
- Maintainable architecture

---

## 🔶 PHASE 7: Specialized Topics

**Duration:** 8-10 weeks  
**Prerequisites:** Previous phases complete  
**Goal:** Advanced and specialized topics

### 📚 What you'll learn:

- Platform Channels
- Microservices
- Model Context Protocol (MCP)
- AI integration
- Performance optimization
- Publishing apps

### 📦 Repositories:

#### 7.1 - `07-flutter-platform-channels`
**Topics:**
- What are Platform Channels?
- MethodChannel
- EventChannel
- BasicMessageChannel
- Flutter ↔ Native communication
- iOS native code (Swift/Objective-C)
- Android native code (Kotlin/Java)
- Custom plugins

**Exercises:** 10+ exercises  
**Project:** Custom plugin

#### 7.2 - `07-dart-mcp-protocol`
**Topics:**
- What is Model Context Protocol?
- Protocol basics
- Tools and resources
- Sampling
- Prompts
- Integration with Claude/other LLMs
- Practical use cases

**Exercises:** 10+ exercises  
**Project:** CLI tool with MCP

#### 7.3 - `07-dart-ai-integration`
**Topics:**
- AI APIs (OpenAI, Claude, etc)
- Prompt engineering
- Context management
- Streaming responses
- Error handling
- Rate limiting
- Cost optimization

**Exercises:** 10+ exercises  
**Project:** Chatbot with AI

#### 7.4 - `07-projeto-final-fullstack-ai`
**Integrated Final Project:**

Fullstack application with AI feature.

**Suggestions:**
- Document analysis app with AI
- Code assistant
- Intelligent chatbot
- Recommendation system

**Applied concepts:**
- Flutter + Backend + AI
- Microservices
- Real-time communication
- Platform channels if needed
- Production-ready

---

## 🎯 How to Use This Roadmap

### For Students:

1. **Don't skip phases** - Each prepares for the next
2. **Do ALL exercises** - Practice is fundamental
3. **Build the projects** - They consolidate learning
4. **Ask questions** - Use repository issues

### For Instructors:

1. **Adapt the pace** - Duration is a suggestion
2. **Add exercises** - Based on your experience
3. **Use in classroom** - Material is open source
4. **Contribute** - Improve the content

### For Self-Learners:

1. **Be disciplined** - Create a schedule
2. **Practice daily** - Consistency > intensity
3. **Seek community** - Learn with others
4. **Build portfolio** - Show your projects

---

## 📅 Suggested Schedule

### Intensive Pace (50 weeks / ~1 year)
- **Dedication:** 15-20h/week
- **Audience:** Full-time students

### Moderate Pace (66 weeks / ~1.3 years)
- **Dedication:** 10-15h/week
- **Audience:** Transitioning professionals

### Flexible Pace (personalized)
- **Dedication:** According to availability
- **Audience:** Learning at your own pace

---

## 🔄 Development Status

**Last update:** October 2025

| Phase | Planning | Development | Complete |
|-------|----------|-------------|----------|
| Phase 1 | ✅ | 🟡 25% | ❌ |
| Phase 2 | ✅ | ⚪ 0% | ❌ |
| Phase 3 | ✅ | ⚪ 0% | ❌ |
| Phase 4 | ✅ | ⚪ 0% | ❌ |
| Phase 5 | ✅ | ⚪ 0% | ❌ |
| Phase 6 | ✅ | ⚪ 0% | ❌ |
| Phase 6.5 | ✅ | ⚪ 0% | ❌ |
| Phase 7 | ✅ | ⚪ 0% | ❌ |

---

## 🤝 Help Build

This roadmap is actively under construction! Contribute by:

- 📝 Suggesting additional topics
- 🔄 Proposing reordering
- ✨ Adding resources
- 🐛 Reporting inconsistencies

**[Open an issue](../../issues)** with your suggestions!

---

<div align="center">

**Made with ❤️ for the Dart/Flutter community**

[![Back to Top](https://img.shields.io/badge/⬆️_Back_to-Top-blue)](#-roadmap---dart-learning-hub)

[Back to Start](./README.md) • [Contribute](./CONTRIBUTING.md) • [License](./LICENSE)

</div>