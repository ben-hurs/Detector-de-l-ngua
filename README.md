# Detector de língua com Redes Neurais

Este é um projeto de detecção de línguas utilizando redes neurais. O modelo foi treinado para classificar texto de linguas estrajeiras como africaner, inglês e holandês.

## Como Executar o Projeto

Siga os passos abaixo para configurar e executar o projeto no seu ambiente local.

### Clonar o Repositório

Para começar, clone o repositório para o seu computador:

```bash
git clone https://github.com/ben-hurs/detector-de-lingua.git
```

### Navegue até a pasta do repositório
```bash
cd detector-de-lingua
```

### Criar e ativar um Ambiente virtual
#### Windows:
```bash
# Instalar a ferramenta venv
python -m pip install virtualenv

# Criar um ambiente virtual
python -m venv env

# Ativar o ambiente virtual
.\env\Scripts\activate
```

#### Linux/Mac:
```bash
# Criar um ambiente virtual
python3 -m venv env

# Ativar o ambiente virtual
source env/bin/activate

```

### Instalação dos pacotes
Com o ambiente virtual ativado, instale os pacotes.
```bash
pip install -r requeriments.txt
```

### Executar o arquivo
```bash
python detector-de-lingua-redes-neurais.py
```




