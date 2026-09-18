# 🧮 Calculadora Simples em React

Uma aplicação de calculadora simples, moderna e responsiva construída em React com CSS Modules. Permite realizar as quatro operações matemáticas básicas com validações visuais e tratamento de erros amigável.

---

## 📸 Demonstração das Funcionalidades

- **Operações Básicas**: Soma (`+`), Subtração (`-`), Multiplicação (`*`) e Divisão (`/`).
- **Tratamento de Erros**:
  - Alerta visual caso algum campo não seja preenchido.
  - Mensagem de erro para tentativa de divisão por zero.
- **Interface Moderna**: Tema escuro (*Dark Mode*) suave com efeitos visuais ao passar o mouse e respostas dinâmicas de sucesso/erro.
- **Limpeza de Dados**: Botão dedicado para resetar todos os inputs e o resultado rapidamente.

---

## 🛠️ Tecnologias Utilizadas

- [React](https://react.dev/) - Biblioteca JavaScript para construção de interfaces.
- **CSS Modules** - Estilização modularizada e isolada por componente.
- **JavaScript (ES6+)** - Lógica e manipulação do estado da aplicação.

---

## 📂 Estrutura do Projeto

```text
src/
├── components/
│   ├── FormCalculadora.jsx        # Lógica do formulário e estados da calculadora
│   └── FormCalculadora.module.css # Estilos específicos do componente da calculadora
├── App.css                        # Estilos globais e background
├── App.jsx                        # Componente principal
└── main.jsx                       # Ponto de entrada do React
```

---

## 🚀 Como Executar o Projeto

### Pré-requisitos

Certifique-se de ter instalado em sua máquina:
- [Node.js](https://nodejs.org/) (versão 16 ou superior)
- `npm` ou `yarn`

### Passo a Passo

1. **Clone o repositório:**
   ```bash
   git clone https://github.com/seu-usuario/nome-do-repositorio.git
   ```

2. **Acesse a pasta do projeto:**
   ```bash
   cd nome-do-repositorio
   ```

3. **Instale as dependências:**
   ```bash
   npm install
   ```

4. **Inicie o servidor de desenvolvimento:**
   ```bash
   npm run dev
   # ou se estiver usando Create React App:
   # npm start
   ```

5. **Abra no navegador:**
   Acesse o endereço informado no terminal (geralmente `http://localhost:5173` ou `http://localhost:3000`).

---

## 📄 Licença

Este projeto está sob a licença [MIT](LICENSE) - sinta-se à vontade para usá-lo e modificá-lo como desejar!
