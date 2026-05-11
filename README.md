# Análise-TCC

Análise de dados de pesquisa para trabalho de conclusão de curso (TCC). Este repositório contém análises de respostas de questionários segmentadas por áreas de estudo e outros fatores demográficos.

## 📋 Descrição do Projeto

Este projeto realiza uma análise detalhada de dados coletados através de questionários para fins acadêmicos. As análises incluem:

- **Análise Demográfica**: Distribuição de respondentes por área de estudo, idade, gênero, etc.
- **Análise por Área de Estudo**: Comparação de respostas entre diferentes áreas (Ciências Agrárias, Biológicas, Exatas, Humanas e Sociais)
- **Visualizações**: Gráficos e tabelas para apresentação dos resultados
- **Estatísticas Descritivas**: Resumos estatísticos dos dados coletados

## 📁 Estrutura do Repositório

```
Analise-TCC/
├── README.md                          # Este arquivo
├── respostas_questionario.csv         # Dados brutos do questionário
├── areas_estudo_analises.ipynb        # Notebook com análises por área de estudo
├── tcc_analises.ipynb                 # Notebook com análises gerais do TCC
├── figuras/                           # Pasta com figuras e gráficos gerados
└── env/                               # Ambiente virtual Python
```

## 🛠️ Tecnologias Utilizadas

- **Python 3.x**
- **Pandas**: Manipulação e análise de dados
- **Matplotlib**: Visualizações básicas
- **Seaborn**: Visualizações estatísticas avançadas
- **NumPy**: Operações numéricas
- **Jupyter Notebook**: Ambiente interativo para análise

## 🚀 Como Usar

### Pré-requisitos

- Python 3.7+
- Pip

### Instalação

1. Clone o repositório:
```bash
git clone https://github.com/MariaLuiseB/Analise-TCC.git
cd Analise-TCC
```

2. Crie um ambiente virtual (opcional, mas recomendado):
```bash
python -m venv env
```

3. Ative o ambiente virtual:
   - **Windows**:
     ```bash
     .\env\Scripts\activate
     ```
   - **macOS/Linux**:
     ```bash
     source env/bin/activate
     ```

4. Instale as dependências:
```bash
pip install pandas matplotlib seaborn jupyter ipykernel
```

### Executando os Notebooks

1. Inicie o Jupyter Notebook:
```bash
jupyter notebook
```

2. Abra um dos notebooks:
   - `areas_estudo_analises.ipynb` - Análises segmentadas por área de estudo
   - `tcc_analises.ipynb` - Análises gerais

## 📊 Dados

### Arquivo: `respostas_questionario.csv`

Contém as respostas coletadas através do formulário de pesquisa, incluindo:
- Data/hora da resposta
- E-mail do respondente
- Consentimento informado
- Informações demográficas (área de estudo, idade, gênero, etc.)
- Respostas para as questões da pesquisa

## 📝 Estrutura das Análises

### Notebooks Principais

#### `areas_estudo_analises.ipynb`
Análise das perguntas demográficas segmentadas por área de estudo:
- Distribuição de respondentes por área
- Características demográficas por área
- Comparações entre áreas

#### `tcc_analises.ipynb`
Análises gerais do TCC incluindo:
- Resumo geral dos dados
- Estatísticas descritivas
- Visualizações principais

## 📈 Saídas Geradas

As análises geram:
- Gráficos em formato PNG salvos em `figuras/`
- Tabelas com estatísticas descritivas
- Resumos de frequências e distribuições

## 👤 Autor

Maria Luise Britto

## 📄 Licença

Este projeto é parte de um trabalho acadêmico e pode estar sujeito aos termos de confidencialidade da instituição.

## 📧 Contato

Para dúvidas ou sugestões sobre este análise, entre em contato através do e-mail fornecido no formulário de consentimento.

---

**Última atualização**: Maio de 2026
