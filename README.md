# 🤖 CS50's Introduction to Artificial Intelligence with Python

> O meu percurso pelo curso [CS50 AI](https://cs50.harvard.edu/ai/) da Universidade de Harvard: notas, quizzes, código das aulas e projetos, organizados por módulo.

![Python](https://img.shields.io/badge/Python-3.12-3776AB?logo=python&logoColor=white)
![Harvard CS50](https://img.shields.io/badge/Harvard-CS50%20AI-A51C30)
![Progresso](https://img.shields.io/badge/progresso-1%2F7%20m%C3%B3dulos-yellow)

---

## 📖 Sobre este repositório

Este repositório é o meu caderno de estudo do **CS50's Introduction to Artificial Intelligence with Python**. À medida que avanço no curso vou adicionando aqui:

- 📝 **Quizzes**: as perguntas de cada módulo, com a resposta e um resumo do conceito por trás
- 💻 **Código das aulas** (`srcN/`): os exemplos dados em cada lecture, para correr e experimentar
- 🧩 **Projetos**: as minhas implementações dos problem sets
- 🗒️ **Notas**: resumos e apontamentos pessoais de cada tema

As explicações estão em português; os enunciados e o código mantêm-se em inglês, como no curso.

---

## 🗺️ Progresso

| # | Módulo | Tema | Quiz | Código da aula | Projetos | Estado |
|:-:|---|---|:-:|:-:|---|:-:|
| 0 | [Search](Search/) | Procura em espaços de estados (DFS, BFS, A\*, Minimax) | [Quiz 0](Search/Quiz0.md) | [src0](Search/src0/) | Degrees · Tic-Tac-Toe | 🟡 |
| 1 | Knowledge | Lógica proposicional e inferência | Quiz 1 | src1 | Knights · Minesweeper | ⏳ |
| 2 | Uncertainty | Probabilidade, redes Bayesianas, Markov | Quiz 2 | src2 | PageRank · Heredity | ⏳ |
| 3 | Optimization | Hill climbing, simulated annealing, CSPs | Quiz 3 | src3 | Crossword | ⏳ |
| 4 | Learning | Machine learning supervisionado e reinforcement learning | Quiz 4 | src4 | Shopping · Nim | ⏳ |
| 5 | Neural Networks | Redes neuronais, CNNs, TensorFlow | Quiz 5 | src5 | Traffic | ⏳ |
| 6 | Language | NLP, gramáticas, transformers e atenção | Quiz 6 | src6 | Parser · Attention | ⏳ |

**Legenda:** ✅ concluído · 🟡 em curso · ⏳ por começar

---

## 📂 Estrutura

Cada módulo tem a sua pasta, sempre com a mesma organização:

```
CS50-s-Introduction-to-Artificial-Intelligence-with-Python/
├── README.md
├── Search/                 # Módulo 0
│   ├── Quiz0.md            # Quiz com respostas e explicações
│   ├── Notes.md            # Apontamentos da aula
│   ├── src0/               # Código de exemplo da lecture
│   │   ├── maze.py
│   │   ├── maze1.txt ...
│   │   └── requirements.txt
│   ├── degrees/            # Projeto 0a
│   └── tictactoe/          # Projeto 0b
├── Knowledge/              # Módulo 1
├── Uncertainty/            # Módulo 2
├── Optimization/           # Módulo 3
├── Learning/               # Módulo 4
├── Neural-Networks/        # Módulo 5
└── Language/               # Módulo 6
```

---

## 🚀 Como correr o código

Requer **Python 3.12** (a versão que o curso usa).

```bash
# 1. Clonar o repositório
git clone https://github.com/Blive77/CS50-s-Introduction-to-Artificial-Intelligence-with-Python.git
cd CS50-s-Introduction-to-Artificial-Intelligence-with-Python

# 2. (Opcional) Criar um ambiente virtual
python -m venv .venv
source .venv/bin/activate        # Windows: .venv\Scripts\activate

# 3. Entrar na pasta de um módulo e instalar as dependências
cd Search/src0
pip install -r requirements.txt

# 4. Correr um exemplo
python maze.py maze1.txt
```

---

## 🔗 Recursos

- 🌐 [Página oficial do curso](https://cs50.harvard.edu/ai/)
- 🎥 [Aulas no YouTube](https://www.youtube.com/@cs50)
- 📚 [Artificial Intelligence: A Modern Approach](https://aima.cs.berkeley.edu/) (Russell & Norvig): o livro de referência para os temas do curso
- 💬 [Comunidade CS50 no Discord](https://cs50.harvard.edu/x/communities/)

---

## ⚖️ Honestidade académica

Este repositório é um registo pessoal de aprendizagem. Se estás a fazer o CS50 AI, tenta resolver os problemas sozinho primeiro: copiar soluções viola a [política de honestidade académica do CS50](https://cs50.harvard.edu/ai/honesty/) e, mais importante, tira-te a parte em que realmente aprendes.

---

<p align="center">Feito com ☕ e muita procura em largura, por <a href="https://github.com/Blive77">Blive77</a></p>
