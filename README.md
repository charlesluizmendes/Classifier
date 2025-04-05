# Ambiente 

## Instalando Pacotes

No diretório raiz (/) execute o comando abaixo:

```
$ pip install -r requirements.txt
```

### Pacotes Instalados

```
$ pip install transformers
$ pip install scikit-learn 
$ pip install pandas
$ pip install accelerate
$ pip install bitsandbytes
$ pip install torch torchvision torchaudio --index-url https://download.pytorch.org/whl/cu121
```

* O modelo BERT foi criando utlizando CUDA, para acelerar o treinamento e classificação. 

# Execução

## Execução do Notebook

Para executar o notebook [processing.ipynb](https://github.com/charlesluizmendes/Classifier/blob/main/processing.ipynb) no Google Colab basta seguir os passos abaixo:

- Menu 'Arquivo'
- Clicar em 'Fazer upload do notebook'
- Menu 'Ambiente de execução'
- Clicar em 'Executar tudo'

Caso queira executar o notebook no VSCode bastar:

- Abrir o notebook [processing.ipynb](https://github.com/charlesluizmendes/Classifier/blob/main/processing.ipynb)
- Clicar em 'Run All'