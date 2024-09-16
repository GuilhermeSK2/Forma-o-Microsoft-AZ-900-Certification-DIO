# Guia para Criação e Conexão a um Banco de Dados no Azure

![png-clipart-microsoft-azure-sql-database-microsoft-sql-server-cloud-computing-blue-text-removebg-preview](https://github.com/user-attachments/assets/4fa207a6-ee36-4b25-a2f9-115ee1a47e84)

## 1. Crie sua Conta no Azure

Se você ainda não tem uma conta no Azure, acesse [portal.azure.com](https://portal.azure.com) e siga as etapas para criar a sua. Após isso, você estará pronto para continuar.

## 2. Acesse o Portal do Azure

Após fazer login, vá ao painel principal. Pesquise por "SQL Database" na barra de busca ou clique em **"Criar um recurso"** e selecione **"Banco de Dados"**.

## 3. Criando o Banco de Dados

1. **Iniciar Criação**: Clique em **"Criar"** para iniciar o assistente de criação do banco de dados.
2. **Configurações**:
   - **Nome**: Escolha um nome único para o banco de dados.
   - **Assinatura**: Selecione a assinatura ativa.
   - **Grupo de Recursos**: Escolha um grupo existente ou crie um novo.
   - **Servidor**: Selecione ou crie um novo servidor, informando o nome, localização e credenciais de administrador.

## 4. Configurações do Banco de Dados

Escolha o tipo de banco de dados, como SQL Database ou Cosmos DB. Neste guia, criaremos um **SQL Database**.

- **Plano de Tarifação**: Selecione o plano que melhor se adapta às suas necessidades. Para testes, o plano gratuito pode ser uma boa opção.
- **Backup e Recuperação**: Configure as opções de backup para garantir a segurança dos seus dados.

## 5. Revisão e Criação

Revise todas as configurações e clique em **"Criar"**. O processo pode levar alguns minutos enquanto o banco de dados é provisionado.

## 6. Conexão ao Banco de Dados

Após a criação, conecte-se ao banco de dados utilizando ferramentas como SQL Server Management Studio (SSMS) ou Azure Data Studio, usando as credenciais que você definiu.

## 7. Explore seu Banco de Dados

Com o banco de dados pronto, você pode começar a adicionar dados, executar consultas e explorar as funcionalidades do Azure SQL Database.
