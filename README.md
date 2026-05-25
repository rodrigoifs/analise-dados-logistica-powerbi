# 🚚 Projeto: Análise de Dados de Logística com Power BI

## 📋 Descrição do Projeto
Este projeto consiste no desenvolvimento de um dashboard estratégico focado em Inteligência Logística (Supply Chain Analytics). O objetivo principal é centralizar os dados de fluxos de envios para monitorar o cumprimento de prazos, identificar os canais mais eficientes, analisar a sazonalidade e avaliar o desempenho operacional de equipes e parceiros.

O projeto foi construído como o Mini-Projeto 4 durante a minha formação na **Data Science Academy (DSA)**.

---

## 🎯 Desafio de Negócio
Uma empresa com alto volume de distribuição precisava de uma ferramenta analítica para otimizar suas operações de transporte e responder a perguntas complexas:
* Qual o volume total de entregas e quantas foram efetivamente concluídas no prazo?
* Quais regiões ou equipes apresentam maior eficiência operacional?
* Como se comporta a sazonalidade de envios ao longo dos meses e quais cidades concentram os maiores índices de atraso?
* Quem são os parceiros logísticos/vendedores com as melhores avaliações (*ratings*) de serviço?

---

## 🛠️ Tecnologias e Ferramentas (Stack)
* **Power BI Desktop:** Modelagem visual e estruturação do storytelling de dados logísticos.
* **Power Query:** Carga, limpeza, transformação e unificação das bases de entregas e tabelas de vendas.
* **Linguagem DAX:** Criação de medidas para contagem de volumes, cálculo de percentuais de status (antecipado, no prazo, atrasado) e médias de eficiência.

---

## ⚙️ Processo de Desenvolvimento (Ações Executadas)

### 1. Engenharia de Dados (ETL)
* Higienização das colunas de datas de envio e datas de recebimento efetivo para cálculo de prazos.
* Classificação automatizada do status de cada entrega.

### 2. Design de Dashboard e Componentes Visuais
* **Layout Corporativo:** Utilização de uma paleta de cores sóbria baseada em tons de vinho, facilitando o destaque dos indicadores críticos.
* **Visualização de Sazonalidade:** Implementação de gráficos de linha para monitorar o "Total de Entregas por Mês" e o fluxo de entregas por canal, permitindo prever gargalos em meses de pico.
* **Tabelas de Desempenho com Indicadores Visuais:** Acoplamento de um sistema de avaliação por estrelas (*Rating*) diretamente na matriz de performance por vendedor, facilitando o reconhecimento de destaques na equipe.

---

## 📈 Insights e Resultados Obtidos
* **Volumetria de Operação:** O painel consolidou um histórico massivo de **54 Mil entregas** processadas.
* **Alta Eficiência de Prazo:** Foi constatado um excelente nível de serviço (SLA), com **47 Mil entregas realizadas dentro do prazo**.
* **Status de Envio:** O gráfico de colunas indicou que a grande maioria das entregas ocorre de forma **Antecipada (70,71%)**, enquanto as atrasadas somam apenas **12,98%**.
* **Liderança Regional:** A equipe da região **Norte** destacou-se com o maior percentual de entregas da operação (**27,44%**), seguida de perto pelo **Sudeste (24,87%)**.
* **Gestão de Perdas:** Criação de uma tabela de criticidade listando o ranking exato das cidades com maiores atrasos numéricos, permitindo ações corretivas imediatas nas rotas.

---

## 📷 Visualização do Painel

Abaixo está o registro da tela principal de análise logística:

![Análise de Dados de Logística](https://raw.githubusercontent.com/rodrigoifs/analise-dados-logistica-powerbi/refs/heads/main/imagens/analise-logistica.png)
