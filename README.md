# -Aplica-o-Simples-de-Cadastro-de-Usu-rios

✅ Checklist para o Sucesso do Projeto
🔧 1. Preparação do Ambiente
 Node.js instalado

 Editor de código (como VS Code)

 Git configurado

🧱 2. Estrutura do Projeto
 Criar projeto com Vite + React:

bash
Copiar
Editar
npm create vite@latest cadastro-usuarios --template react
 Instalar dependências:

bash
Copiar
Editar
cd cadastro-usuarios
npm install
npm install @mui/material @emotion/react @emotion/styled
🧩 3. Organização do Código
 Estrutura baseada em componentes: components/, pages/, utils/

 Separar telas:

Tela de Cadastro (Cadastro.jsx)

Tela de Usuários Cadastrados (Usuarios.jsx)

 Navegação com React Router:

bash
Copiar
Editar
npm install react-router-dom
🎨 4. Interface com Material-UI
 Utilizar componentes como TextField, Button, Card, AppBar, etc.

 Criar formulário funcional com validações básicas

💾 5. Persistência de Dados
 Armazenar os dados no Local Storage

 Ler dados ao iniciar e salvar ao cadastrar

 Atualizar a lista de usuários mesmo após refresh

⚙️ 6. Funcionalidades Obrigatórias
 Cadastro: formulário para inserir nome, e-mail, etc.

 Exibição de usuários: listagem dos dados cadastrados

 Layout Responsivo e acessível

🔀 7. Controle de Versão
 Inicializar repositório Git:

bash
Copiar
Editar
git init
 Usar commits semânticos (feat:, fix:, chore: etc.)

 Versionamento limpo e bem documentado

🚀 8. Deploy
 Subir o código no GitHub

 Fazer deploy gratuito com Vercel ou Netlify

 Configurar domínio personalizado (se necessário)

🎯 9. Objetivo Final
Entregar uma aplicação modular, funcional e intuitiva, com:

Código limpo e organizado

Boas práticas de React

UI elegante com Material-UI

Dados persistentes no navegador
