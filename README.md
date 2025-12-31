📊 Análise de Churn — TelecomX Brasil

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![Google Colab](https://img.shields.io/badge/Google%20Colab-F9AB00?style=for-the-badge&logo=googlecolab&logoColor=white)

---

📌 Objetivo
Este projeto realiza uma **Análise Exploratória de Dados (EDA)** detalhada sobre a evasão de clientes (churn) na operadora TelecomX. O foco é identificar padrões e fatores críticos que impactam diretamente a receita e o crescimento sustentável da empresa.

---

📁 Estrutura do Projeto

```text
├── TelecomX_BR.ipynb   # Notebook principal com o código e relatório
├── README.md           # Documentação do projeto
└── data/               # Pasta com os dados brutos
    └── telecom_churn.json


---

🧪 Tecnologias e Ferramentas
* Linguagem: Python
* Manipulação de Dados: Pandas, NumPy
* Visualização: Matplotlib, Seaborn
* Ambiente: Google Colab

---

🔎 Etapas do Projeto
1. Extração e ETL: Leitura de 7.267 registros via JSON e limpeza de dados inconsistentes.
2. Análise de Churn: Estudo da distribuição geral (26,58% de evasão).
3. Segmentação por Blocos: Análise detalhada de perfil do cliente, telefonia, internet e contratos.
4. Estatística Descritiva: Comparação de custos mensais e tempo de permanência ('tenure').

---

📈 Principais Insights e Métricas
Baseado na análise de 7.032 registros válidos:

| Fator de Risco | Impacto Observado |
| :--- | :--- |
| Modelo Contratual | Contratos mensais ('month-to-month') possuem churn de ~43% |
| Tecnologia | Clientes com Fibra Óptica apresentam evasão elevada de ~42% |
| Suporte Técnico | A ausência de suporte e segurança online eleva o churn para acima de 40% |
| Financeiro | O pagamento via 'Electronic Check' concentra 45% do risco |

> Nota: Clientes que evadem possuem uma mediana de permanência de apenas 10 meses, contra 38 meses dos clientes fiéis.

---


💡 Recomendações Estratégicas
* Fidelização: Incentivar a migração para contratos anuais com benefícios progressivos.
* Experiência: Reavaliar o valor percebido da Fibra Óptica e incluir suporte nos pacotes.
* Monitoramento: Atenção redobrada aos clientes nos primeiros 12 meses de contrato.

---

▶️ Como Executar
1. Acesse o notebook `TelecomX_BR.ipynb` no Google Colab.
2. Execute as células sequencialmente para processar os dados e gerar os gráficos.
3. O relatório final consolidado encontra-se ao final do notebook.

---

👤 Autor
João Carlos Maiolo 📫 [joao.c.maiolo@uol.com.br]
