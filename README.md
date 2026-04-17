# Estudos de Python para Dados e Machine Learning

Este repositório é dedicado ao estudo e aprofundamento na linguagem Python, com foco principal em bibliotecas de Ciência de Dados e Machine Learning. O objetivo final e principal deste roteiro de aprendizado é chegar ao entendimento e aplicação de **Redes Neurais em Grafos (Graph Neural Networks - GNNs)**.

## Objetivos

- Revisar e consolidar conceitos básicos de Python.
- Dominar as principais bibliotecas de Ciência de Dados (Pandas, NumPy, Matplotlib, etc.).
- Revisar os conceitos matemáticos fundamentais.
- Entender os fundamentos de Machine Learning (Scikit-Learn, TensorFlow/PyTorch).
- Explorar e implementar arquiteturas de Graph Neural Networks (GNNs).

## Requisitos

- Python **3.9.25** (Você pode alterar a versão editando o arquivo `.python-version` caso utilize gerenciadores como `pyenv`).
- Editor de código (Recomendamos o **VS Code** com a extensão do **Jupyter** instalada para abrir os notebooks nativamente).

## Como Configurar e Executar o Ambiente

1. **Clone o repositório** e entre na pasta do projeto:

   ```bash
   git clone
   cd python-aplicado-a-dados-e-machine-learning
   ```

2. **Crie o ambiente virtual (venv)** (usando a versão correspondente do seu Python):

   ```bash
   python -m venv .venv
   ```

3. **Ative o ambiente virtual**:
   - No **Linux/macOS**:
     ```bash
     source .venv/bin/activate
     ```
   - No **Windows**:
     ```bash
     .venv\Scripts\activate
     ```

4. **Instale as dependências do projeto (Se houver algum)**:

   ```bash
   pip install -r requirements.txt
   ```

### Abrindo os Notebooks

Você tem duas opções principais para rodar os cadernos interativos (`.ipynb`):

**Opção A: No VS Code (Mais rápido e integrado)**

1. Instale a extensão do **Jupyter** no seu VS Code.
2. Abra qualquer arquivo `.ipynb`.
3. No canto superior direito, escolha "Select Kernel" e aponte para o ambiente virtual `.venv` recém-criado.

**Opção B: No Navegador Web (Instalação Local do JupyterLab)**
Se preferir usar a interface web padrão do Jupyter, aplique os passos abaixo no seu terminal (com a `.venv` já ativada):

```bash
# Instala o JupyterLab e o Kernel dentro desse ambiente isolado
pip install jupyterlab ipykernel

# Registra o kernel para o Jupyter reconhecer (substitua a string de display de acordo com sua versão)
python -m ipykernel install --user --name=py_kernel --display-name "Python 3.9.25 (venv)"

# Inicie o Jupyter no navegador
jupyter lab
```
