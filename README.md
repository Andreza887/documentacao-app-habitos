# 📱 Aplicativo de Hábitos

Este repositório contém o desenvolvimento do **Aplicativo de Hábitos**, cuja proposta é auxiliar usuários na criação, acompanhamento e manutenção de hábitos diários de maneira simples e prática.

O projeto inclui:
- Documentação estruturada (PDF)
- Organização seguindo boas práticas de DevOps
- Fluxo GitFlow simplificado
- Branches específicas para features
- Integração e entrega contínua (CI/CD) simuladas via Pull Requests

---

## 📌 Objetivo do Aplicativo

O objetivo do sistema é permitir que usuários:
- Cadastrem hábitos
- Marquem hábitos como concluídos diariamente
- Visualizem histórico e progresso
- Recebam notificações (versão futura)
- Acompanhem estatísticas semanais

---

# 🛠️ Tecnologias Utilizadas

- Git e GitHub (controle de versão e DevOps)
- Documentação em PDF
- (Adicionar as tecnologias do app quando implementado — Ex: Flutter, Dart etc.)
# 📱 Aplicativo de Hábitos

Este repositório contém o desenvolvimento do **Aplicativo de Hábitos**, cuja proposta é auxiliar usuários na criação, acompanhamento e manutenção de hábitos diários de maneira simples e prática.

O projeto inclui:
- Documentação estruturada (PDF)
- Organização seguindo boas práticas de DevOps
- Fluxo GitFlow simplificado
- Branches específicas para features
- Integração e entrega contínua (CI/CD) simuladas via Pull Requests

---

## 📌 Objetivo do Aplicativo

O objetivo do sistema é permitir que usuários:
- Cadastrem hábitos
- Marquem hábitos como concluídos diariamente
- Visualizem histórico e progresso
- Recebam notificações (versão futura)
- Acompanhem estatísticas semanais

---

# 🛠️ Tecnologias Utilizadas

- Git e GitHub (controle de versão e DevOps)
- Documentação em PDF
- (Adicionar as tecnologias do app quando implementado — Ex: Flutter, Dart etc.)

---

# 🗂️ Estrutura do Repositório

├── docs/ → PDFs da documentação
├── src/ → Código-fonte (quando implementado)
├── develop/ → Branch de desenvolvimento
├── main/ → Branch principal (produção)
└── features/ → Branches de funcionalidades

# 🗂️ Estrutura do Repositório

---

# 🔀 Fluxo de Versionamento (GitFlow Simplificado)

O projeto utiliza um fluxo baseado em **GitFlow** adaptado:

### 🟦 Branch principal: `main`
Versão estável e final do código.

### 🟩 Branch de desenvolvimento: `develop`
Onde as funcionalidades são integradas antes de ir para main.

### 🟧 Branches de funcionalidade: `feature-*`
Contêm implementações separadas, como por exemplo:
- `feature-habitos`
- `feature-login`

---

# 🔄 Integração Contínua (CI)

A CI foi realizada com:

base: develop
compare: feature-habitos

🟢 Resultado:  
O conteúdo da feature foi integrado na branch develop.

O professor pode verificar isso na aba **Pull Requests → Closed**.

---

# 🚀 Entrega Contínua (CD)

A CD foi realizada com:

base: main
compare: develop

🟢 Resultado:  
A branch main recebeu o conteúdo final do desenvolvimento.

Esse fluxo representa a entrega final do sistema.

---

# 📁 Documentação

A documentação completa está disponível na pasta:

/docs

Contém:
- Requisitos funcionais e não funcionais
- Regras de negócio
- Diagramas UML
- Relatórios
- Estrutura do código (SRC)
- Outros documentos

---

# 👩‍💻 Desenvolvedora

**Andreza Rodrigues de Oliveira**

---

# ✅ Status da Entrega

- [x] Branch main criada
- [x] Branch develop criada
- [x] Branches feature criadas
- [x] PR de CI (feature → develop)
- [x] PR de CD (develop → main)
- [x] Documentação em PDF gerada
- [ ] Código do aplicativo (em andamento)


