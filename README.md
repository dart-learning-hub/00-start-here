# 🚀 Start Here - Dart Learning Hub

[🇧🇷 Versão em Português](#português) | [🇺🇸 English Version](#english)

---

<a name="português"></a>

## 🇧🇷 Português

### Bem-vindo ao Dart Learning Hub!

Este é o **ponto de partida** da sua jornada de aprendizado em Dart, Flutter e Backend. Aqui você encontra todos os recursos, guias e o roadmap completo do projeto.

---

## 📋 Índice

- [Sobre o Projeto](#sobre-o-projeto)
- [Como Usar Este Hub](#como-usar-este-hub)
- [Roadmap Completo](#roadmap-completo)
- [Configurando o Ambiente](#configurando-o-ambiente)
- [Estrutura dos Repositórios](#estrutura-dos-repositórios)
- [Metodologia de Ensino](#metodologia-de-ensino)
- [Recursos Adicionais](#recursos-adicionais)
- [Contribuindo](#contribuindo)
- [Licença](#licença)

---

## 📚 Sobre o Projeto

O **Dart Learning Hub** é um ecossistema completo de aprendizado que cobre:

### 🎯 Objetivos

- Fornecer uma **trilha estruturada** do básico ao avançado
- Enfatizar **aprendizado prático** através de projetos
- Preparar para **competições profissionais** (como WorldSkills)
- Capacitar para o **mercado de trabalho** em Dart/Flutter

### 🏗️ Estrutura

O hub está organizado em **7 fases progressivas**, cada uma com:
- ✅ Conceitos teóricos explicados de forma clara
- 💻 Exemplos de código comentados
- 📝 Exercícios práticos progressivos
- 🎯 Projeto final que consolida o aprendizado

---

## 🗺️ Como Usar Este Hub

### 1️⃣ Identifique seu nível

**Iniciante absoluto?**
- Comece na **Fase 1: Dart Essencial**
- Nunca programou? Perfeito! Este é seu ponto de partida.

**Já programa em outra linguagem?**
- Comece na **Fase 1** mas pode acelerar
- Foque nas diferenças específicas do Dart

**Já sabe Dart básico?**
- Avalie as Fases 2 e 3
- Vá direto para onde precisa

**Só quer Flutter?**
- Recomendamos **pelo menos Fase 1** antes
- Mas pode começar na Fase 5 se tiver pressa

### 2️⃣ Siga a sequência recomendada

```
┌─────────────────────────────────────────┐
│ Você está aqui: Escolhendo por onde começar │
└─────────────────────────────────────────┘
              ↓
┌─────────────────────────────────────────┐
│ Configure seu ambiente (veja seção abaixo) │
└─────────────────────────────────────────┘
              ↓
┌─────────────────────────────────────────┐
│ Clone o repositório da sua fase          │
└─────────────────────────────────────────┘
              ↓
┌─────────────────────────────────────────┐
│ Leia o README do módulo                  │
└─────────────────────────────────────────┘
              ↓
┌─────────────────────────────────────────┐
│ Estude os conceitos + exemplos           │
└─────────────────────────────────────────┘
              ↓
┌─────────────────────────────────────────┐
│ Faça os exercícios                       │
└─────────────────────────────────────────┘
              ↓
┌─────────────────────────────────────────┐
│ Construa o projeto final                 │
└─────────────────────────────────────────┘
              ↓
┌─────────────────────────────────────────┐
│ Próxima fase! 🎉                         │
└─────────────────────────────────────────┘
```

### 3️⃣ Pratique ativamente

- ⚠️ **NÃO apenas leia** o código
- ✅ **DIGITE** você mesmo os exemplos
- 🧪 **EXPERIMENTE** variações
- 🐛 **QUEBRE** o código de propósito para entender erros
- 💡 **CRIE** suas próprias soluções para os exercícios

---

## 🗺️ Roadmap Completo

### Visão Geral das Fases

| Fase | Tópicos | Duração | Repositórios |
|------|---------|---------|--------------|
| **1. Dart Essencial** | Sintaxe, funções, OOP básica | 6-8 sem | 4 repos |
| **2. Dart Intermediário** | OOP avançada, generics, async | 6-8 sem | 4 repos |
| **3. Dart Avançado + Backend** | Streams, HTTP server, Vaden intro | 6-8 sem | 4 repos |
| **4. Backend Completo** | Vaden avançado, PostgreSQL, MongoDB | 8-10 sem | 4 repos |
| **5. Flutter Fundamentos** | Widgets, navegação, state básico | 6-8 sem | 4 repos |
| **6. Flutter + APIs** | Provider, HTTP, persistência | 6-8 sem | 4 repos |
| **6.5 Flutter Avançado** | Riverpod, arquitetura, testing | 4-6 sem | 4 repos |
| **7. Tópicos Especializados** | Platform channels, MCP, IA | 8-10 sem | 4 repos |

**📄 [Ver ROADMAP.md completo com todos os detalhes →](./ROADMAP.md)**

---

## ⚙️ Configurando o Ambiente

### Pré-requisitos

- 💻 Computador com Windows, macOS ou Linux
- 🌐 Conexão com internet
- 📝 Editor de texto (recomendamos VS Code)

### Instalando Dart

#### Windows
```bash
# Usando Chocolatey
choco install dart-sdk

# Ou baixe do site oficial
# https://dart.dev/get-dart
```

#### macOS
```bash
# Usando Homebrew
brew tap dart-lang/dart
brew install dart
```

#### Linux
```bash
# Usando apt (Ubuntu/Debian)
sudo apt update
sudo apt install apt-transport-https
wget -qO- https://dl-ssl.google.com/linux/linux_signing_key.pub | sudo gpg --dearmor -o /usr/share/keyrings/dart.gpg
echo 'deb [signed-by=/usr/share/keyrings/dart.gpg arch=amd64] https://storage.googleapis.com/download.dartlang.org/linux/debian stable main' | sudo tee /etc/apt/sources.list.d/dart_stable.list
sudo apt update
sudo apt install dart
```

### Verificando a instalação

```bash
dart --version
# Deve mostrar algo como: Dart SDK version: 3.x.x
```

### Configurando VS Code (recomendado)

1. Instale o [VS Code](https://code.visualstudio.com/)
2. Instale a extensão **Dart**
3. Instale a extensão **Flutter** (para as fases Flutter)

### Para as Fases Flutter (5+)

```bash
# Baixe do site oficial
# https://docs.flutter.dev/get-started/install

# Verifique a instalação
flutter doctor
```

---

## 📁 Estrutura dos Repositórios

Cada repositório segue este padrão:

```
nome-do-modulo/
├── README.md                    # Visão geral do módulo
│
├── 01-conceito-basico/          # Cada conceito em sua pasta
│   ├── README.md                # Explicação teórica
│   ├── exemplos.dart            # Código de exemplo comentado
│   ├── exercicios.dart          # Exercícios práticos
│   └── solucoes/                # Soluções dos exercícios
│       └── exercicio_01.dart
│
├── 02-proximo-conceito/
│   └── ...
│
├── projeto-final/               # Projeto que integra tudo
│   ├── README.md                # Especificação do projeto
│   ├── requisitos.md            # Requisitos funcionais
│   └── exemplo-solucao/         # Uma solução de referência
│
└── recursos/                    # Materiais extras
    ├── links-uteis.md
    └── cheatsheet.md
```

---

## 🎓 Metodologia de Ensino

Este projeto segue princípios pedagógicos validados para ensino de programação:

### 📖 Progressão em Espiral

Conceitos importantes são revisitados em níveis crescentes de complexidade.

**Exemplo:** OOP
- **Fase 1:** Classes básicas e herança simples
- **Fase 2:** Mixins, interfaces, classes abstratas
- **Fase 6:** Padrões de arquitetura (MVVM, Clean Architecture)

### 🔨 Aprendizado Baseado em Projetos

Cada fase termina com um projeto prático que **consolida todo o conhecimento**.

### 👥 Leitura + Escrita de Código

- **Leia** código existente nos exemplos
- **Interprete** o que ele faz
- **Modifique** para experimentar
- **Escreva** suas próprias soluções

### ⚡ Feedback Rápido

- Exercícios com **testes automatizados**
- Validação imediata do seu código
- Aprenda com os erros rapidamente

---

## 📚 Recursos Adicionais

### Documentação Oficial

- 📘 [Dart Language Tour](https://dart.dev/language)
- 📱 [Flutter Documentation](https://docs.flutter.dev/)
- 🎯 [Dart API Reference](https://api.dart.dev/)

### Ferramentas Online

- 🎮 [DartPad](https://dartpad.dev/) - Playground interativo
- 📦 [Pub.dev](https://pub.dev/) - Repositório de packages

### Comunidades

- 💬 [Flutterando Discord](https://discord.gg/flutterando)
- 🌐 [Flutter Brasil no Telegram](https://t.me/FlutterBR)
- 🐦 [#FlutterBrasil no Twitter](https://twitter.com/search?q=%23FlutterBrasil)

---

## 🤝 Contribuindo

Este projeto é **open source** e **aberto a contribuições**!

**Formas de contribuir:**
- 🐛 Reportar bugs ou erros
- 📝 Melhorar documentação
- ✨ Adicionar novos exercícios
- 🌍 Ajudar com traduções
- 💡 Sugerir melhorias

**📄 [Leia o CONTRIBUTING.md completo →](./CONTRIBUTING.md)**

---

## 📜 Licença

Este projeto está sob a licença **MIT**.

Isso significa que você pode:
- ✅ Usar para fins educacionais
- ✅ Usar para fins comerciais
- ✅ Modificar e distribuir
- ✅ Usar em projetos privados

**[Ver LICENSE completa →](./LICENSE)**

---

## 💬 Precisa de Ajuda?

- 📖 Leia a [FAQ](./FAQ.md)
- 💬 Abra uma [Issue](../../issues)
- 🌐 Junte-se à comunidade Flutterando

---

## ⭐ Apoie o Projeto

Se este projeto está te ajudando:
- ⭐ Deixe uma estrela nos repositórios
- 🔄 Compartilhe com amigos
- 💬 Dê feedback
- 🤝 Contribua com melhorias

---

**🎯 Boa jornada de aprendizado!**

---

<a name="english"></a>

## 🇺🇸 English

### Welcome to Dart Learning Hub!

This is the **starting point** for your learning journey in Dart, Flutter, and Backend. Here you'll find all resources, guides, and the complete project roadmap.

---

## 📋 Table of Contents

- [About the Project](#about-the-project-en)
- [How to Use This Hub](#how-to-use-this-hub-en)
- [Complete Roadmap](#complete-roadmap-en)
- [Setting Up Environment](#setting-up-environment-en)
- [Repository Structure](#repository-structure-en)
- [Teaching Methodology](#teaching-methodology-en)
- [Additional Resources](#additional-resources-en)
- [Contributing](#contributing-en)
- [License](#license-en)

---

<a name="about-the-project-en"></a>

## 📚 About the Project

**Dart Learning Hub** is a complete learning ecosystem covering:

### 🎯 Goals

- Provide a **structured path** from basic to advanced
- Emphasize **practical learning** through projects
- Prepare for **professional competitions** (like WorldSkills)
- Enable **job market readiness** in Dart/Flutter

### 🏗️ Structure

The hub is organized into **7 progressive phases**, each with:
- ✅ Theoretical concepts clearly explained
- 💻 Commented code examples
- 📝 Progressive practical exercises
- 🎯 Final project consolidating learning

---

<a name="how-to-use-this-hub-en"></a>

## 🗺️ How to Use This Hub

### 1️⃣ Identify your level

**Complete beginner?**
- Start at **Phase 1: Dart Essentials**
- Never programmed? Perfect! This is your starting point.

**Already program in another language?**
- Start at **Phase 1** but can accelerate
- Focus on Dart-specific differences

**Already know basic Dart?**
- Evaluate Phases 2 and 3
- Go straight to where you need

**Just want Flutter?**
- We recommend **at least Phase 1** first
- But can start at Phase 5 if in a hurry

### 2️⃣ Follow the recommended sequence

```
┌─────────────────────────────────────────┐
│ You are here: Choosing where to start    │
└─────────────────────────────────────────┘
              ↓
┌─────────────────────────────────────────┐
│ Set up your environment (see section below) │
└─────────────────────────────────────────┘
              ↓
┌─────────────────────────────────────────┐
│ Clone your phase's repository            │
└─────────────────────────────────────────┘
              ↓
┌─────────────────────────────────────────┐
│ Read the module's README                 │
└─────────────────────────────────────────┘
              ↓
┌─────────────────────────────────────────┐
│ Study concepts + examples                │
└─────────────────────────────────────────┘
              ↓
┌─────────────────────────────────────────┐
│ Do the exercises                         │
└─────────────────────────────────────────┘
              ↓
┌─────────────────────────────────────────┐
│ Build the final project                  │
└─────────────────────────────────────────┘
              ↓
┌─────────────────────────────────────────┐
│ Next phase! 🎉                           │
└─────────────────────────────────────────┘
```

### 3️⃣ Practice actively

- ⚠️ **DON'T just read** the code
- ✅ **TYPE** the examples yourself
- 🧪 **EXPERIMENT** with variations
- 🐛 **BREAK** the code on purpose to understand errors
- 💡 **CREATE** your own solutions to exercises

---

<a name="complete-roadmap-en"></a>

## 🗺️ Complete Roadmap

### Phase Overview

| Phase | Topics | Duration | Repositories |
|-------|---------|----------|--------------|
| **1. Dart Essentials** | Syntax, functions, basic OOP | 6-8 weeks | 4 repos |
| **2. Intermediate Dart** | Advanced OOP, generics, async | 6-8 weeks | 4 repos |
| **3. Advanced Dart + Backend** | Streams, HTTP server, Vaden intro | 6-8 weeks | 4 repos |
| **4. Complete Backend** | Advanced Vaden, PostgreSQL, MongoDB | 8-10 weeks | 4 repos |
| **5. Flutter Fundamentals** | Widgets, navigation, basic state | 6-8 weeks | 4 repos |
| **6. Flutter + APIs** | Provider, HTTP, persistence | 6-8 weeks | 4 repos |
| **6.5 Advanced Flutter** | Riverpod, architecture, testing | 4-6 weeks | 4 repos |
| **7. Specialized Topics** | Platform channels, MCP, AI | 8-10 weeks | 4 repos |

**📄 [See complete ROADMAP.md with all details →](./ROADMAP.md)**

---

<a name="setting-up-environment-en"></a>

## ⚙️ Setting Up Environment

### Prerequisites

- 💻 Computer with Windows, macOS, or Linux
- 🌐 Internet connection
- 📝 Text editor (we recommend VS Code)

### Installing Dart

#### Windows
```bash
# Using Chocolatey
choco install dart-sdk

# Or download from official site
# https://dart.dev/get-dart
```

#### macOS
```bash
# Using Homebrew
brew tap dart-lang/dart
brew install dart
```

#### Linux
```bash
# Using apt (Ubuntu/Debian)
sudo apt update
sudo apt install apt-transport-https
wget -qO- https://dl-ssl.google.com/linux/linux_signing_key.pub | sudo gpg --dearmor -o /usr/share/keyrings/dart.gpg
echo 'deb [signed-by=/usr/share/keyrings/dart.gpg arch=amd64] https://storage.googleapis.com/download.dartlang.org/linux/debian stable main' | sudo tee /etc/apt/sources.list.d/dart_stable.list
sudo apt update
sudo apt install dart
```

### Verifying installation

```bash
dart --version
# Should show something like: Dart SDK version: 3.x.x
```

### Setting up VS Code (recommended)

1. Install [VS Code](https://code.visualstudio.com/)
2. Install the **Dart** extension
3. Install the **Flutter** extension (for Flutter phases)

### For Flutter Phases (5+)

```bash
# Download from official site
# https://docs.flutter.dev/get-started/install

# Verify installation
flutter doctor
```

---

<a name="repository-structure-en"></a>

## 📁 Repository Structure

Each repository follows this pattern:

```
module-name/
├── README.md                    # Module overview
│
├── 01-basic-concept/            # Each concept in its folder
│   ├── README.md                # Theoretical explanation
│   ├── examples.dart            # Commented example code
│   ├── exercises.dart           # Practical exercises
│   └── solutions/               # Exercise solutions
│       └── exercise_01.dart
│
├── 02-next-concept/
│   └── ...
│
├── final-project/               # Project integrating everything
│   ├── README.md                # Project specification
│   ├── requirements.md          # Functional requirements
│   └── sample-solution/         # A reference solution
│
└── resources/                   # Extra materials
    ├── useful-links.md
    └── cheatsheet.md
```

---

<a name="teaching-methodology-en"></a>

## 🎓 Teaching Methodology

This project follows validated pedagogical principles for programming education:

### 📖 Spiral Progression

Important concepts are revisited at increasing levels of complexity.

**Example:** OOP
- **Phase 1:** Basic classes and simple inheritance
- **Phase 2:** Mixins, interfaces, abstract classes
- **Phase 6:** Architecture patterns (MVVM, Clean Architecture)

### 🔨 Project-Based Learning

Each phase ends with a practical project that **consolidates all knowledge**.

### 👥 Reading + Writing Code

- **Read** existing code in examples
- **Interpret** what it does
- **Modify** to experiment
- **Write** your own solutions

### ⚡ Fast Feedback

- Exercises with **automated tests**
- Immediate validation of your code
- Learn from errors quickly

---

<a name="additional-resources-en"></a>

## 📚 Additional Resources

### Official Documentation

- 📘 [Dart Language Tour](https://dart.dev/language)
- 📱 [Flutter Documentation](https://docs.flutter.dev/)
- 🎯 [Dart API Reference](https://api.dart.dev/)

### Online Tools

- 🎮 [DartPad](https://dartpad.dev/) - Interactive playground
- 📦 [Pub.dev](https://pub.dev/) - Package repository

### Communities

- 💬 [Flutterando Discord](https://discord.gg/flutterando)
- 🌐 [Flutter Brasil on Telegram](https://t.me/FlutterBR)
- 🐦 [#FlutterBrasil on Twitter](https://twitter.com/search?q=%23FlutterBrasil)

---

<a name="contributing-en"></a>

## 🤝 Contributing

This project is **open source** and **open to contributions**!

**Ways to contribute:**
- 🐛 Report bugs or errors
- 📝 Improve documentation
- ✨ Add new exercises
- 🌍 Help with translations
- 💡 Suggest improvements

**📄 [Read complete CONTRIBUTING.md →](./CONTRIBUTING.md)**

---

<a name="license-en"></a>

## 📜 License

This project is under **MIT** license.

This means you can:
- ✅ Use for educational purposes
- ✅ Use for commercial purposes
- ✅ Modify and distribute
- ✅ Use in private projects

**[See complete LICENSE →](./LICENSE)**

---

## 💬 Need Help?

- 📖 Read the [FAQ](./FAQ.md)
- 💬 Open an [Issue](../../issues)
- 🌐 Join the Flutterando community

---

## ⭐ Support the Project

If this project is helping you:
- ⭐ Star the repositories
- 🔄 Share with friends
- 💬 Give feedback
- 🤝 Contribute improvements

---

**🎯 Happy learning journey!**

---

<div align="center">

**Made with ❤️ for the Dart/Flutter community**

[Complete Roadmap](./ROADMAP.md) • [First Module](https://github.com/dart-learning-hub/01-dart-fundamentals-core) • [Contribute](./CONTRIBUTING.md)

</div>
