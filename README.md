# Projeto de Otimização com Interface Simplex

Este projeto é uma aplicação web desenvolvida em Python utilizando o microframework Flask para resolver problemas de otimização linear (Simplex). Ele apresenta uma interface amigável onde os usuários podem inserir dados de entrada, como variáveis de decisão, coeficientes da função objetivo e restrições, e visualizar os resultados de maneira clara e organizada.

## 📋 Funcionalidades

- **Entrada de Dados:** Interface para o usuário inserir:
  - Número de variáveis de decisão.
  - Número de restrições.
  - Coeficientes da função objetivo (F.O.).
  - Coeficientes das restrições.
- **Cálculo Automático:** Implementação do algoritmo Simplex em Python para processar os dados e resolver o problema.
- **Exibição dos Resultados:** Interface que mostra os valores das variáveis de decisão, a viabilidade da solução e o novo lucro obtido após a otimização.
- **Interface Responsiva:** Desenvolvida em HTML e estilizada com CSS, garantindo uma experiência de usuário intuitiva.

## 🛠️ Tecnologias Utilizadas

- **Backend:**
  - [Python](https://www.python.org/)
  - [Flask](https://flask.palletsprojects.com/)
- **Frontend:**
  - HTML5
  - CSS3
- **Bibliotecas e Ferramentas Adicionais:**
  - Algoritmo Simplex implementado manualmente ou via bibliotecas como `SciPy` (opcional).

## 📂 Estrutura do Projeto
'''
project/ 
│-- main.py # Arquivo principal para rodar a aplicação Flask 
│-- templates/ # Arquivos HTML 
│ │-- home.html # Página inicial (entrada de dados) 
│ │-- result.html # Página para exibir os resultados 
│-- static/ # Arquivos estáticos (CSS, imagens) 
│ │-- styles.css # Estilo da aplicação 
│-- venv/ # Ambiente virtual (recomendado)
'''

