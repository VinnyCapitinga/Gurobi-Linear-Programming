#  Modelagem e Resolução de Problemas de Programação Linear com Gurobi

Este repositório apresenta a **modelagem e resolução de problemas de Programação Linear (PL)**, **Programação Linear Inteira (PLI)** e **Programação Linear Binária (PLB)** utilizando o **solver Gurobi** em Python.

O projeto tem caráter **acadêmico e demonstrativo**, com o objetivo de aplicar conceitos de **Pesquisa Operacional** em problemas práticos de otimização.

---

## 🧩 Estrutura do Projeto

    gurobi-linear-programming/
    │
    ├── README.md
    ├── LICENSE
    ├── requirements.txt
    │
    ├── notebooks/
    │ ├── PL/
    │ │ ├── questao_01_fazenda.ipynb
    │ │ ├── questao_02_transporte.ipynb
    │ │ └── ...
    │ ├── PLI/
    │ └── PLB/
    │
    └── docs/
    ├── lista_1_MC.pdf # Lista de questões base
    └── Readme.md # Índice e descrições das questões



## 📚 Lista de Questões

A lista de exercícios utilizada como base para este projeto foi elaborada pela  
**Profa. Dra. Tatiane Fernandes Figueiredo**, no contexto da disciplina de *Pesquisa Operacional*.

📘 O arquivo completo está disponível em:  
 📁Docs

> O material é utilizado aqui **apenas para fins educacionais e demonstrativos**.

---

## ⚙️ Execução dos Notebooks

Para executar os notebooks em sua máquina local:

1. Certifique-se de ter o **Python 3.10+** instalado.
2. Instale o **Gurobi** e configure sua **licença acadêmica** (ou comercial).
3. Instale a dependência principal:

   ```bash
   pip install -r requirements.txt

4 Execute os notebooks normalmente:


jupyter notebook
💡 Caso não possua uma licença Gurobi válida, ainda é possível abrir e visualizar os notebooks, mas o solver não executará as otimizações.

Agradecimentos

Agradeço à Profa. Dra. Tatiane Fernandes Figueiredo pela elaboração das questões e pela contribuição teórica que inspirou o desenvolvimento deste projeto.

⚖️ Licença

Este projeto é distribuído sob a licença MIT.
O solver Gurobi é um software proprietário — sua utilização requer licença válida.
