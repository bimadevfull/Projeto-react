
<div align="center">

# 📝 Projeto React - Lista de Tarefas

### Um aplicativo moderno e elegante para gerenciar suas tarefas diárias

![React](https://img.shields.io/badge/React-18.2.0-61DAFB?style=for-the-badge&logo=react&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

[Sobre](#-sobre) •
[Funcionalidades](#-funcionalidades) •
[Instalação](#-instalação) •
[Como Usar](#-como-usar) •
[Tecnologias](#️-tecnologias) •
[Estrutura](#-estrutura-do-projeto) •
[Contribuir](#-como-contribuir)

</div>

---

## 📖 Sobre

O **Projeto React - Lista de Tarefas** é uma aplicação web moderna e intuitiva desenvolvida com React.js para ajudar você a organizar suas tarefas diárias de forma simples e eficiente. Com interface limpa, animações suaves e persistência de dados, nunca foi tão fácil manter o controle de suas atividades!

### 🎯 Objetivo

Fornecer uma ferramenta simples, rápida e bonita para gerenciamento de tarefas, perfeita para estudantes, profissionais e qualquer pessoa que deseja organizar melhor seu dia a dia.

---

## ✨ Funcionalidades

<table>
<tr>
<td>

### 📌 Gerenciamento de Tarefas
- ➕ **Adicionar** novas tarefas rapidamente
- ✅ **Marcar** tarefas como concluídas
- 🗑️ **Remover** tarefas individuais
- 🧹 **Limpar** todas as tarefas concluídas de uma vez

</td>
<td>

### 🎨 Interface e Experiência
- 🔍 **Filtros** inteligentes (Todas, Ativas, Concluídas)
- 💾 **Persistência** automática de dados
- 📊 **Estatísticas** em tempo real
- 🎭 **Animações** suaves e elegantes

</td>
</tr>
<tr>
<td>

### 📱 Recursos Adicionais
- 📅 **Data e hora** de criação das tarefas
- 💻 **Design responsivo** para todos os dispositivos
- 🎨 **Interface moderna** com gradientes
- ⌨️ **Atalhos de teclado** (Enter para adicionar)

</td>
<td>

### 🚀 Performance
- ⚡ **Carregamento rápido**
- 🔄 **Atualização em tempo real**
- 💪 **Sem necessidade de backend**
- 🌐 **100% offline** após o primeiro carregamento

</td>
</tr>
</table>

---

## 🚀 Instalação

### Pré-requisitos

Antes de começar, certifique-se de ter instalado em seu computador:

- **Node.js** (versão 14 ou superior) - [Download aqui](https://nodejs.org/)
- **npm** (geralmente vem com o Node.js) ou **yarn**
- Um editor de código (recomendo [VS Code](https://code.visualstudio.com/))

### Verificar instalação

```bash
node --version
npm --version
```

---

### 📥 Método 1: Instalação Rápida (Recomendado)

```bash
# 1️⃣ Criar o projeto React
npx create-react-app Projeto-react

# 2️⃣ Entrar na pasta do projeto
cd Projeto-react

# 3️⃣ Copiar todos os arquivos fornecidos para substituir os existentes
# (Substitua: App.js, App.css, index.js, index.css, package.json)
# (Crie: components/TodoItem.js, components/TodoItem.css)

# 4️⃣ Instalar dependências
npm install

# 5️⃣ Iniciar o servidor de desenvolvimento
npm start
```

### 📦 Método 2: Instalação Manual

```bash
# 1️⃣ Criar a pasta do projeto
mkdir Projeto-react
cd Projeto-react

# 2️⃣ Inicializar o projeto React
npx create-react-app .

# 3️⃣ Copiar os arquivos do projeto

# 4️⃣ Instalar dependências
npm install

# 5️⃣ Executar o projeto
npm start
```

### 🎉 Pronto!

O aplicativo será aberto automaticamente no seu navegador em:
```
http://localhost:3000
```

---

## 💡 Como Usar

### Interface Principal

```
┌─────────────────────────────────────────┐
│   📝 Minha Lista de Tarefas             │
│   Organize seu dia de forma simples     │
├─────────────────────────────────────────┤
│  [Digite uma tarefa...] [➕ Adicionar]  │
├─────────────────────────────────────────┤
│  [Todas] [Ativas] [Concluídas]          │
├─────────────────────────────────────────┤
│  ☐ Estudar React.js          [🗑️]       │
│  ☑ Fazer exercícios          [🗑️]       │
│  ☐ Ler documentação          [🗑️]       │
├─────────────────────────────────────────┤
│  Total: 3  |  Ativas: 2  |  Concluídas: 1│
│  [🗑️ Limpar Concluídas]                 │
└─────────────────────────────────────────┘
```

### Passo a Passo

1. **➕ Adicionar uma tarefa**
   - Digite o texto no campo de entrada
   - Pressione `Enter` ou clique no botão "Adicionar"

2. **✅ Marcar como concluída**
   - Clique no checkbox ao lado da tarefa
   - A tarefa ficará com aparência diferente

3. **🔍 Filtrar tarefas**
   - **Todas**: Mostra todas as tarefas
   - **Ativas**: Mostra apenas tarefas pendentes
   - **Concluídas**: Mostra apenas tarefas finalizadas

4. **🗑️ Remover tarefas**
   - Clique no ícone da lixeira para remover uma tarefa específica
   - Use "Limpar Concluídas" para remover todas de uma vez

5. **📊 Visualizar estatísticas**
   - Veja o total de tarefas, ativas e concluídas no rodapé

### ⌨️ Atalhos de Teclado

| Tecla | Ação |
|-------|------|
| `Enter` | Adicionar nova tarefa |
| `Tab` | Navegar entre elementos |

---

## 🛠️ Tecnologias

### Core

<div align="center">

| Tecnologia | Versão | Descrição |
|------------|--------|-----------|
| ![React](https://img.shields.io/badge/React-61DAFB?style=flat&logo=react&logoColor=black) | 18.2.0 | Biblioteca JavaScript para interfaces |
| ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black) | ES6+ | Linguagem de programação |
| ![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white) | 3 | Estilização e animações |
| ![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white) | 5 | Estrutura da aplicação |

</div>

### Recursos Utilizados

- **React Hooks**: `useState`, `useEffect`
- **LocalStorage API**: Persistência de dados no navegador
- **CSS Animations**: Transições e efeitos visuais
- **Responsive Design**: Layout adaptável para todos os dispositivos
- **Component Architecture**: Arquitetura modular e reutilizável

---

## 📂 Estrutura do Projeto

```
Projeto-react/
│
├── 📁 public/
│   ├── index.html              # HTML principal
│   └── favicon.ico             # Ícone do site
│
├── 📁 src/
│   ├── 📁 components/
│   │   ├── TodoItem.js         # Componente de item da tarefa
│   │   └── TodoItem.css        # Estilos do item
│   │
│   ├── App.js                  # Componente principal
│   ├── App.css                 # Estilos principais
│   ├── index.js                # Ponto de entrada
│   └── index.css               # Estilos globais
│
├── package.json                # Dependências do projeto
├── README.md                   # Documentação (você está aqui!)
└── .gitignore                  # Arquivos ignorados pelo Git
```

### 📋 Descrição dos Arquivos Principais

| Arquivo | Responsabilidade |
|---------|------------------|
| `App.js` | Lógica principal, gerenciamento de estado e filtros |
| `App.css` | Estilos gerais, layout e animações |
| `TodoItem.js` | Componente reutilizável para cada tarefa |
| `TodoItem.css` | Estilos específicos dos itens de tarefa |
| `index.js` | Renderização do app no DOM |

---

## 🎨 Personalização

### Alterar Cores

Edite o arquivo `src/App.css`:

```css
/* Gradiente de fundo */
background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);

/* Cor primária dos botões */
background: #667eea;

/* Cor de sucesso (tarefas concluídas) */
background: #66bb6a;

/* Cor de erro (remover tarefas) */
background: #ff6b6b;
```

### Adicionar Novos Recursos

O projeto está estruturado de forma modular. Para adicionar funcionalidades:

1. Crie novos componentes na pasta `src/components/`
2. Importe e use no `App.js`
3. Adicione estilos correspondentes

---

## 📱 Capturas de Tela

### Desktop
```
┌────────────────────────────────────────────────┐
│  🖥️  Interface completa e espaçosa             │
│  - Campo de entrada grande                     │
│  - Botões bem distribuídos                     │
│  - Lista com scroll suave                      │
└────────────────────────────────────────────────┘
```

### Mobile
```
┌──────────────────┐
│  📱  Responsivo   │
│  - Menu vertical │
│  - Touch-friendly│
│  - Scroll suave  │
└──────────────────┘
```

---

## 🧪 Scripts Disponíveis

No diretório do projeto, você pode executar:

### `npm start`
```bash
npm start
```
Inicia o servidor de desenvolvimento em modo watch.
Abra [http://localhost:3000](http://localhost:3000) para visualizar.

### `npm run build`
```bash
npm run build
```
Cria uma versão otimizada para produção na pasta `build/`.

### `npm test`
```bash
npm test
```
Inicia o test runner em modo interativo.

### `npm run eject`
```bash
npm run eject
```
⚠️ **Atenção**: Esta operação é irreversível!

---

## 🐛 Solução de Problemas

### Problema: Porta 3000 já está em uso

```bash
# Windows
netstat -ano | findstr :3000
taskkill /PID <PID> /F

# Mac/Linux
lsof -ti:3000 | xargs kill -9
```

### Problema: Erro ao instalar dependências

```bash
# Limpar cache do npm
npm cache clean --force

# Deletar node_modules e reinstalar
rm -rf node_modules package-lock.json
npm install
```

### Problema: Página em branco

1. Verifique o console do navegador (F12)
2. Confirme que todos os arquivos foram copiados corretamente
3. Execute `npm start` novamente

---

## 🤝 Como Contribuir

Contribuições são sempre bem-vindas! Se você quer melhorar este projeto:

### Passo a Passo

1. **Fork** este repositório
2. **Clone** seu fork:
   ```bash
   git clone https://github.com/seu-usuario/Projeto-react.git
   ```
3. **Crie** uma branch para sua feature:
   ```bash
   git checkout -b minha-nova-feature
   ```
4. **Commit** suas mudanças:
   ```bash
   git commit -m "Adiciona nova feature incrível"
   ```
5. **Push** para a branch:
   ```bash
   git push origin minha-nova-feature
   ```
6. Abra um **Pull Request**

### 💡 Ideias para Contribuir

- 🌍 Adicionar suporte para múltiplos idiomas
- 🎨 Criar temas claro/escuro
- 📅 Adicionar datas de vencimento
- 🏷️ Sistema de tags/categorias
- 🔔 Notificações de tarefas
- 📤 Exportar/importar tarefas
- 🔐 Sistema de autenticação
- ☁️ Sincronização com nuvem

---

## 📚 Recursos de Aprendizado

### Para Iniciantes em React

- 📖 [Documentação Oficial do React](https://react.dev/)
- 🎥 [React para Iniciantes - Curso Gratuito](https://www.youtube.com/results?search_query=react+para+iniciantes)
- 📝 [Tutorial Interativo do React](https://react-tutorial.app/)

### Conceitos Utilizados neste Projeto

- **Hooks**: useState, useEffect
- **Props**: Passagem de dados entre componentes
- **Event Handling**: Manipulação de eventos
- **Conditional Rendering**: Renderização condicional
- **Lists and Keys**: Renderização de listas
- **LocalStorage**: Persistência de dados

---

## 📄 Licença

Este projeto está sob a licença **MIT**.

```
MIT License

Copyright (c) 2025 bimadevfull

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

---

## 👨‍💻 Autor

<div align="center">

### bimadevfull

[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/bimadevfull)

**Desenvolvedor apaixonado por criar experiências web incríveis!**

</div>

---

## 🙏 Agradecimentos

- 💙 Comunidade React por todo o suporte
- 🎨 Design inspirado em aplicativos modernos de produtividade
- ☕ Café, muito café...

---

## 📞 Contato e Suporte

Tem dúvidas ou sugestões? Entre em contato:

- 📧 **Email**: [seu-email@example.com](mailto:seu-email@example.com)
- 💬 **Issues**: Abra uma issue neste repositório
- 🌟 Se este projeto te ajudou, deixe uma ⭐ no repositório!

---

<div align="center">

### 🌟 Se você gostou deste projeto, não esqueça de dar uma estrela! 🌟

**Feito com ❤️ e React**

![React](https://img.shields.io/badge/Made%20with-React-61DAFB?style=for-the-badge&logo=react&logoColor=white)

---

**[⬆ Voltar ao topo](#-projeto-react---lista-de-tarefas)**

</div>
