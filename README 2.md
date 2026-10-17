# 🚗 Porsche Sales Dashboard com IA

Projeto desenvolvido para o desafio **Criando uma Dashboard da Porsche com Agentes de IA**, da DIO.

## 📌 Objetivo

Transformar a base sanitizada de vendas da Porsche em um dashboard interativo em HTML, permitindo analisar os dados de forma clara, visual e orientada a perguntas de negócio.

## ❓ Perguntas de negócio

Foram escolhidas três perguntas principais:

1. **Quais modelos geram mais receita?**  
   Permite identificar os veículos com maior participação no faturamento.

2. **Em quais cidades há maior volume de vendas?**  
   Ajuda a visualizar a distribuição geográfica das vendas.

3. **Quais métodos de pagamento concentram maior valor vendido?**  
   Permite entender como os clientes realizam os pagamentos e quais modalidades representam maior receita.

## 📊 Funcionalidades

O dashboard apresenta:

- Receita total;
- Quantidade de vendas;
- Ticket médio;
- Modelo líder em receita;
- Receita por modelo;
- Vendas por cidade;
- Receita por método de pagamento;
- Filtros por modelo, cidade, ano do modelo e método de pagamento;
- Tabela com os registros filtrados.

## 🧹 Tratamento da base

Antes da criação do dashboard, foram utilizadas as colunas sanitizadas disponibilizadas na base do desafio. Foram priorizados os campos padronizados de modelo, ano, preço, quilometragem, método de pagamento, cidade, estado e status de entrega. Dessa forma, diferenças de escrita e formatação presentes nos dados brutos não interferem nas análises.

## 🤖 Uso de IA

O ChatGPT foi utilizado como apoio para estruturar o dashboard em HTML, definir a organização visual, transformar as perguntas de negócio em indicadores e gráficos e implementar os filtros interativos.

### Prompt utilizado

> Crie um dashboard interativo em HTML utilizando a base sanitizada de vendas da Porsche. O dashboard deve apresentar indicadores de receita total, quantidade de vendas e ticket médio, além de responder a três perguntas de negócio: quais modelos geram mais receita, quais cidades possuem maior volume de vendas e quais métodos de pagamento concentram maior valor vendido. Inclua filtros por modelo, cidade, ano e método de pagamento. Utilize um visual escuro, organizado e responsivo.

Durante o desenvolvimento, o prompt foi refinado para melhorar a organização dos indicadores, a legibilidade dos gráficos e o funcionamento conjunto dos filtros.

## 📁 Arquivos

- `index.html` — dashboard interativo completo;
- `README.md` — documentação do projeto;
- arquivo `.xlsx` — base sanitizada utilizada no desafio.

## ▶️ Como visualizar

O projeto pode ser aberto diretamente pelo arquivo `index.html` ou publicado pelo **GitHub Pages**.

Para publicar no GitHub Pages:

1. Abra **Settings** no repositório.
2. Acesse **Pages**.
3. Em **Build and deployment**, escolha **Deploy from a branch**.
4. Selecione a branch `main` e a pasta `/ (root)`.
5. Clique em **Save**.
6. Aguarde a publicação e copie o endereço gerado pelo GitHub Pages.

## 🚀 Resultado

O resultado é um dashboard interativo que transforma os registros da base sanitizada em informações úteis para análise de vendas, permitindo filtrar os dados e responder às principais perguntas de negócio de forma rápida e visual.

> Projeto desenvolvido para fins educacionais como parte de um desafio da DIO.
