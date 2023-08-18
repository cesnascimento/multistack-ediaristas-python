# Projeto e-diaristas


### Instalado o projeto

### Clonas o projeto
`git clone https://github.com/cesnascimento/multistack-ediaristas-python.git`
### Instalar dependências
`pip install -r requirements.txt`
### Alterar configuração do BD no arquivo `settings.py`
```
DATABASES = {
    'default': {
        'ENGINE': 'django.db.backends.mysql',
        'NAME': 'NOME_DO_BD',
        'HOST': 'HOST_DO_DB',
        'PORT': 'PORTA_DB',
        'USER': 'USUARIO_BD',
        'PASSWORD': 'SENHA_BD'
    }
}
```
### Migrar banco de dados
`python manage.py migrate`
### Iniciar o servidor
`python manage.py runserver`