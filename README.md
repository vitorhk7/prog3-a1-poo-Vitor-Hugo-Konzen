# Projeto A1 - Sistema de Cadastro de Usuários (PHP) - Vitor Hugo Konzen
5 FASE - Ciência da Computação, UNOESC SAO MIGUEL DO OESTE

## 📚 Sobre o projeto
Projeto desenvolvido para a atividade A1, com aplicação dos conteúdos aprendidos tanto em aula quanto com alguns tutoriais do youtube.

O sistema inclui:
- Cadastro e Login de Usuários
- Sessões para controle de acesso
- Segurança aplicada (validação de dados e criptografia de senha)
- Cadastro de Veículos atrelado ao usuário logado
- Estilização com CSS

---

## 🛠️ Tecnologias Utilizadas
- PHP 7.4+
- CSS3
- HTML5

---

## ⚙️ Como executar o projeto

1. Instale um servidor local (recomendado XAMPP, WAMP ou Laragon).

2. Coloque o projeto na pasta `htdocs` (ou equivalente):

3. Acesse pelo navegador: http://localhost/prog3-a1-poo-Vitor-Hugo-Konzen/index.php
---

4. Você poderá:
- Cadastrar novos usuários.
- Fazer login usando o email e senha cadastrados.
- Ser redirecionado para a área logada (Dashboard).
- Fazer logout.

---

## 📋 Funcionalidades

- **Cadastro de Usuários:**
- Formulário para nome, email e senha.
- Validação e sanitização de dados.
- Criação de objetos da classe `Usuario`.

- **Login de Usuários:**
- Verificação de credenciais dentro de um array.
- Login utilizando sessão PHP.
- Criação opcional de cookies para manter sessão ativa.

- **Área Logada (Dashboard):**
- Exibição de uma saudação personalizada para o usuário logado.

- **Logout:**
- Destruição da sessão e remoção do cookie, encerrando o acesso.

## 🎨 Estilo Visual

- **Verde para elementos principais.**
- **Verde para botões de sucesso.**
- **Branco para fundo e campos de entrada.**
- **Layout simples e responsivo.**


## 📚 Referências

Sistema de Cadastro/Login com PHP - Gustavo Neitzke
