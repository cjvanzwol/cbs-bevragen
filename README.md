# CBS bevragen
Template notebook voor het bevragen van CBSdata via odata

## Installeren
### Afhankelijkheden
Python, pip en virtualen zijn geinstalleerd.

### Installeer omgeving
clone deze repository
#### Windows
```
virtualenv .env
.env\Scripts\activate
.env\Scripts\python.exe -m pip install --upgrade pip
pip install -r requirements.txt
python -m ipykernel install --name cbsodata
```
#### Linux
virtualenv .env
source .env/bin/activate
.env/bin/ -m pip install --upgrade pip
pip install -r requirements.txt
python -m ipykernel install --name cbsodata

## Hoe werkt het notebook
Stel variabelen in:
- ... = code van de dataset van CBS