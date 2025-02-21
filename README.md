## CLEBER TRACKER

## SOBRE O PROJETO

O CLEBER TRACKER é um projeto desenvolvido com Vue 3, TypeScript e TailwindCSS, visando aprimorar funcionalidades do Vue, incluindo computed properties, watchers e Composition API, assim como melhorar a estilização com TailwindCSS.

## TECNOLOGIAS UTILIZADAS

- Vue 3
- TypeScript
- TailwindCSS
- SASS
- ESLint e Prettier

## INSTALAÇÃO E EXECUÇÃO

### 1. CLONE O REPOSITÓRIO

```sh
git clone https://github.com/cleber/cleber-tracker.git
cd cleber-tracker
```

### 2. INSTALE AS DEPENDÊNCIAS

```sh
yarn install
# OU
npm install
```

### 3. EXECUTE O PROJETO EM AMBIENTE DE DESENVOLVIMENTO

```sh
yarn serve
# OU
npm run serve
```
O projeto estará disponível em: http://localhost:8080/

### 4. BUILD PARA PRODUÇÃO

```sh
yarn build
# OU
npm run build
```
Os arquivos compilados estarão na pasta /dist.

### 5. ANALISE PROBLEMAS DE LINT

```sh
yarn lint
# OU
npm run lint
```

## ESTRUTURA DO PROJETO

```
cleber-tracker/
│── public/
│   ├── favicon.ico      # Ícone do projeto
│   ├── index.html       # Arquivo HTML principal
│
│── src/
│   ├── assets/          # Arquivos estáticos (imagens, fontes, etc.)
│   │   ├── logo.webp    # Logo do projeto
│   ├── components/      # Componentes Vue reutilizáveis
│   │   ├── Barralateral.vue
│   │   ├── Botao.vue
│   │   ├── Box.vue
│   │   ├── Cronometro.vue
│   │   ├── Formulario.vue
│   │   ├── Tarefa.vue
│   │   ├── Temporizador.vue
│   ├── interfaces/      # Definições de tipos TypeScript
│   ├── App.vue          # Componente raiz do Vue
│   ├── Main.ts          # Arquivo principal do app
│   ├── Shims-vue.d.ts   # Configuração do TypeScript para Vue
│   ├── Style.scss       # Arquivo global de estilos
│
│── config/              # Arquivos de configuração
│   ├── postcss.config.js
│   ├── tailwind.config.ts
│   ├── tsconfig.json
│   ├── vue.config.js
│
│── .browserslistrc      # Configuração de compatibilidade de navegadores
│── .eslintrc.js         # Configuração do ESLint
│── .gitignore           # Arquivos ignorados pelo Git
│── babel.config.js      # Configuração do Babel
│── package.json         # Dependências e scripts
│── package-lock.json    # Lockfile do npm
│── README.md            # Documentação do projeto
```

## FUNCIONALIDADES IMPLEMENTADAS

- Uso de computed properties para cálculo dinâmico de valores.
- Watchers para monitorar mudanças de estado.
- Composição de componentes para reutilização de código.
- Estilização rápida e responsiva com TailwindCSS.

## COMPONENTES VUE PERSONALIZADOS

- **Barralateral.vue**: Barra lateral de navegação.
- **Botao.vue**: Componente de botão reutilizável.
- **Box.vue**: Caixa para exibição de informações.
- **Cronometro.vue**: Componente de cronômetro.
- **Formulario.vue**: Formulário para entrada de dados.

TAREFA.VUE: GERENCIADOR DE TAREFAS.

TEMPORIZADOR.VUE: TEMPORIZADOR CUSTOMIZADO.

LINTING COM ESLINT E TYPESCRIPT PARA CÓDIGO MAIS LIMPO E PADRONIZADO.
