🎬 Flix API

API desenvolvida em Python com Django REST Framework para treinar habilidades em CRUD.
O projeto simula um catálogo de filmes, permitindo gerenciar informações de filmes, atores, gêneros e classificações.

🚀 Tecnologias Utilizadas

Python 3.x

Django

Django REST Framework

SQLite (padrão, mas pode ser adaptado para outros bancos)

⚙️ Funcionalidades

Cadastro, listagem, atualização e exclusão de Filmes

Cadastro e gerenciamento de Atores

Cadastro de Gêneros

Gerenciamento de Classificações (faixa etária / rating)

Relacionamento entre filmes, atores e gêneros


git clone https://github.com/seu-usuario/flix-api.git
cd flix-api


python -m venv venv
source venv/bin/activate   # Linux/Mac
venv\Scripts\activate      # Windows

python manage.py migrate

python manage.py runserver


