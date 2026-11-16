# 📚 E-commerce de Livros (Bookstore)

![Angular](https://shields.io)
![TypeScript](https://shields.io)
![HTML5](https://shields.io)
![CSS3](https://shields.io)
![DIO](https://shields.io)

## 📖 Sobre o Projeto

Este projeto consiste em uma aplicação web de **E-commerce de Livros**, desenvolvida como parte de um desafio prático de bootcamp da **[Digital Innovation One (DIO)](https://dio.me "Digital Innovation One")**. 

O objetivo principal da aplicação é construir a interface front-end utilizando o framework **Angular**, estruturando a arquitetura de componentes, serviços e modelos de dados para consumir e exibir uma listagem de produtos (livros) vinda de uma API back-end, além de simular funcionalidades essenciais de uma loja virtual, como filtragem por preço e visualização de catálogo.

---

## ✨ Funcionalidades

- **Catálogo de Livros:** Exibição dinâmica dos livros disponíveis com título, preço, categoria, quantidade e imagem de capa.
- **Filtro de Produtos:** Possibilidade de filtrar os livros exibidos com base em faixas de valores (preço mínimo e máximo).
- **Integração com API REST:** Consumo de dados externos através de serviços HTTP (`HttpClient` do Angular) para buscar a lista de produtos.
- **Interface Responsiva:** Layout estruturado em componentes reutilizáveis (cabeçalho, barra de navegação, área de filtros, lista de itens e rodapé).

---

## 🛠️ Tecnologias Utilizadas

Com base na estrutura do repositório, o projeto utiliza as seguintes tecnologias e ferramentas:

- **[Angular](https://angular.dev "Angular oficial"):** Framework principal para construção da Single Page Application (SPA).
- **[TypeScript](https://typescriptlang.org "TypeScript oficial"):** Superset JavaScript utilizado para tipagem estática e organização do código.
- **HTML5 & CSS3:** Estruturação semântica e estilização das páginas e componentes.
- **[Karma](https://github.io "Karma test runner") & Jasmine:** Configuração pronta (`karma.conf.js` e `tsconfig.spec.json`) para execução de testes unitários.
- **[Node.js](https://nodejs.org "Node.js oficial") & npm:** Gerenciamento de pacotes e dependências (`package.json`).

---

## 📂 Estrutura de Arquivos

A organização principal do repositório segue o padrão de projetos Angular CLI:

```text
e-commerce_de_livros/
├── src/                  # Código-fonte da aplicação (componentes, serviços, modelos e assets)
├── angular.json          # Configurações de build, serve e testes do Angular CLI
├── karma.conf.js         # Configurações do executor de testes Karma
├── package.json          # Dependências do projeto e scripts de execução
├── package-lock.json     # Árvore exata de versões das dependências instaladas
├── tsconfig.json         # Configurações base do compilador TypeScript
├── tsconfig.app.json     # Configurações TypeScript específicas da aplicação
├── tsconfig.spec.json    # Configurações TypeScript específicas para os testes
└── README.md             # Documentação do projeto
```

---

## 🚀 Como Executar o Projeto Localmente

### Pré-requisitos

Antes de começar, certifique-se de ter instalado em sua máquina:
- [Node.js](https://nodejs.org "Download Node.js") (versão LTS recomendada)
- [Angular CLI](https://angular.devtools/cli "Angular CLI documentação") (`npm install -g @angular/cli`)
- [Git](https://git-scm.com "Download Git")

### Passo a passo

1. **Clone o repositório:**
   ```bash
   git clone https://github.com
   ```

2. **Acesse a pasta do projeto:**
   ```bash
   cd e-commerce_de_livros
   ```

3. **Instale as dependências:**
   ```bash
   npm install
   ```

4. **Configure o endpoint da API (se aplicável):**
   Verifique dentro da pasta `src/app/` o arquivo de serviço responsável pelas requisições HTTP e certifique-se de que a URL da API back-end de listagem de livros esteja ativa ou apontando para o seu servidor local.

5. **Inicie o servidor de desenvolvimento:**
   ```bash
   ng serve
   ```
   *(Ou utilize `npm start`)*

6. **Acesse no navegador:**
   Abra o navegador e acesse `http://localhost:4200/`. A aplicação será recarregada automaticamente caso você altere qualquer arquivo fonte.

---

## 🧪 Executando os Testes

Para rodar os testes unitários configurados via Karma, execute o comando:

```bash
ng test
```

---

## 🤝 Contribuição

Contribuições são sempre bem-vindas! Se você quiser melhorar este projeto:

1. Faça um **Fork** do projeto.
2. Crie uma **Branch** para sua modificação (`git checkout -b feature/MinhaMelhoria`).
3. Faça o **Commit** das suas alterações (`git commit -m 'Adiciona nova funcionalidade'`).
4. Faça o **Push** para a branch (`git push origin feature/MinhaMelhoria`).
5. Abra um **Pull Request**.

---

## 👨‍💻 Autor

Desenvolvido por **[marceloxm](https://github.com/marceloxm "Perfil GitHub marceloxm")** durante os estudos na **Digital Innovation One (DIO)**.

