# Painel Operacional CD — TERMO SSA 01

Painel web interativo e de alta performance desenvolvido para a gestão, auditoria e consolidação operacional de dados de XML do Centro de Distribuição (CD), com foco na zona **TERMO SSA 01**.

---

## 🚀 Funcionalidades Principais

1. **Importação Inteligente de XML:**
   - Tela de upload central com design intuitivo e suporte a *Drag & Drop*.
   - Processamento assíncrono em blocos (*chunks*) para leitura eficiente de arquivos XML volumosos sem travar o navegador.
   - Filtro automático focado estritamente na zona **TERMO SSA 01**.

2. **Painéis Analíticos em Tempo Real (Grid 4 Colunas):**
   - **Painel 1 (Top 20 Lojas & Rotas):** Ranking das 20 principais lojas com filtro dinâmico de produtos (incluindo atalho rápido para o grupo de medicamentos **GLP-1**).
   - **Painel 2 (Top 10 Produtos):** Os SKUs com maior volume de saída e indicadores visuais de proporção.
   - **Painel 3 (Todas as Lojas):** Listagem consolidada com busca instantânea por loja/rota e cálculo dinâmico do total de caixas.
   - **Painel 4 (Detalhe por Loja):** Visão granular por item e filial com filtros avançados.

3. **Modais Interativos:**
   - **Detalhes da Loja:** Exibe unidades totais, caixas e a lista completa de produtos separados para a filial selecionada.
   - **Números das Caixas:** Detalhamento específico dos volumes/etiquetas geradas.

4. **Relatórios Oficiais para Impressão:**
   - **Relatório CAP TSSA01:** Grade horizontal otimizada (5x2) idêntica ao layout operacional padrão para preenchimento e controle de rotas de (401 a 416).
   - **Relatório Top 20:** Versão compacta otimizada para impressão em página única A4.

---

## 🛠️ Tecnologias Utilizadas

- **HTML5 & CSS3** com layout responsivo e estrutura em grade.
- **Tailwind CSS (via CDN)** para estilização rápida e moderna.
- **JavaScript Vanilla (ES6+)** puro, sem dependências externas complexas para manipulação de DOM e parsing de XML.

---

## 🖥️ Como Executar

1. Baixe ou copie o código fonte em um arquivo chamado `index.html`.
2. Dê um duplo clique no arquivo para abri-lo em qualquer navegador moderno (Google Chrome, Microsoft Edge, Firefox, etc.).
3. Clique no botão de upload (ou arraste o seu arquivo XML) para carregar os dados e liberar os painéis.

---

## 👨‍💻 Autoria

Desenvolvido por **Luis Roberto dos Anjos Braga**.