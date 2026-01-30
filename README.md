# terminal-velocity-prediction

Repositório com a base de código utilizada no artigo  
**"Physics-based feature engineering for machine learning in terminal velocity prediction of fractal aggregates formed during flocculation"**

---

## 1. Clone o repositório

```bash
mkdir -p ~/repos
cd ~/repos
git clone https://github.com/danieltodaDS/terminal-velocity-prediction.git
cd terminal-velocity-prediction
```

## 2. Configure a versao correta do Python (recomendado:`pyenv`): 
Este projeto foi desenvolvido com Python 3.12.1.
```bash
pyenv install 3.12.1
pyenv local 3.12.1
python --version
```
⚠️ Caso não utilize pyenv, certifique-se de estar usando Python 3.12.x.


## 3. Crie e ative o ambiente virtual
```bash
python -m venv .venv

#Linux
source .venv/bin/activate 

#Windows
source .venv\\Scripts\\Activate 
pip install -r requirements.txt
```

## 4. Instale as dependências
```bash
pip install -r requirements.txt
```