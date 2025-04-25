# Mean-Variance-Standard Deviation Calculator

Este projeto calcula estatísticas básicas (média, variância, desvio padrão, máximo, mínimo e soma) de uma matriz 3x3, utilizando a biblioteca **NumPy** em Python. Ele faz parte do curso de **Análise de Dados com Python** da [freeCodeCamp](https://www.freecodecamp.org/learn/data-analysis-with-python/data-analysis-with-python-projects/mean-variance-standard-deviation-calculator).

## 📊 Objetivo

Criar uma função chamada `calculate()` que receba uma lista com 9 números e retorne um dicionário com as seguintes estatísticas da matriz 3x3:

- Média (`mean`)
- Variância (`variance`)
- Desvio padrão (`standard deviation`)
- Máximo (`max`)
- Mínimo (`min`)
- Soma (`sum`)

Cada estatística deve ser calculada ao longo dos eixos (linhas e colunas) e da matriz "achatada" (flattened).

Se a lista não contiver exatamente 9 números, a função deve lançar um `ValueError`.

## 📁 Estrutura do Projeto

```
📦 mean-variance-standard-deviation-calculator/
├── mean_var_std.py            # Arquivo principal com a função calculate()
├── main.py                    # Script de teste
├── test_module.py             # Testes unitários
└── README.md                  # Este arquivo
```

## 🚀 Como Executar

1. Clone o repositório:
   ```bash
   git clone <url-do-seu-repositório>
   cd mean-variance-standard-deviation-calculator
   ```

2. Instale as dependências (se necessário):
   ```bash
   pip install numpy
   ```

3. Execute o script de teste:
   ```bash
   python main.py
   ```

## ✅ Requisitos

- Python 3.x
- numpy

## 🧪 Testes

Os testes são executados automaticamente ao rodar o `main.py`, que importa as funções de `test_module.py`.

---

Projeto baseado no curso gratuito da [freeCodeCamp](https://www.freecodecamp.org/).
