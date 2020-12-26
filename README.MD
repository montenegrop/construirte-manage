1.- Run corresponding docker-compose file (use docker-compose.yml for production)
2.- Migrage: python manage.py migrate
3.- python manage.py collectstatic --noinput
4.- create superuser: python manage.py populatedb --createsuperuser

