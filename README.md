# Agendor CRM - Mapa Interativo & Extrator

Painel interativo e sistema de visualização geográfica de dados extraídos do CRM Agendor.

## 🚀 Funcionalidades
- **Mapa Interativo com Google Maps**: Visualização em mapa com pinos inteligentes (clusterização) por estado e cidade.
- **Camadas de Mapa**: Google Maps (Ruas), Google Satélite (Híbrido) e OpenStreetMap.
- **Filtros Avançados**: Busca em tempo real por Nome, CNPJ, Razão Social, Contato, Cidade, Estado (UF), Categoria, Setor e Responsável.
- **Gaveta de Detalhes da Empresa**:
  - Dados cadastrais completos (CNPJ, Razão Social, Website, Telefones, Endereço).
  - Pessoas e Contatos com botão de WhatsApp direto e discador.
  - Negócios e Oportunidades com funil e valores em R$.
  - Linha do tempo de Histórico e Anotações.
  - Tarefas e agendamentos.
- **Edição em Tempo Real**:
  - Edição de informações da empresa, contatos e endereços.
  - Geocodificação automática de latitude e longitude pelo endereço.
  - Inserção de novas anotações diretamente no histórico.
  - Persistência no armazenamento local (`localStorage`) e exportação em JSON/CSV.

## 📂 Estrutura de Arquivos
- `mapa_interativo.html` / `index.html`: Aplicação Web completa.
- `dados_mapa.js` / `dados_mapa.json`: Dataset consolidado e relacional.
- `1_Empresas.csv`: Planilha de empresas extraídas.
- `2_Pessoas_Contatos.csv`: Planilha de contatos.
- `3_Negocios_Oportunidades.csv`: Planilha de negócios e oportunidades.
- `4_Historico_Anotacoes.csv`: Planilha de histórico de anotações.
- `5_Tarefas_Agendamentos.csv`: Planilha de tarefas agendadas.
- `Agendor_Original.sqlite`: Banco de dados SQLite original do backup.

## 💻 Como Executar
Basta abrir o arquivo `mapa_interativo.html` em qualquer navegador web.
