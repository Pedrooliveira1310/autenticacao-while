🔐 Terminal de Alta Segurança - Cyber-SENAI
📌 Descrição

Este projeto consiste em um sistema simples de autenticação de usuários desenvolvido com HTML, CSS e JavaScript.
O objetivo é simular um terminal de acesso seguro com controle de tentativas de login.

O sistema permite que usuários façam login com credenciais pré-definidas e bloqueia o acesso após múltiplas tentativas inválidas.

🚀 Funcionalidades
✔️ Campo de entrada para usuário e senha
✔️ Validação de login com lista interna de usuários
✔️ Controle de tentativas (máximo de 3)
✔️ Mensagens de feedback em tempo real:
Acesso liberado
Login inválido
Sistema bloqueado
✔️ Bloqueio automático do sistema após exceder tentativas
✔️ Desativação dos campos após bloqueio
🧠 Lógica do Sistema
Existe uma lista fixa de usuários cadastrados no código:
const users = [
  { username: "user1", password: "pass1" },
  ...
];
O sistema:
Recebe os dados digitados
Verifica se correspondem a algum usuário
Se correto → acesso liberado
Se incorreto → reduz tentativas
Após 3 erros → bloqueia o sistema
🔒 Regras de Segurança
Número máximo de tentativas: 3
Após atingir o limite:
Sistema é bloqueado
Campos são desativados
Usuário deve procurar suporte
🛠️ Tecnologias Utilizadas
HTML5 → Estrutura da página
CSS3 → Estilização básica
JavaScript → Lógica de autenticação
📂 Estrutura do Projeto
📁 projeto
 └── index.html

Todo o código está contido em um único arquivo HTML, incluindo:

Estrutura
Estilo
Script
▶️ Como Executar
Baixe ou copie o código
Salve como index.html
Abra no navegador
🧪 Usuários para Teste

Você pode usar os seguintes exemplos:

Usuário	Senha
user1	pass1
user5	pass5
user10	pass10
📈 Possíveis Melhorias
🔐 Criptografia de senha
📦 Integração com banco de dados
🌐 Backend (Node.js, PHP, etc.)
🎨 Interface mais moderna
📊 Registro de tentativas (log)
