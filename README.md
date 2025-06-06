
# 📦 Análise das Exportações Brasileiras

Este projeto tem como objetivo analisar dados de exportações do Brasil, com foco nas exportações destinadas à **França** a partir do ano de **2016**. A análise foi realizada em Python utilizando bibliotecas populares de manipulação de dados, e pode servir como base para estudos econômicos, comerciais ou de mercado.

## 🎯 Objetivos

- Carregar e explorar dados de exportações do Brasil;
- Filtrar a base de dados para exportações destinadas à França a partir de 2016;
- Exportar esse subconjunto em um novo arquivo `.csv`;
- Preparar os dados para análises e visualizações futuras.

## 🗂️ Dados

As bases de dados utilizadas estão disponíveis neste link do Google Drive:

📁 [Acessar os dados no Google Drive](https://drive.google.com/drive/folders/18LRQfN9hCe8Y2UOBY8tiO2tO8nDWO1f7?usp=drive_link)

- `exportacao_full.csv`: base de dados original com todas as exportações
- `exportacao_france.csv`: base filtrada apenas com exportações para a França a partir de 2016

> ℹ️ A base original foi obtida na plataforma [Kaggle](https://www.kaggle.com/), reconhecida por fornecer conjuntos de dados confiáveis para análise e aprendizado de máquina.

## 🧰 Tecnologias e Bibliotecas Utilizadas

- **Python 3.x**
- **Jupyter Notebook**: ambiente para desenvolvimento interativo
- **Pandas**: biblioteca para manipulação e análise de dados

## ⚙️ Técnicas Aplicadas

- **Leitura de arquivos CSV**
- **Filtragem de dados** com base em condições lógicas (`Country == "France"` e `Year >= 2016`)
- **Exportação de dados** para novos arquivos `.csv`
- **Exploração inicial** da estrutura da base com métodos como `.info()` e `display()`

## 📁 Estrutura do Projeto

```
Brazil Exports.ipynb         # Notebook principal com o processo de análise
exportacao_full.csv          # Base de dados original (link no Drive)
exportacao_france.csv        # Base filtrada (link no Drive)
```

---

## 👨‍💻 Autor

**Gabriel Chaves**  
📧 gabrielbsc0720@gmail.com  
🔗 [LinkedIn](www.linkedin.com/in/gabriel-borges-ch)

---

Este projeto está licenciado sob a **MIT License**.