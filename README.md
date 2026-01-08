# Serviços Públicos – Análise de Consumo e Energia (Power BI Project)

Projeto de Business Intelligence desenvolvido em **Power BI (formato PBIP/PBIR)** para análise de custos e consumo de serviços públicos, com destaque para **energia elétrica** e os **créditos do programa Solar Digital EDP** (campo `economiaValor`).

## 🎯 Objetivo

* Monitorar consumo, custos e eficiência ao longo do tempo
* Evidenciar **economia financeira** gerada por créditos de energia solar
* Apoiar decisões com indicadores claros (tendência, sazonalidade e eficiência)

## 🧱 Estrutura do Projeto (PBIP)

```
ServicosPublicos/
├─ dataset/
│  ├─ model.bim
│  ├─ tables/
│  └─ measures/
├─ report/
│  ├─ definition.pbir
│  └─ pages/
├─ data/
│  └─ ServicosPublicos.xlsx
├─ docs/
│  ├─ storytelling.md
│  └─ imagens/
├─ README.md
└─ .gitignore
```

## 📊 Principais Métricas (DAX)

* **Valor Total**
* **Consumo Total** (por unidade de medida)
* **Custo Unitário Médio**
* **Economia Solar (R$)**
* **% Economia sobre o Valor**
* **Variação M/M e A/A**

## 🗓️ Tabela Calendário

Criada via DAX com base em `ano` e `mes`, habilitando análises temporais completas.

## 🔍 Insights Esperados

* Tendência de custos por serviço
* Impacto real dos créditos solares no custo total
* Sazonalidade de consumo
* Eficiência (custo por unidade)
* Comparativo com e sem economia solar

## 🛠️ Ferramentas

* Power BI Desktop (PBIP / PBIR)
* VS Code
* Git & GitHub
* OneDrive (fonte de dados)

## 🚀 Como Executar

1. Clone o repositório
2. Abra a pasta no **VS Code**
3. Abra o projeto PBIP no Power BI Desktop
4. Verifique o caminho do arquivo em `OneDrive - vtxcy/ProjetosBI/ServicosPublicos`

## 👤 Autor

**Maurício Barros**

Analista de Dados | BI | Power BI | IA Generativa

🔗 GitHub: [https://github.com/opusvix](https://github.com/opusvix)
