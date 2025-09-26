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

### Como Usar

1.  Certifique-se de ter o Python 3 instalado.
2.  Navegue até a pasta do projeto pelo terminal.
3.  Execute o seguinte comando:
    ```bash
    python joca2trab.py
    ```
4.  O programa apresentará um menu interativo. Siga as instruções para registrar vendas ou exibir o relatório final.

---

## 2. Análise de Medalhas Olímpicas (`trabalho2.py`)

### Descrição

Este projeto é um script de processamento de dados que lê um arquivo `.csv` contendo informações sobre medalhas olímpicas. O objetivo é analisar os dados, agregar as medalhas por país e gerar um quadro de medalhas ordenado.

O script realiza as seguintes etapas:
1.  **Leitura do Arquivo**: Lê os dados de um arquivo chamado `medals.csv`.
2.  **Processamento**: Agrega as medalhas de ouro, prata e bronze para cada país, consolidando os resultados masculinos e femininos.
3.  **Ordenação**: Classifica os países de acordo com o padrão olímpico oficial (primeiro por medalhas de ouro, depois por prata e, por fim, por bronze como critério de desempate).
4.  **Exibição**: Imprime no terminal uma tabela formatada com o quadro de medalhas final. Adicionalmente, exibe uma lista de países que ganharam medalhas em apenas um gênero (masculino ou feminino).

### Pré-requisitos

Para que o script funcione, é necessário ter um arquivo chamado `medals.csv` na mesma pasta do `trabalho2.py`. O arquivo deve conter os dados das medalhas em colunas separadas por vírgula.

### Como Usar

1.  Coloque o arquivo `medals.csv` no mesmo diretório do script.
2.  Execute o seguinte comando no terminal:
    ```bash
    python trabalho2.py
    ```
3.  O programa irá processar o arquivo e exibir o quadro de medalhas e as outras informações diretamente no terminal.
