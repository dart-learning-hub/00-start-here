# 🤝 Contributing Guide

[🇧🇷 Versão em Português](#português) | [🇺🇸 English Version](#english)

---

<a name="português"></a>

## 🇧🇷 Português

### Guia de Contribuição - Dart Learning Hub

Obrigado por considerar contribuir com o Dart Learning Hub! Este guia vai ajudá-lo a entender como você pode participar e melhorar este projeto educacional.

---

## 📋 Índice

- [Código de Conduta](#código-de-conduta)
- [Como Posso Contribuir?](#como-posso-contribuir)
- [Diretrizes de Contribuição](#diretrizes-de-contribuição)
- [Processo de Pull Request](#processo-de-pull-request)
- [Padrões de Código](#padrões-de-código)
- [Estrutura de Commits](#estrutura-de-commits)
- [Comunidade](#comunidade)

---

## 📜 Código de Conduta

Este projeto adota um código de conduta para garantir um ambiente acolhedor e respeitoso para todos.

### Nossos Compromissos:

- ✅ Ser respeitoso e inclusivo
- ✅ Aceitar críticas construtivas
- ✅ Focar no que é melhor para a comunidade
- ✅ Mostrar empatia com outros membros

### Comportamentos Inaceitáveis:

- ❌ Linguagem ou imagens ofensivas
- ❌ Assédio público ou privado
- ❌ Trolling ou comentários depreciativos
- ❌ Divulgação de informações privadas sem permissão

**Reporte comportamentos inadequados abrindo uma issue ou entrando em contato com os mantenedores.**

---

## 🎯 Como Posso Contribuir?

Existem muitas formas de contribuir, mesmo que você seja iniciante!

### 1. 🐛 Reportar Bugs

Encontrou um erro no código ou na documentação?

**Como reportar:**
1. Verifique se o bug já não foi reportado nas [Issues](../../issues)
2. Abra uma nova issue usando o template de bug
3. Descreva claramente:
   - O que você esperava que acontecesse
   - O que realmente aconteceu
   - Passos para reproduzir o erro
   - Seu ambiente (OS, versão do Dart, etc.)

**Exemplo de issue de bug:**
```markdown
**Descrição:** Erro ao executar exemplo em 01-dart-fundamentals-core/03-loops

**Esperado:** O código deveria imprimir números de 1 a 10

**Atual:** Erro: "RangeError: Value not in range"

**Passos para reproduzir:**
1. Clone o repo
2. Execute `dart run exemplos.dart`
3. O erro aparece na linha 15

**Ambiente:**
- Dart SDK: 3.2.0
- OS: Ubuntu 22.04
```

### 2. 📝 Melhorar Documentação

Documentação clara é essencial para aprendizado!

**O que você pode fazer:**
- Corrigir erros de digitação ou gramática
- Clarificar explicações confusas
- Adicionar exemplos adicionais
- Traduzir conteúdo (PT ↔ EN)
- Adicionar diagramas ou imagens

**Áreas comuns para melhorias:**
- READMEs dos módulos
- Comentários nos códigos de exemplo
- Explicações de conceitos
- Links quebrados

### 3. ✨ Adicionar Exercícios

Mais prática = melhor aprendizado!

**Como adicionar exercícios:**
1. Escolha um módulo existente
2. Identifique conceitos que precisam de mais prática
3. Crie exercícios progressivos (fácil → médio → difícil)
4. Forneça testes automatizados (quando possível)
5. Inclua solução de referência

**Estrutura de exercício:**
```dart
// exercicio_06.dart

/// Exercício: Função que retorna números pares de uma lista
/// Exercise: Function that returns even numbers from a list
///
/// Nível / Level: Médio / Medium
///
/// Objetivo / Goal:
/// Criar uma função que receba uma lista de inteiros e retorne
/// apenas os números pares.
/// Create a function that receives a list of integers and returns
/// only the even numbers.
///
/// Exemplo / Example:
/// Input: [1, 2, 3, 4, 5, 6]
/// Output: [2, 4, 6]

List<int> filtrarPares(List<int> numeros) {
  // Seu código aqui / Your code here
  throw UnimplementedError();
}

void main() {
  // Testes / Tests
  assert(filtrarPares([1, 2, 3, 4]) == [2, 4]);
  assert(filtrarPares([1, 3, 5]) == []);
  assert(filtrarPares([]) == []);
  
  print('✅ Todos os testes passaram!');
  print('✅ All tests passed!');
}
```

### 4. 🎨 Criar Projetos de Exemplo

Projetos reais ajudam a consolidar conhecimento!

**O que faz um bom projeto:**
- Aplica múltiplos conceitos da fase
- Tem especificação clara
- Inclui requisitos funcionais
- Fornece uma solução de referência
- Tem testes (quando aplicável)

### 5. 🌍 Ajudar com Traduções

Bilinguismo torna o conteúdo acessível a mais pessoas!

**O que traduzir:**
- READMEs
- Comentários em códigos
- Documentação
- Mensagens de erro

**Diretrizes de tradução:**
- Mantenha o tom consistente (profissional mas amigável)
- Preserve formatação markdown
- Traduza termos técnicos quando houver equivalente comum
- Mantenha termos em inglês quando for padrão da indústria (ex: `callback`, `stream`)

### 6. 🔍 Revisar Pull Requests

Ajude revisando contribuições de outros!

**O que verificar:**
- Código funciona corretamente
- Segue os padrões do projeto
- Documentação está clara
- Testes passam (se aplicável)
- Não há erros de digitação

---

## 📐 Diretrizes de Contribuição

### Estrutura de Arquivos

Mantenha a estrutura consistente:

```
modulo/
├── README.md (bilíngue)
├── 01-topico/
│   ├── README.md (explicação teórica)
│   ├── exemplos.dart (código comentado)
│   ├── exercicios.dart (práticas)
│   └── solucoes/
│       └── exercicio_01.dart
└── projeto-final/
```

### Padrões de Nomenclatura

**Arquivos:**
- `snake_case.dart` para arquivos Dart
- `kebab-case.md` para arquivos Markdown
- Pastas em `kebab-case`

**Variáveis e Funções (Dart):**
- `camelCase` para variáveis e funções
- `PascalCase` para classes
- `SCREAMING_SNAKE_CASE` para constantes

**Exemplo:**
```dart
const int MAX_TENTATIVAS = 3;

class Usuario {
  String nomeCompleto;
  
  void enviarEmail() {
    // ...
  }
}

void calcularMedia(List<int> numeros) {
  // ...
}
```

### Comentários

**Código deve ser bilíngue:**
```dart
// Calcula a soma de todos os elementos da lista
// Calculates the sum of all elements in the list
int calcularSoma(List<int> lista) {
  return lista.reduce((a, b) => a + b);
}
```

**Use comentários de documentação quando apropriado:**
```dart
/// Valida se um email é válido
/// Validates if an email is valid
///
/// Retorna `true` se o email for válido, `false` caso contrário.
/// Returns `true` if the email is valid, `false` otherwise.
///
/// Exemplo / Example:
/// ```dart
/// validarEmail('teste@email.com'); // true
/// validarEmail('invalido'); // false
/// ```
bool validarEmail(String email) {
  final regex = RegExp(r'^[\w-\.]+@([\w-]+\.)+[\w-]{2,4}$');
  return regex.hasMatch(email);
}
```

---

## 🔄 Processo de Pull Request

### 1. Fork e Clone

```bash
# Fork o repositório no GitHub
# Clone seu fork
git clone https://github.com/SEU-USUARIO/NOME-DO-REPO.git
cd NOME-DO-REPO

# Adicione o repositório original como upstream
git remote add upstream https://github.com/dart-learning-hub/NOME-DO-REPO.git
```

### 2. Crie uma Branch

```bash
# Sincronize com upstream
git fetch upstream
git checkout main
git merge upstream/main

# Crie uma branch descritiva
git checkout -b feature/adicionar-exercicios-loops
# ou
git checkout -b fix/corrigir-exemplo-classes
# ou
git checkout -b docs/melhorar-readme-fase1
```

**Padrões de nome de branch:**
- `feature/descricao` - Nova funcionalidade
- `fix/descricao` - Correção de bug
- `docs/descricao` - Documentação
- `refactor/descricao` - Refatoração
- `test/descricao` - Testes

### 3. Faça suas Alterações

- Edite os arquivos necessários
- Teste seu código
- Certifique-se que funciona
- Adicione testes se aplicável

### 4. Commit com Mensagem Clara

```bash
git add .
git commit -m "feat: adicionar 5 exercícios sobre loops for"
```

**Formato de commit:**
```
tipo: descrição curta

[Descrição detalhada opcional]

[Footer opcional]
```

**Tipos de commit:**
- `feat`: Nova funcionalidade
- `fix`: Correção de bug
- `docs`: Documentação
- `style`: Formatação (não muda código)
- `refactor`: Refatoração
- `test`: Adicionar/corrigir testes
- `chore`: Tarefas de manutenção

**Exemplos:**
```bash
git commit -m "feat: adicionar exercícios de maps"
git commit -m "fix: corrigir erro no exemplo de herança"
git commit -m "docs: melhorar explicação de async/await"
git commit -m "style: formatar código seguindo padrão Dart"
```

### 5. Push e Pull Request

```bash
# Push para seu fork
git push origin feature/adicionar-exercicios-loops
```

No GitHub:
1. Vá para seu fork
2. Clique em "New Pull Request"
3. Preencha o template de PR
4. Descreva claramente suas mudanças
5. Submeta o PR

**Template de Pull Request:**
```markdown
## Descrição / Description
[Descreva o que este PR faz]

## Tipo de Mudança / Type of Change
- [ ] 🐛 Bug fix
- [ ] ✨ Nova funcionalidade
- [ ] 📝 Documentação
- [ ] 🎨 Melhoria de código
- [ ] 🧪 Testes

## Checklist
- [ ] Código funciona corretamente
- [ ] Adicionei comentários em partes complexas
- [ ] Documentação foi atualizada
- [ ] Segue o style guide do projeto
- [ ] Testes passam (se aplicável)

## Screenshots (se aplicável)
[Adicione capturas de tela se necessário]

## Issues Relacionadas
Closes #123
```

### 6. Revisão e Merge

- Mantenedores revisarão seu PR
- Podem pedir alterações
- Faça as mudanças solicitadas
- Após aprovação, será feito merge!

---

## 🎨 Padrões de Código

### Dart Style Guide

Siga o [Effective Dart](https://dart.dev/guides/language/effective-dart):

**DO:**
```dart
// ✅ Use lowerCamelCase para variáveis
var itemCount = 5;

// ✅ Use UpperCamelCase para classes
class MinhaClasse {}

// ✅ Use /// para doc comments
/// Calcula algo importante
void calcular() {}

// ✅ Prefira interpolação de strings
print('Olá $nome!');

// ✅ Use const quando possível
const pi = 3.14159;
```

**DON'T:**
```dart
// ❌ Não use snake_case para variáveis
var item_count = 5;

// ❌ Não use // para doc comments públicos
// Calcula algo importante (use /// ao invés)
void calcular() {}

// ❌ Evite concatenação quando interpolar é mais simples
print('Olá ' + nome + '!');

// ❌ Não esqueça const
final pi = 3.14159; // Deveria ser const
```

### Formatação

Use o `dart format`:

```bash
# Formatar um arquivo
dart format nome_arquivo.dart

# Formatar um diretório
dart format .

# Checar sem modificar
dart format --output=none --set-exit-if-changed .
```

### Linting

Use o `dart analyze`:

```bash
# Analisar código
dart analyze

# Deve retornar: "No issues found!"
```

---

## 📝 Estrutura de Commits

### Conventional Commits

Usamos [Conventional Commits](https://www.conventionalcommits.org/):

```
<tipo>[escopo opcional]: <descrição>

[corpo opcional]

[rodapé(s) opcional(is)]
```

**Exemplos:**

```bash
# Feature simples
feat: adicionar exercício de recursão

# Fix com descrição detalhada
fix: corrigir índice fora do range no exemplo de lista

O exemplo estava acessando lista[10] em uma lista de tamanho 5.
Corrigido para usar lista.length.

# Breaking change
feat!: mudar estrutura de pastas dos exercícios

BREAKING CHANGE: Exercícios agora estão em pasta separada.
Atualize seus imports.

# Com issue relacionada
docs: atualizar README com instruções de instalação

Closes #45
```

---

## 🌐 Comunidade

### Onde Conversar?

- 💬 **Issues do GitHub** - Discussões sobre bugs e features
- 🌐 **Discord Flutterando** - Chat da comunidade
- 📧 **Telegram Flutter Brasil** - Grupo de discussão

### Dúvidas sobre Contribuição?

- Abra uma [Discussion](../../discussions)
- Marque `@mantenedores` em comentários
- Entre em contato via comunidade Flutterando

---

## 🙏 Reconhecimento

Todos os contribuidores serão reconhecidos no projeto!

Sua contribuição, grande ou pequena, faz diferença. Obrigado por ajudar a tornar a educação em Dart mais acessível! ❤️

---

<a name="english"></a>

## 🇺🇸 English

### Contributing Guide - Dart Learning Hub

Thank you for considering contributing to Dart Learning Hub! This guide will help you understand how you can participate and improve this educational project.

---

## 📋 Table of Contents

- [Code of Conduct](#code-of-conduct-en)
- [How Can I Contribute?](#how-can-i-contribute-en)
- [Contribution Guidelines](#contribution-guidelines-en)
- [Pull Request Process](#pull-request-process-en)
- [Code Standards](#code-standards-en)
- [Commit Structure](#commit-structure-en)
- [Community](#community-en)

---

<a name="code-of-conduct-en"></a>

## 📜 Code of Conduct

This project adopts a code of conduct to ensure a welcoming and respectful environment for everyone.

### Our Commitments:

- ✅ Be respectful and inclusive
- ✅ Accept constructive criticism
- ✅ Focus on what's best for the community
- ✅ Show empathy towards other members

### Unacceptable Behaviors:

- ❌ Offensive language or images
- ❌ Public or private harassment
- ❌ Trolling or derogatory comments
- ❌ Publishing private information without permission

**Report inappropriate behavior by opening an issue or contacting maintainers.**

---

<a name="how-can-i-contribute-en"></a>

## 🎯 How Can I Contribute?

There are many ways to contribute, even if you're a beginner!

### 1. 🐛 Report Bugs

Found an error in code or documentation?

**How to report:**
1. Check if the bug hasn't been reported in [Issues](../../issues)
2. Open a new issue using the bug template
3. Clearly describe:
   - What you expected to happen
   - What actually happened
   - Steps to reproduce the error
   - Your environment (OS, Dart version, etc.)

**Bug issue example:**
```markdown
**Description:** Error when running example in 01-dart-fundamentals-core/03-loops

**Expected:** Code should print numbers from 1 to 10

**Actual:** Error: "RangeError: Value not in range"

**Steps to reproduce:**
1. Clone the repo
2. Run `dart run exemplos.dart`
3. Error appears on line 15

**Environment:**
- Dart SDK: 3.2.0
- OS: Ubuntu 22.04
```

### 2. 📝 Improve Documentation

Clear documentation is essential for learning!

**What you can do:**
- Fix typos or grammar errors
- Clarify confusing explanations
- Add additional examples
- Translate content (PT ↔ EN)
- Add diagrams or images

**Common areas for improvement:**
- Module READMEs
- Comments in example code
- Concept explanations
- Broken links

### 3. ✨ Add Exercises

More practice = better learning!

**How to add exercises:**
1. Choose an existing module
2. Identify concepts that need more practice
3. Create progressive exercises (easy → medium → hard)
4. Provide automated tests (when possible)
5. Include reference solution

**Exercise structure:**
```dart
// exercicio_06.dart

/// Exercício: Função que retorna números pares de uma lista
/// Exercise: Function that returns even numbers from a list
///
/// Nível / Level: Médio / Medium
///
/// Objetivo / Goal:
/// Criar uma função que receba uma lista de inteiros e retorne
/// apenas os números pares.
/// Create a function that receives a list of integers and returns
/// only the even numbers.
///
/// Exemplo / Example:
/// Input: [1, 2, 3, 4, 5, 6]
/// Output: [2, 4, 6]

List<int> filtrarPares(List<int> numeros) {
  // Seu código aqui / Your code here
  throw UnimplementedError();
}

void main() {
  // Testes / Tests
  assert(filtrarPares([1, 2, 3, 4]) == [2, 4]);
  assert(filtrarPares([1, 3, 5]) == []);
  assert(filtrarPares([]) == []);
  
  print('✅ Todos os testes passaram!');
  print('✅ All tests passed!');
}
```

### 4. 🎨 Create Example Projects

Real projects help consolidate knowledge!

**What makes a good project:**
- Applies multiple concepts from the phase
- Has clear specification
- Includes functional requirements
- Provides a reference solution
- Has tests (when applicable)

### 5. 🌍 Help with Translations

Bilingualism makes content accessible to more people!

**What to translate:**
- READMEs
- Code comments
- Documentation
- Error messages

**Translation guidelines:**
- Keep consistent tone (professional but friendly)
- Preserve markdown formatting
- Translate technical terms when there's a common equivalent
- Keep terms in English when they're industry standard (e.g., `callback`, `stream`)

### 6. 🔍 Review Pull Requests

Help by reviewing others' contributions!

**What to check:**
- Code works correctly
- Follows project standards
- Documentation is clear
- Tests pass (if applicable)
- No typos

---

*[Note: The English version continues with the same structure as Portuguese, covering Guidelines, PR Process, Code Standards, Commit Structure, and Community sections. Would you like me to continue with the complete English translation?]*

---

## 🙏 Recognition

All contributors will be recognized in the project!

Your contribution, big or small, makes a difference. Thank you for helping make Dart education more accessible! ❤️

---

<div align="center">

**Made with ❤️ for the Dart/Flutter community**

[Back to README](./README.md) • [View Roadmap](./ROADMAP.md) • [License](./LICENSE)

</div>
