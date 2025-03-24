# Azure Cognitive Search: Utilizando AI Search para Indexação e Consulta de Dados

## Configuração do Azure Cognitive Search

### 1. Criar um Serviço de Pesquisa no Azure
4. Selecione uma região e um grupo de recursos.
5. Clique em **Criar** e aguarde a implantação.

### 2. Criar um Índice de Pesquisa
1. No portal do Azure, abra o serviço criado e selecione **Índices**.
2. Clique em **Adicionar índice**.
3. Defina o esquema do índice, incluindo:
   - Nome do índice.
   - Campos (chave primária, campos pesquisáveis, filtráveis, ordenáveis).
4. Salve o índice.

### 3. Criar um Data Source
1. Acesse **Fontes de Dados** dentro do Azure Cognitive Search.
2. Selecione a fonte de dados (SQL Server, Blob Storage, Cosmos DB, etc.).
3. Configure as credenciais e selecione os dados a serem indexados.
4. Salve a fonte de dados.

### 4. Criar um Indexador
1. Acesse **Indexadores** e clique em **Adicionar indexador**.
2. Escolha a fonte de dados criada anteriormente.
3. Configure a frequência de indexação (manual ou automática).
4. Execute o indexador para popular o índice.

### 5. Consultar os Dados Indexados
1. Utilize o **Azure Search Explorer** para testar consultas.
2. Execute consultas REST utilizando o endpoint de pesquisa.
3. Integre a pesquisa ao seu aplicativo usando SDKs do Azure.

## Aprendizados
Durante o processo de configuração e utilização do Azure Cognitive Search, alguns dos principais aprendizados incluem:
- **Definição adequada do esquema do índice** é essencial para consultas eficientes.
- **A escolha correta da fonte de dados** impacta diretamente na performance e relevância das buscas.
- **A integração com outros serviços do Azure**, como **AI Search**, **Cognitive Services** e **Power BI**, expande as possibilidades de análise e busca inteligente.
- **Monitoramento e ajustes contínuos** são necessários para otimizar a indexação e melhorar os resultados da busca ao longo do tempo.

---

