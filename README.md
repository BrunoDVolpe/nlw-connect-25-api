Ativar Frontend (web):
- Se primeira vez, instalar as dependências com: npm i
- Rodar aplicação: npm run dev

Ativar backend (api):
- Verificar que o docker está funcionando e que o serviço do postgreSQL está desativado no ctrl + alt + del para evitar erro de autenticação
- Subir o container dessa aplicação: docker compose up -d (aguarde o serviço funcionar)
- Se for primeiro acesso:
    - Instalar as dependências: npm i
    - Criar as tabelas: npx run db:migrate
- Rodar aplicação: npm run dev

Página de inscrição: http://localhost:3000/
Página ranking - Usuário 1: http://localhost:3000/invite/c1042b00-f369-484f-90ec-fa67e7870456
Docs: http://localhost:3333/docs