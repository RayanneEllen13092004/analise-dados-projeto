* Segmentação de Clientes com Machine Learning + Dashboard no Power BI

Este projeto utiliza Python (Jupyter Notebook) para análise e segmentação de clientes com técnicas de Machine Learning (ML) e depois visualiza os resultados em um Dashboard interativo no Power BI.
📌 Visão Geral

    Objetivo: Agrupar clientes em clusters com comportamentos similares para estratégias de marketing personalizadas.

    Técnicas:
        - Pré-processamento de dados (Pandas, Scikit-learn).
        - Algoritmo de Clustering (K-Means).
        - Dashboard no Power BI para análise interativa.

🛠 Tecnologias Utilizadas
    - Linguagem: Python
    - Ferramentas:
        Jupyter Notebook
        Power BI

    Bibliotecas:
    python -> scikit-learn

🚀 Como Executar o Projeto
    Pré-requisitos:
        - Python 3.x instalado.
        - Jupyter Notebook (pip install notebook).
        - Bibliotecas listadas em requirements.txt (caso exista).

    Passos:
    bash
    # Clone o repositório
    git clone https://github.com/seu-usuario/customer-segmentation.git

    # Instale as dependências (se necessário)
    pip install -r requirements.txt

    # Execute o Jupyter Notebook
    jupyter notebook segmentacao_clientes.ipynb

    Power BI:
        - Abra o arquivo dashboard_segmentacao.pbix no Power BI Desktop.
        - Certifique-se de que a fonte de dados está atualizada.

🔍 Métodologia
    Análise Exploratória (EDA):
        - Limpeza de dados (missings, outliers).
        - Análise de correlação e distribuição.

    Machine Learning:
        - Normalização/Padronização dos dados.
        - Aplicação de algoritmo de clustering.

    Visualização:
        - Gráficos de barras e rosca para mostrar os clusters.
        - Exportação dos dados segmentados para o Power BI.

    Dashboard:
        - Filtros interativos por cluster.

📊 Resultados
Saídas do Jupyter Notebook:
    - Dashboard no Power BI: ![Dashboard](ML+Powerbi/img/imgfinal.png)

    Com o objetivo de auxiliar em:
        - Visão geral por segmento.
        - Comparativo de métricas por grupo.
        - Insights acionáveis.

📝 Conclusão
    - Os clusters identificados permitem direcionar campanhas de marketing de forma eficiente.
    - O Power BI facilita a interpretação dos dados por equipes não técnicas.

🔗 Links Úteis
    - Dashboard no Power BI Online: https://app.powerbi.com/links/aEfRGW7mZI?ctid=1c071ab0-c3a1-4ffc-ae0f-17869f1c19bb&pbi_source=linkShare
    - Curso de onde tirei as skills para esse projeto: https://www.datascienceacademy.com.br/course/microsoft-power-bi-para-business-intelligence-e-data-science

📧 Contato
Feito por Rayanne Ellen dos Santos Marques
✉️ marquesrayanne2020@gmail.com
🔗 https://www.linkedin.com/in/rayanneellenmarques/

🎯 Melhorias Futuras
    - Testar outros algoritmos (DBSCAN, Hierárquico).
    - Adicionar previsão de churn.
    - Automatizar a pipeline com Airflow.
