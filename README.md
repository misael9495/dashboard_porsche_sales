# 🏎️ Porsche — Painel de Performance de Vendas

Dashboard interativo desenvolvido para análise de desempenho comercial e visualização de dados de vendas de veículos Porsche.

O projeto apresenta informações de vendas por **modelo, ano, cidade, estado, preço e forma de pagamento**, permitindo ao usuário aplicar filtros e analisar os dados de forma visual e dinâmica.

## 📊 Sobre o projeto

O **Painel de Performance de Vendas** foi desenvolvido com uma interface inspirada na identidade visual da Porsche, utilizando uma estética moderna, escura e minimalista.

O dashboard possui uma base de **100 registros de vendas** e apresenta diferentes indicadores e gráficos para facilitar a análise dos dados.

## 🚀 Funcionalidades

* 📈 Indicadores gerais de vendas
* 💰 Cálculo da receita total
* 💵 Cálculo do ticket médio
* 🏆 Identificação do modelo líder
* 🏙️ Análise de vendas por cidade
* 🚘 Análise por família de modelos
* 📅 Análise por ano do modelo
* 💳 Análise por forma de pagamento
* 🔎 Filtro por modelo Porsche
* 📆 Filtro por ano
* 📍 Filtro por cidade
* 💳 Filtro por forma de pagamento
* 🔄 Botão para limpar os filtros
* 📋 Tabela completa dos registros
* ↕️ Ordenação dos dados da tabela
* 📱 Layout responsivo para diferentes tamanhos de tela

Os filtros são aplicados dinamicamente e atualizam os indicadores, gráficos e tabela de acordo com a seleção realizada.

## 📊 Indicadores

O dashboard apresenta quatro indicadores principais:

* **Total de vendas**
* **Receita total**
* **Ticket médio**
* **Modelo líder**

Os indicadores são recalculados automaticamente quando os filtros são alterados.

## 📈 Gráficos

O projeto utiliza a biblioteca **Chart.js** para gerar os gráficos.

### Mix de linhas por cidade

Apresenta as 10 cidades com maior volume de vendas e mostra a composição das vendas por família de veículos:

* 911
* 718
* Cayenne
* Macan
* Panamera
* Taycan

### Volume por ano

Exibe a quantidade de unidades vendidas de acordo com o ano do modelo.

### Forma de pagamento

Apresenta a distribuição das vendas de acordo com o método de pagamento utilizado.

## 🧰 Tecnologias utilizadas

* **HTML5**
* **CSS3**
* **JavaScript**
* **Chart.js 4.5.0**
* **Google Fonts**

  * Inter
  * Big Shoulders Display

A biblioteca Chart.js é utilizada para a criação dos gráficos interativos do dashboard.

## 🎨 Interface

A interface utiliza:

* Tema escuro;
* Detalhes em dourado;
* Tipografia moderna;
* Cards para indicadores;
* Gráficos interativos;
* Tabela de dados;
* Layout responsivo;
* Efeitos de interação nos elementos.

O projeto também possui suporte a `prefers-reduced-motion`, reduzindo as animações para usuários que possuem essa preferência de acessibilidade ativada.

## 📁 Estrutura do projeto

O projeto pode ser organizado da seguinte maneira:

```text
porsche-dashboard/
│
├── index.html
└── README.md
```

Atualmente, o código do dashboard está concentrado no arquivo HTML, contendo a estrutura da página, estilos CSS e lógica JavaScript.

## ▶️ Como executar

### 1. Clone o repositório

```bash
git clone https://github.com/SEU-USUARIO/porsche-dashboard.git
```

### 2. Entre na pasta

```bash
cd porsche-dashboard
```

### 3. Execute o projeto

Como o projeto utiliza HTML, CSS e JavaScript puro, basta abrir o arquivo:

```text
index.html
```

Você também pode utilizar uma extensão como **Live Server** no Visual Studio Code para executar o projeto localmente.

## 🔍 Funcionamento dos filtros

O usuário pode selecionar:

**Modelo Porsche**

Filtra os registros por um modelo específico.

**Ano do modelo**

Permite selecionar um ou mais anos.

**Cidade**

Permite pesquisar e selecionar uma cidade disponível na base.

**Forma de pagamento**

Filtra os registros de acordo com o método de pagamento.

Também existe o botão **Limpar filtros**, responsável por retornar o dashboard para a visualização completa dos dados.

## 📋 Dados

Cada registro possui informações como:

```text
Modelo
Ano
Preço
Forma de pagamento
Cidade
Estado
```

A tabela permite ordenar os registros clicando no cabeçalho de cada coluna.

## 🎯 Objetivo

O objetivo do projeto é demonstrar a utilização de **JavaScript para manipulação de dados**, criação de filtros, cálculos, geração de gráficos e atualização dinâmica de uma interface web.

O projeto também demonstra conceitos importantes de **Data Visualization** e construção de dashboards interativos.

## 💡 Aprendizados

Durante o desenvolvimento foram trabalhados conceitos como:

* Manipulação de arrays e objetos em JavaScript;
* Funções JavaScript;
* Eventos do DOM;
* Manipulação dinâmica do HTML;
* Filtros de dados;
* Ordenação de registros;
* Cálculos estatísticos básicos;
* Criação de gráficos com Chart.js;
* Responsividade com CSS;
* Organização de uma interface de dashboard;
* Visualização e análise de dados.


## 👨‍💻 Autor

**Misael Silva**

Projeto desenvolvido para fins de estudo e demonstração de conhecimentos em desenvolvimento web e visualização de dados.

---

⭐ Se este projeto foi útil para você, considere deixar uma estrela no repositório!
