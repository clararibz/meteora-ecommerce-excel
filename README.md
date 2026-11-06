# Meteora Ecommerce – Controle de Produtos em Excel

Planilha desenvolvida em Excel para organizar e analisar o catálogo de produtos
da **Meteora**, uma loja de moda online fictícia. O projeto aplica fórmulas, tabelas,
tabela dinâmica e gráficos para transformar uma lista de produtos em informação
fácil de consultar.

## Sobre o projeto

A planilha reúne 20 itens de 10 produtos, divididos em três categorias
(Vestuário, Acessórios e Calçado). Para cada item são registrados tamanho,
preço unitário e quantidade. A partir disso, o preço com desconto e o valor
total são calculados automaticamente.

O desconto fica em uma única célula, então basta alterar o percentual para
atualizar todos os preços e totais.

## Estrutura da planilha

| Aba | Conteúdo |
|---|---|
| **Produtos** | Base de dados com fórmulas de desconto e valor total |
| **Tabela de Produtos** | Mesma base formatada como Tabela do Excel, com referências estruturadas e linha de totais |
| **Planilha3** | Tabela dinâmica com a soma de quantidade por produto |
| **Gráfico** | Gráfico de colunas "Soma de Quantidade por Produtos" |

## Fórmulas utilizadas

- **Preço com desconto:** `Preço Unitário − (Preço Unitário × Desconto)`
- **Valor total:** `Preço com Desconto × Quantidade`
- **Totais:** soma de preços, quantidades e valores na linha de totais

## Resultados

- **132** unidades em estoque
- **R$ 9.205,02** em valor total, já com 10% de desconto
- Produtos com maior quantidade: **Bermuda (40)**, **Camiseta Lisa (28)** e **Cinto (21)**
- Produto com maior preço unitário: **Óculos (R$ 399,90)**
- O Tênis tamanho 38 está com estoque zerado

## Recursos do Excel utilizados

- Fórmulas e referências absolutas (`$I$4`)
- Tabelas do Excel (referências estruturadas)
- Tabela dinâmica
- Gráfico de colunas
- Formatação de moeda e linha de totais

## Como usar

1. Baixe o arquivo `planilha/Meteora_Ecommerce.xlsx`.
2. Abra no Microsoft Excel (ou no LibreOffice Calc).
3. Altere o valor do desconto na célula **I4** para ver os preços e totais se atualizarem.
4. Se mudar as quantidades, atualize a tabela dinâmica em *Dados > Atualizar tudo*.

## 👤 Autor

Seu Nome – [LinkedIn](www.linkedin.com/in/maria-clara-ribeiro-silva-482183368) | [GitHub](https://github.com/clararibz)
