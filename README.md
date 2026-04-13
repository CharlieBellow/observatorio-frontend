# Observatório do Mercado de Trabalho - SINE

Este projeto faz parte de um ecossistema de dados desenvolvido para automatizar a coleta, o tratamento e a visualização de indicadores de emprego e renda (RAIS/CAGED).

## 🏗️ Visão Geral do Sistema

Diferente de sistemas convencionais, o Observatório foi projetado para lidar com **Big Data Governamental**, focando em três pilares:
1. **Automação de Dados:** Pipelines em Python que substituem o processamento manual.
2. **Performance:** Backend assíncrono para entrega rápida de indicadores.
3. **UX Analítico:** Interface focada em dashboards de fácil interpretação.

## 🛠️ Foco deste Repositório ([Frontend / Backend / FastAPI])

*Nesta seção, descreva a parte específica, por exemplo:*
> **Frontend:** Implementado com **Next.js 14**, utiliza **Tailwind CSS** e **ShadCN UI** para uma interface responsiva e **TanStack Query** para gerenciamento de estado e cache de dados.

## 🚀 Destaques de Engenharia

- **Pipeline ETL:** Extração e transformação de arquivos brutos de servidores FTP governamentais utilizando **Python e Pandas**.
- **Containerização:** Ambiente totalmente isolado e replicável via **Docker**, facilitando o deploy e a escalabilidade.
- **FastAPI:** Uso de rotas assíncronas e Pydantic para garantir que a comunicação entre o pipeline de dados e o frontend seja extremamente rápida e tipada.

## 📉 Resultados Obtidos

* **Eficiência:** Redução do tempo de processamento de dados de dias para minutos.
* **Acessibilidade:** Dados antes restritos a planilhas técnicas agora estão disponíveis via interface web para gestores públicos.

---
**Nota:** Este projeto demonstra minha capacidade de gerenciar o ciclo de vida completo de um produto de dados (End-to-End).
