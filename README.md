Projeto A1 - Sistema de Cadastro e Autenticação de Usuários
Desenvolvido por: Vitor Hugo Konzen
Disciplina: Programação III – UNOESC - SMO
Curso: Ciencias da Computação
📋 Descrição do Projeto
Este é um sistema simples de cadastro e login de usuários, desenvolvido inteiramente com PHP puro e Programação Orientada a Objetos (POO). O objetivo é aplicar conceitos de sessões, cookies, segurança, e organização de código em um projeto funcional.

🚀 Funcionalidades
✅ Cadastro de usuários com nome, e-mail e senha
✅ Login com validação de e-mail e senha
✅ Sessões para controle de acesso
✅ Cookie para lembrar e-mail do usuário (opcional)
✅ Dashboard com saudação personalizada
✅ Logout com destruição da sessão
✅ Interface estilizada com CSS
✅ Tratamento e sanitização de dados
💻 Estrutura de Diretórios
🧪 Tecnologias Utilizadas
PHP 7.4+
HTML5
CSS3
Orientação a Objetos
🔒 Segurança Implementada
Hash de senhas com password_hash()
Verificação com password_verify()
Proteção de rotas com sessão
Dados validados e sanitizados
🎨 Estilo Visual
Cores principais: preto e vermelho
Layout responsivo e centrado
Campos de input estilizados
Botões com hover animado
🛠️ Como Executar Localmente
Instale um servidor local como XAMPP, WAMP ou Laragon.
Clone este repositório ou copie os arquivos para a pasta htdocs do seu servidor.
Inicie o servidor Apache.
No navegador, acesse:
http://localhost/projeto-a1/login.php
Utilize o sistema normalmente:
Cadastre um novo usuário.
Faça login com e-mail e senha cadastrados.
Teste a área logada, o logout e o cookie de lembrar e-mail.
📌 Observações
Este projeto simula um banco de dados com array na memória.
Após cadastro, os dados ficam disponíveis apenas durante a sessão ativa.
📚 Referências
Documentação oficial do PHP
