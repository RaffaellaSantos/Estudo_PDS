# Estudo\_PDS

## 📌 Sobre o projeto

Este projeto faz parte da disciplina **Processamento Digital de Sinais**, tendo como objetivo:

* Realizar **análise espectral** de sinais de áudio `.wav`
* **Identificar**, **filtrar** e **classificar ruídos** em gravações de áudio
* Exemplificar técnicas de **processamento digital de sinais** aplicadas a áudio

---

## 🗂️ Estrutura do repositório

```
Estudo_PDS/
├── .venv/                 # Ambiente virtual Python
├── arquivos wav/         # Gravações .wav utilizadas como entrada
├── arquivos gerados/     # Resultados gerados pelo notebook
└── trabalho.ipynb        # Notebook com todo o código do projeto
```

* **`.venv`**: contém o ambiente virtual com as dependências necessárias
* **`arquivos wav`**: arquivos de áudio utilizados no processamento
* **`arquivos gerados`**: áudios e gráficos resultantes do código
* **`trabalho.ipynb`**: notebook interativo com análise, filtragem e classificação

---

## ⚙️ Como configurar e executar

### 1. Clonar o repositório:

```bash
git clone https://github.com/RaffaellaSantos/Estudo_PDS.git
cd Estudo_PDS
```

### 2. Ativar o ambiente virtual

* **Linux/macOS**:

  ```bash
  source .venv/bin/activate
  ```

* **Windows (PowerShell)**:

  ```powershell
  .venv\Scripts\Activate.ps1
  ```

### 3. Instalar dependências (se necessário)

Caso o ambiente não contenha todas as bibliotecas, instale manualmente:

```bash
pip install numpy matplotlib scipy scikit-learn prettytable
```

### 4. Executar o notebook:

```bash
jupyter notebook trabalho.ipynb
```

Ou abra diretamente no VS Code / JupyterLab.

---

## 📊 O que o notebook faz

1. **Carrega** os sinais de áudio `.wav`
2. **Analisa espectralmente** (FFT, espectrograma)
3. **Detecta e classifica ruídos**
4. **Aplica filtros** para remoção de ruído
5. **Salva** os sinais filtrados em `arquivos gerados`


## 🛠️ Recomendações

* Sempre **ative o ambiente virtual** antes de executar o notebook
* Mantenha os arquivos `.wav` na pasta `arquivos wav/` com o nome esperado
* Confira a criação dos arquivos em `arquivos gerados/`
