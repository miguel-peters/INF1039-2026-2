# INF1039-2026-2

PROCESSO DE CRIAÇÃO DO DJANGO NO REPOSITÓRIO

Criar e ativar o ambiente virtual
- python -m venv venv
- .\venv\Scripts\activate

Instalar o Django
- pip install Django

Criar o projeto dentro do repositorio no Django
- django-admin startproject calouroPlus
- cd calouroPlus
- python manage.py startap calouroPlusApp

OBS:
- ir até o settings.py e adcionar o app que acabamos de criar para o Django conseguir ler o aplicativo

PROCESSO DE ADCIONAR O VIEW + URL DENTRO DO DJANGO

Antes disso acontecer, a pasta static e a pasta templates tem que estar dentro da pasta do django

- Dento da pasta calouroApp, no codigo views.py, criar uma função onde retorna o request e o código da página HTML
- Ir para a pasta do django, no código urls.py e adcionar um path até a nova função home

OBS: Lembrar de importar o código views.py para dentro do código urls.py para conseguir pegar a função!
