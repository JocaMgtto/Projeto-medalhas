# Meus Primeiros Projetos de Faculdade em Python

Este repositório contém dois projetos simples desenvolvidos em Python durante meu primeiro ano de faculdade. O objetivo desses trabalhos foi aplicar e praticar conceitos fundamentais de programação, como manipulação de dados, laços de repetição, funções, estruturas de dados e leitura de arquivos.

---

## 1. Sistema de Venda de Tickets (`joca2trab.py`)

### Descrição

Este projeto é um sistema de linha de comando que simula o caixa de um Restaurante Universitário (RU). O programa permite registrar vendas de tickets, calculando o valor com base no tipo de usuário (universitário, docente, colaborador, etc.), já que os preços são diferenciados.

Ao final, o sistema pode gerar um relatório completo com:
* O total de tickets vendidos.
* A receita total acumulada.
* Gráficos simples em modo texto que mostram a distribuição percentual dos tipos de usuários e das formas de pagamento utilizadas (Pix, Cartão, Dinheiro).



## 2. Análise de Medalhas Olímpicas (`trabalho2.py`)

### Descrição

Este projeto é um script de processamento de dados que lê um arquivo `.csv` contendo informações sobre medalhas olímpicas. O objetivo é analisar os dados, agregar as medalhas por país e gerar um quadro de medalhas ordenado.

O script realiza as seguintes etapas:
1.  **Leitura do Arquivo**: Lê os dados de um arquivo chamado `medals.csv`.
2.  **Processamento**: Agrega as medalhas de ouro, prata e bronze para cada país, consolidando os resultados masculinos e femininos.
3.  **Ordenação**: Classifica os países de acordo com o padrão olímpico oficial (primeiro por medalhas de ouro, depois por prata e, por fim, por bronze como critério de desempate).
4.  **Exibição**: Imprime no terminal uma tabela formatada com o quadro de medalhas final. Adicionalmente, exibe uma lista de países que ganharam medalhas em apenas um gênero (masculino ou feminino).



