# Dockerizing DRF Cinema
API for managing cinema


### Installing using GIThub
- git clone https://github.com/Litvinenko23/cinema-drf-api.git
- python -m venv venv
- source venv/bin/activate
- pip install -r requirements.txt

### Next steps
- python manage.py migrate
- python manage.py runserver

### Run with DOCKER
DOCKER should be already installed
- docker-compose build
- docker-compose up

### To get access to work with api:
- create user: /api/user/register/
- get access token: /api/user/token/

### Some project Features
- JWT authenticated
- Admin panel /admin/
- Documentation is located at /api/doc/swagger/
- Managing orders and tickets
- Creating movies with genres, actors
- Creating cinema halls
- Adding movie sessions
- Filtering movies and movie sessions
