
Sistema COSMET


## Como Desenvolver

1. Clone o Repositório
2. Crie uma Virtualenv
3. Ative a Virtualenv
4. Instalar Dependências
5. Suba o servidor de desenvolvimento

```console
git clone https://github.com/pcego/salao.git
cd salao
python -m venv .salao
source .salao/bin/activate
pip install -r requirements.txt
python manage.py runserver
```