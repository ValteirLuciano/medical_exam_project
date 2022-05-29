Projeto Exame medico
Exemplo de uso do Django com inlineformset e htmx. Projeto exames médicos.

Este projeto foi feito com:

Python 3.8
Django 4.0
Bootstrap 4.0
htmx


Como rodar o projeto?

Clone esse repositório.
Crie um virtualenv com Python 3.
Ative o virtualenv.
Instale as dependências.
Rode as migrações.


git clone https://gitlab.com/rg3915/exame-inline.git
cd exame-inline
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
python contrib/env_gen.py
python manage.py migrate
python manage.py createsuperuser --username="admin" --email=""


