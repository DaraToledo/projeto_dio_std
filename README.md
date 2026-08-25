Porsche Sales Intelligence

Dashboard interativa em HTML para análise de vendas Porsche por modelo, ano-modelo, cidade, período e método de pagamento.

O projeto foi construído a partir da planilha de vendas fornecida e utiliza uma interface visual inspirada na linguagem do site oficial da Porsche Brasil: minimalista, elegante, responsiva e orientada à leitura executiva dos dados.

Objetivo

Transformar a base de vendas em uma visão comercial simples e visual, capaz de responder perguntas como:

Quais são os modelos Porsche mais vendidos?

Quais modelos lideram as vendas em cada cidade?

Qual ano-modelo teve maior saída em determinado período?

Como os métodos de pagamento se distribuem?

Qual é o volume e o valor total das vendas?

Qual é o ticket médio das vendas filtradas?

Como as vendas evoluem ao longo dos meses?

Principais recursos

Filtros

A dashboard possui filtros interativos por:

Modelo Porsche

Model year

Cidade

Método de pagamento

Período da venda

Os componentes da página são recalculados automaticamente conforme a seleção dos filtros.

KPIs

A área executiva apresenta indicadores como:

Total de vendas

Receita total

Ticket médio

Modelo líder

Ano-modelo líder

Análises

A dashboard inclui:

Ranking dos modelos mais vendidos

Análise de vendas por cidade

Identificação dos carros mais populares em cada cidade

Matriz de ano-modelo por período

Distribuição dos métodos de pagamento

Evolução mensal das vendas

Insights automáticos de negócio de acordo com os filtros selecionados

Base de dados

A base original contém 100 registros de vendas e os seguintes campos:

Campo

Descrição

sale_id

Identificador da venda

sale_date

Data da venda

customer_name

Nome do cliente

porsche_model

Modelo Porsche vendido

model_year

Ano-modelo

sale_price

Valor da venda

vehicle_mileage

Quilometragem do veículo

payment_method

Método de pagamento

city

Cidade

state

Estado

salesperson

Vendedor

delivery_status

Status de entrega

Para a dashboard, os dados foram tratados e normalizados para reduzir diferenças de formatação em datas, anos-modelo, preços e métodos de pagamento.

O nome dos clientes não é utilizado na interface analítica da dashboard.

Como executar

Não é necessário instalar dependências, servidor local ou banco de dados.

Baixe o arquivo porsche_sales_dashboard.html.

Abra o arquivo em um navegador moderno, como Google Chrome, Microsoft Edge, Firefox ou Safari.

Utilize os filtros no topo da dashboard.

Clique em Limpar filtros para retornar à visão completa da base.

Estrutura

projeto/
├── porsche_sales_dashboard.html
└── README.md

A aplicação é autocontida: HTML, CSS, JavaScript e os dados necessários para a visualização estão incorporados no próprio arquivo.

Privacidade

A dashboard foi desenhada para análise comercial agregada.

Informações pessoais de clientes não são exibidas nos gráficos, rankings ou KPIs. Para publicação externa ou uso em produção, recomenda-se manter apenas os campos estritamente necessários à análise e evitar inserir dados pessoais no código distribuído ao navegador.

UI/UX

A direção visual prioriza:

aparência premium e editorial;

forte hierarquia tipográfica;

bastante espaço em branco;

contraste entre áreas claras e escuras;

cards simples;

navegação direta;

responsividade;

foco nos modelos e nos indicadores comerciais.

A referência visual é a linguagem institucional da Porsche, sem reproduzir ou depender de componentes proprietários do site oficial.

Tecnologias

HTML5

CSS3

JavaScript puro

Sem frameworks externos

Sem bibliotecas via CDN

Sem necessidade de conexão com a internet para executar a dashboard

Arquivo principal

porsche_sales_dashboard.html

Próximas evoluções possíveis

Importação dinâmica de novas planilhas

Comparação entre cidades e estados

Ranking de vendedores

Análise de estoque e status de entrega

Comparativo de veículos novos e seminovos por quilometragem

Metas comerciais

Exportação de gráficos e relatórios

Mapa geográfico de vendas

Integração com banco de dados ou API

Visão mobile dedicada
