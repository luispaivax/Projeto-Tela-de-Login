# Tela de Login em React

Este projeto é uma **tela de login simples** construída com **React**. O objetivo é demonstrar a criação de um formulário funcional, com campos de entrada, ícones, botões e manipulação de estado usando hooks.

---

## Tecnologias utilizadas

- **React**: Biblioteca JavaScript para construção de interfaces de usuário.
- **React Icons (`react-icons`)**: Para adicionar ícones de usuário e senha aos campos de input.
- **CSS**: Para estilização da tela (`Login.css`).
- **Hooks do React (`useState`)**: Para controlar os estados dos campos de entrada (usuário e senha).

---

## Estrutura do projeto

- `Login.jsx`: Componente funcional que representa a tela de login.
- `Login.css`: Arquivo de estilos para personalizar aparência dos inputs, botão e layout.
- `App.js` ou outro componente principal: Importa e exibe o `Login`.

---

## Funcionalidades

1. **Campos de entrada**:
   - E-mail: `<input type="email" />`
   - Senha: `<input type="password" />`
   - Os valores digitados são armazenados nos estados `username` e `password` usando o hook `useState`.

2. **Ícones**:
   - `FaUser` ao lado do campo de e-mail.
   - `FaLock` ao lado do campo de senha.

3. **Checkbox "Lembre de mim"** e link "Esqueceu a senha?".

4. **Botão "Entrar"**:
   - Ao clicar, dispara a função `handleSubmit`.
   - Evita o comportamento padrão do formulário (`event.preventDefault()`).
   - Exibe um alert com os dados digitados (simulação de envio).

5. **Link de cadastro**: Redireciona para a página de registro (não implementada).
