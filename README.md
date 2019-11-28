* Estudos e experimentos com TensorFlow no Python

Feito com Python 3.7.5 64-bits no Windows 10

Para instalar venv:
pip3 install -U pip virtualenv    
virtualenv --system-site-packages -p py ./venv 

Para entrar na venv:
./venv/Scripts/activate

Para salvar dependências:
pip freeze > requirements.txt

Para instalar dependências:
pip install -r requirements.txt

Para sair da venv:
deactivate