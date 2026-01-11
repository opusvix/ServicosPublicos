<div align="center">
  <img src="imagens/Cesan.png" alt="CESAN" height="60" />
  &nbsp;&nbsp;&nbsp;
  <img src="imagens/Escelsa.png" alt="EDP Escelsa" height="60" />
  &nbsp;&nbsp;&nbsp;
  <img src="imagens/Solar.png" alt="EDP Solar" height="60" />
</div>

# Serviços Públicos & Energia Solar

### Análise de Consumo, Custos e Créditos de Energia Solar (Power BI)

## 📌 Contexto do Projeto

Os custos com serviços públicos representam uma parcela relevante do orçamento de organizações públicas e privadas. Este projeto analisa dados históricos de **consumo e faturamento**, com foco na avaliação do impacto financeiro dos **créditos de energia do programa Solar Digital EDP**, estabelecido por contrato de locação de usina de minigeração de energia elétrica.

O dashboard foi desenvolvido em **Power BI**, utilizando abordagem analítica orientada a negócio, com indicadores financeiros, operacionais e ambientais (ESG), apoiando a tomada de decisão baseada em dados.

## 🎯 Objetivos

* Analisar a evolução do consumo e dos custos ao longo do tempo
* Avaliar o impacto financeiro da adoção da energia solar
* Identificar sazonalidades e oportunidades de eficiência
* Mensurar a contribuição ambiental associada ao uso de energia limpa

## 📊 Estrutura do Dashboard

* **Página 1 – Visão Geral**

  * Indicadores-chave de consumo, custo e economia
  * Evolução temporal dos custos

* **Página 2 – Consumo & Eficiência**

  * Heatmap sazonal de consumo
  * Análise por tipo de serviço
  * Indicadores de eficiência operacional

* **Página 3 – Energia Solar & ESG**

  * Economia acumulada com energia solar
  * Comparativo de custos com vs. sem energia solar
  * Contribuição ambiental total (Kg CO₂ evitado)

* **Página 4 – Detalhamento Anual**

  * Análise consolidada por ano
  * Apoio à tomada de decisão estratégica

## 🧩 Modelagem de Dados

* Modelo em estrela
* Tabela calendário dedicada
* Relacionamentos unidirecionais (Calendário → Fato)
* Base preparada para análises temporais e comparativas

## 🧮 Principais Medidas DAX

* Consumo Total
* Custo Bruto
* Economia Solar
* Custo Líquido
* Economia Acumulada
* Percentual de Economia
* Contribuição Ambiental Total (Kg CO₂)
* Variação mês a mês (M/M)

## 🛠️ Tecnologias Utilizadas

* Power BI Desktop (PBIP / PBIR)
* DAX
* Git & GitHub
* Visual Studio Code
* OneDrive (fonte de dados)

## 📁 Estrutura do Repositório

```
├── definition.pbir
├── imagens/
├── README.md
├── storytelling.md
├── .gitignore
```

## ▶️ Como Executar o Projeto

1. Clone este repositório
2. Abra o arquivo `definition.pbir` no Power BI Desktop
3. Caso necessário, ajuste o caminho da base de dados no OneDrive
4. Atualize o modelo e explore o dashboard

## 🚀 Próximos Passos

* Projeções de economia futura
* Criação de metas e alertas de consumo
* Expansão dos indicadores ESG

## 👤 Autor

**Maurício Barros**
Analista de Dados | Power BI | Data Analytics | ESG
