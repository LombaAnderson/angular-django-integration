# angular-django-integration


[![NPM](https://img.shields.io/npm/l/react)](https://github.com/LombaAnderson/angular-django-integration/blob/main/LICENSE)

# Sobre o projeto

Aplicação que tem a finalidade de desenvolvimento de integração completa entre o frontend feito em Angular para cadastro de clientes e o backend desenvolvido em Django
Rest Framework

## Imagem de exemplo da api do Django Rest Framework
<div align="center">
<img src=https://user-images.githubusercontent.com/60937513/168070105-362d9208-daad-4c50-a07f-1383e8d95895.png" width="700" />
</div>

# principais Tecnologias utilizadas
- Python & Angular

 Principais Frameworks
-Django
-Django Rest Framework
-Cors
-Python-decouple


# Instruções para compilar, testar e rodar o projeto

```bash
# Clonar repositório
git clone https://github.com/LombaAnderson/angular-django-integration

# Criação e acesso da pasta do projeto
-mkdir members-backend                                                                                                                        
-cd members-backend

# Criação do ambiente de desenvolvimento do Python
-python -m venv venv

# Ativar o ambiente de desenvolvimento(venv)
-source venv/Scripts/.activate

# Instalação do Django (Atenção: instalar somente após a ativação da venv)
-pip install django
 
# Comando de criação do projeto
-django-admin startproject core .

# Criação do servidor
-python manage.py runserver

# Acesso ao servidor Django
http://127.0.0.1:8000/

# Apps 
-django-admin startapp front

# Preparação das migrations
- python manage.py makemigrations

# Envio das migrations configuradas para o banco de dados
- python manage.py migrate
                                                                                                                           
# Criação do Frontend com Angular

- npm install -g @angular/cli
- ng new members-front
- cd members-front
- ng serve
- ng generate service api
- ng generate component members-detail

```

# Autor

Anderson Lomba de Oliveira

Linkedin

https://www.linkedin.com/in/anderson-lomba-140279142/

Portfólio

https://www.lombanderson.epizy.com

# Agradecimentos

Agradeço ao meu Deus que sempre me ajuda, que sem Ele nada pode ser feito e a minha esposa que amo muito! 


