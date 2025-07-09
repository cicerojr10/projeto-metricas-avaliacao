# 📊 Projeto: Avaliação de Classificadores com Matriz de Confusão

Este projeto demonstra como gerar e visualizar uma **matriz de confusão normalizada** para modelos de classificação com múltiplas classes, utilizando dados simulados. O código foi desenvolvido no **Google Colab**, ideal para estudos, apresentações (live code) e repositórios educacionais.

---

## 🚀 Funcionalidades

- Gera dados fictícios de classificação com **10 classes (0 a 9)**
- Simula previsões com acerto parcial
- Calcula a **matriz de confusão** usando `TensorFlow`
- Normaliza e exibe a matriz com `Seaborn`
- **Salva a imagem** como `.png`
- Permite **baixar a imagem** direto pelo Google Colab

---

## 🛠️ Tecnologias

- Python 3
- Google Colab
- TensorFlow
- NumPy
- Pandas
- Seaborn
- Matplotlib

---

## 📦 Como Executar no Google Colab

1. Acesse o [Google Colab](https://colab.research.google.com/)
2. Copie e cole os blocos de código fornecidos
3. Execute os blocos um por um
4. A matriz será exibida ao final e poderá ser baixada

---

## 💾 Como Salvar o Gráfico

O projeto inclui um bloco final que:

- Salva a imagem como `matriz_confusao.png`
- Inicia o **download automático no seu navegador**

---

## 📁 Estrutura Recomendada do Projeto

```
projeto-metricas-avaliacao/
├── matriz_confusao.png              # Arquivo gerado com o gráfico
├── confusion_matrix_colab.ipynb     # Notebook com o código completo
├── README.md                        # Este arquivo
└── requirements.txt                 # (opcional) Dependências para executar localmente
```

---

## 🧪 Exemplo de Resultado

Uma matriz 10x10 como esta:

```
      Predito
      0  1  2 ... 9
Real
 0   0.80 ...
 1   ...   0.90
 ...
```

Representada visualmente com tons de azul mais fortes indicando maior acerto.

---

## 📬 Contato

Projeto criado por **Cícero Quintino Junior** para fins educacionais e práticos.
