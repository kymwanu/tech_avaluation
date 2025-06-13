# Documentação dos Projetos

Esta documentação reúne instruções para três projetos distintos, abrangendo desde uma aplicação Flutter até interfaces web modernas com Vue.js e dashboards sofisticados.

---

## 1. Demo Project

### Visão Geral

Aplicativo Flutter multiplataforma com navegação por abas, exibição de produtos e categorias, e interface visual customizada. Ideal para e-commerce, catálogos ou demonstrações de UI.

### Instruções de Instalação

1. **Pré-requisitos:**  
   - [Flutter SDK](https://flutter.dev/docs/get-started/install)
   - Android Studio/Xcode (para emuladores/dispositivos)
   - Dart

2. **Clone o repositório:**
   ```bash
   git clone <URL_DO_REPOSITORIO>
   cd demo_project
   ```

3. **Instale as dependências:**
   ```bash
   flutter pub get
   ```

4. **Execute o aplicativo:**
   ```bash
   flutter run
   ```

### Estrutura Recomendada

- `/lib`: Código principal Flutter
  - `main.dart`: Ponto de entrada
  - `/screens`: Telas do app
  - `/widgets`: Componentes reutilizáveis

---

## 2. Landing Page Tech Evaluation

### Visão Geral

Landing page moderna e responsiva com Quasar Framework (Vue.js), voltada para apresentação institucional, funcionalidades e contato.

### Instruções de Instalação

1. **Pré-requisitos:**  
   - [Node.js](https://nodejs.org/)
   - [Yarn](https://yarnpkg.com/) ou npm

2. **Clone o repositório:**
   ```bash
   git clone <URL_DO_REPOSITORIO>
   cd landing-page-tech-evaluation
   ```

3. **Instale as dependências:**
   ```bash
   yarn install
   # ou
   npm install
   ```

4. **Execute em modo desenvolvimento:**
   ```bash
   quasar dev
   ```

5. **Para build de produção:**
   ```bash
   quasar build
   ```

### Estrutura Recomendada

- `/src`
  - `/pages`: Páginas principais
  - `/components`: Componentes Vue reutilizáveis

---

## 3. Dashboard Web – Tech Avaluation

### Visão Geral

Dashboard web moderna para métricas financeiras, histórico de pagamentos e transações. Inclui navegação lateral, suporte a temas e gráficos dinâmicos.

### Instruções de Instalação

1. **Pré-requisitos:**  
   - [Node.js](https://nodejs.org/)
   - [Yarn](https://yarnpkg.com/) ou npm

2. **Clone o repositório:**
   ```bash
   git clone <URL_DO_REPOSITORIO>
   cd dashboard-web-tech-aval
   ```

3. **Instale as dependências:**
   ```bash
   yarn install
   # ou
   npm install
   ```

4. **Execute em modo desenvolvimento:**
   ```bash
   yarn dev
   # ou
   npm run dev
   ```

5. **Build de produção:**
   ```bash
   yarn build
   # ou
   npm run build
   ```

### Estrutura Recomendada

- `/src`
  - `/components`: Componentes do dashboard
  - `/views`: Páginas do dashboard
  - `/store`: Gerenciamento de estado

---

## Dicas Gerais

- Sempre consulte o arquivo `package.json` ou `pubspec.yaml` para dependências específicas.
- Cada projeto pode conter instruções adicionais em seu próprio README.

---

> Substitua `<URL_DO_REPOSITORIO>` pelo endereço correto de cada projeto.
