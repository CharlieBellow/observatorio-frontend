![Início](https://github.com/user-attachments/assets/164a578e-7050-4084-a45c-1b93e819c9fc)
![Carregamento](https://github.com/user-attachments/assets/80798ffa-dbd1-4e54-9a2a-77feed8d9658)
![Tabelas](https://github.com/user-attachments/assets/b232be48-ef23-42c5-8ff1-7caff5b79288)
![Gráficos](https://github.com/user-attachments/assets/302a7662-75be-4783-8c02-ecabdd08ac8f)
![Documentos](https://github.com/user-attachments/assets/afca7815-142e-4e90-9251-ac14df730e29c)


# Observatório do Mercado de Trabalho - SINE

Este projeto faz parte de um ecossistema de dados desenvolvido para automatizar a coleta, o tratamento e a visualização de indicadores de emprego e renda (RAIS/CAGED).

## 🏗️ Visão Geral do Sistema

Diferente de sistemas convencionais, o Observatório foi projetado para lidar com **Big Data Governamental**, focando em três pilares:
1. **Automação de Dados:** Pipelines em Python que substituem o processamento manual.
2. **Performance:** Backend assíncrono para entrega rápida de indicadores.
3. **UX Analítico:** Interface focada em dashboards de fácil interpretação.

## 🛠️ Foco deste Repositório ([Frontend / Backend / FastAPI])


> **Frontend: (Vite + React) - Foco: Performance e Interface Reativa.** Implementado com Vite, garantindo um ambiente de desenvolvimento ultra-rápido e um bundle final otimizado. A interface utiliza Tailwind CSS para estilização utilitária e ShadCN UI para garantir componentes acessíveis e consistentes. O foco principal foi a criação de uma experiência fluida para a visualização de grandes volumes de dados analíticos.

> **FastAPI: (Ambiente de Produção)- Foco: Alta Disponibilidade e Deploy Moderno** Utilizado para expor endpoints de alta performance, simulando um ambiente de produção real com deploy na Vercel. Esta camada atua como a ponte ágil para o consumo de dados, garantindo que o frontend receba informações tipadas e validadas em milissegundos, demonstrando competência em infraestrutura e CI/CD.

> **Backend: (Django + Pandas) - Foco: Engenharia de Dados e Lógica de Negócio.** O "core" de processamento de dados utiliza Django (Python) integrado à biblioteca Pandas. Esta estrutura é responsável por iterar, limpar e filtrar bases governamentais massivas, garantindo a integridade dos dados antes da persistência no banco de dados. É aqui que a complexidade técnica se transforma em informação estruturada e pronta para o negócio.



## 🚀 Destaques de Engenharia

- **Pipeline ETL:** Extração e transformação de arquivos brutos de servidores FTP governamentais utilizando **Python e Pandas**.
- **Containerização:** Ambiente totalmente isolado e replicável via **Docker**, facilitando o deploy e a escalabilidade.
- **FastAPI:** Uso de rotas assíncronas e Pydantic para garantir que a comunicação entre o pipeline de dados e o frontend seja extremamente rápida e tipada.

## 📉 Resultados Obtidos

* **Eficiência:** Redução do tempo de processamento de dados de dias para minutos.
* **Acessibilidade:** Dados antes restritos a planilhas técnicas agora estão disponíveis via interface web para gestores públicos.

---
**Nota:** Este projeto demonstra minha capacidade de gerenciar o ciclo de vida completo de um produto de dados (End-to-End).


# Rodar o projeto:
pip install -r requirements.txt
uvicorn api.index:app --reload
