# 🗺️ Roadmap - Dart Learning Hub

[🇧🇷 Versão em Português](#português) | [🇺🇸 English Version](#english)

---

<a name="português"></a>

## 🇧🇷 Português

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
- Validation pipes
- Configuration management
- Environment variables
- Logging strategies

**Exercícios:** 15+ exercícios  
**Projeto:** Sistema de autenticação JWT

#### 4.2 - `04-postgresql-dart`
**Tópicos:**
- Instalando PostgreSQL
- Package `postgres`
- Connection pooling
- Raw queries
- Prepared statements
- Transactions
- Migrations básicas
- CRUD operations
- Relacionamentos (1:N, N:N)
- Índices e otimização

**Exercícios:** 15+ exercícios  
**Projeto:** API de blog com PostgreSQL

#### 4.3 - `04-mongodb-dart`
**Tópicos:**
- Instalando MongoDB
- Package `mongo_dart`
- Connections e database
- Collections
- CRUD operations
- Query operators
- Aggregation pipeline
- Índices
- Embedded documents
- Referencias entre documentos

**Exercícios:** 12+ exercícios  
**Projeto:** API de e-commerce com MongoDB

#### 4.4 - `04-projeto-fullstack-api`
**Projeto Final Integrado:**

API completa de gerenciamento de projetos (estilo Trello/Asana).

**Funcionalidades:**
- Autenticação JWT
- CRUD de usuários, projetos, tarefas
- Relacionamentos complexos
- PostgreSQL para dados estruturados
- Upload de arquivos
- Paginação e filtros
- Testes unitários e de integração

**Conceitos aplicados:**
- Vaden framework completo
- PostgreSQL com migrations
- Autenticação e autorização
- Clean architecture
- Testing

---

## 🔷 FASE 5: Flutter Fundamentos

**Duração:** 6-8 semanas  
**Pré-requisitos:** Fase 1 completa (mínimo)  
**Objetivo:** Criar interfaces mobile com Flutter

### 📚 O que você vai aprender:

- Widgets fundamentais
- Layout system
- Stateless vs Stateful widgets
- Navegação básica
- Temas e estilos
- Gestures e interações

### 📦 Repositórios:

#### 5.1 - `05-flutter-widgets-layouts`
**Tópicos:**
- Setup Flutter
- Widget tree
- MaterialApp e Scaffold
- Widgets básicos (Text, Image, Icon, Button)
- Container, Padding, Margin
- Row, Column
- Stack, Positioned
- ListView, GridView
- SingleChildScrollView
- Expanded, Flexible

**Exercícios:** 20+ exercícios  
**Projeto:** Tela de perfil responsiva

#### 5.2 - `05-flutter-navigation-routes`
**Tópicos:**
- Navigator.push/pop
- Named routes
- Passing data between screens
- Retornando dados
- Route generators
- Navegação aninhada
- Bottom navigation
- Drawer navigation
- Tab navigation

**Exercícios:** 15+ exercícios  
**Projeto:** App multi-telas com navegação

#### 5.3 - `05-flutter-state-basics`
**Tópicos:**
- StatelessWidget
- StatefulWidget
- `setState()`
- Lifecycle methods
- InheritedWidget (conceito)
- ValueNotifier
- Por que state management?

**Exercícios:** 15+ exercícios  
**Projeto:** Contador interativo avançado

#### 5.4 - `05-projeto-expense-tracker`
**Projeto Final Integrado:**

App de controle de despesas pessoais.

**Funcionalidades:**
- Adicionar/editar/remover despesas
- Categorização
- Filtros por data
- Gráficos simples
- Navegação entre telas
- Persistência local (SharedPreferences)

**Conceitos aplicados:**
- Widgets e layouts complexos
- Navegação
- State management básico
- Forms e validação

---

## 🔶 FASE 6: Flutter + APIs

**Duração:** 6-8 semanas  
**Pré-requisitos:** Fase 5 completa  
**Objetivo:** Integrar apps Flutter com APIs e gerenciar estado

### 📚 O que você vai aprender:

- Provider (state management)
- HTTP requests
- JSON parsing
- Persistência local
- Forms avançados
- Error handling em UI

### 📦 Repositórios:

#### 6.1 - `06-flutter-provider`
**Tópicos:**
- O que é Provider?
- ChangeNotifier
- Provider types (Provider, ChangeNotifierProvider, etc)
- Consumer widget
- Provider.of vs Consumer
- MultiProvider
- ProxyProvider
- Arquitetura com Provider

**Exercícios:** 15+ exercícios  
**Projeto:** App de contador com Provider

#### 6.2 - `06-flutter-http-api`
**Tópicos:**
- Package `http`
- GET, POST, PUT, DELETE requests
- Headers e authentication
- JSON parsing com `dart:convert`
- Model classes
- Serialização/Deserialização
- Error handling
- Loading states
- FutureBuilder
- Retry mechanisms

**Exercícios:** 15+ exercícios  
**Projeto:** App de notícias consumindo API

#### 6.3 - `06-flutter-local-storage`
**Tópicos:**
- SharedPreferences
- Hive database
- SQLite com sqflite
- Escolhendo storage certo
- CRUD local
- Migrations
- Offline-first approach

**Exercícios:** 12+ exercícios  
**Projeto:** App de notas com Hive

#### 6.4 - `06-projeto-todo-app-fullstack`
**Projeto Final Integrado:**

App de tarefas conectado a backend real.

**Funcionalidades:**
- CRUD de tarefas
- Sincronização com API
- Autenticação
- Offline support
- Pull to refresh
- Paginação
- Search e filtros

**Conceitos aplicados:**
- Provider para state management
- HTTP para API integration
- Hive para cache local
- Tratamento de erros
- Loading/error states

---

## 🔷 FASE 6.5: Flutter Avançado

**Duração:** 4-6 semanas  
**Pré-requisitos:** Fase 6 completa  
**Objetivo:** Padrões avançados e qualidade de código

### 📚 O que você vai aprender:

- Riverpod
- Clean Architecture
- MVVM pattern
- Testing (Unit, Widget, Integration)
- Performance optimization

### 📦 Repositórios:

#### 6.5.1 - `06-flutter-riverpod`
**Tópicos:**
- Provider vs Riverpod
- Instalação e setup
- ProviderScope
- StateProvider, StateNotifierProvider
- FutureProvider, StreamProvider
- Family e AutoDispose
- ref.watch vs ref.read
- Code generation

**Exercícios:** 12+ exercícios  
**Projeto:** Migrar app Provider para Riverpod

#### 6.5.2 - `06-flutter-architecture`
**Tópicos:**
- Clean Architecture principles
- Layers (Presentation, Domain, Data)
- MVVM pattern
- Repository pattern
- Use cases
- Dependency injection
- Folder structure
- Separation of concerns

**Exercícios:** 10+ exercícios  
**Projeto:** Refatorar app com Clean Architecture

#### 6.5.3 - `06-flutter-testing`
**Tópicos:**
- Unit tests
- Widget tests
- Integration tests
- Mocking com Mockito
- Test coverage
- Golden tests
- TDD (Test-Driven Development)

**Exercícios:** 15+ exercícios  
**Projeto:** Testar app completo

#### 6.5.4 - `06-projeto-production-ready-app`
**Projeto Final Integrado:**

App production-ready seguindo best practices.

**Características:**
- Clean Architecture
- Riverpod
- 80%+ test coverage
- CI/CD ready
- Error tracking
- Analytics
- Performance optimized

---

## 🔶 FASE 7: Tópicos Especializados

**Duração:** 8-10 semanas  
**Pré-requisitos:** Fases anteriores completas  
**Objetivo:** Tópicos avançados e especializações

### 📚 O que você vai aprender:

- Platform Channels (Kotlin)
- MCP (Model Context Protocol)
- Integração com IA
- Microservices com Dart
- Real-time com WebSockets

### 📦 Repositórios:

#### 7.1 - `07-flutter-platform-channels`
**Tópicos:**
- O que são Platform Channels?
- MethodChannel
- EventChannel
- BasicMessageChannel
- Escrevendo código Kotlin
- Integração Android nativa
- Plugins customizados

**Exercícios:** 10+ exercícios  
**Projeto:** Plugin customizado Android

#### 7.2 - `07-dart-mcp-integration`
**Tópicos:**
- O que é MCP?
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

<a name="english"></a>

## 🇺🇸 English

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

*[Note: Due to length, I'm providing the full Portuguese version above. The English version follows the same structure with translated content for all 7 phases. Would you like me to continue with the complete English translation?]*

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

[Back to Start](./README.md) • [Contribute](./CONTRIBUTING.md) • [License](./LICENSE)

</div>
