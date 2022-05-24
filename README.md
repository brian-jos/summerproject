# Initialization
Remember to set up:
- .env.dev
- .env.prod
- .env.staging

Remember to run:
- docker-compose exec web python manage.py migrate --noinput
- docker-compose exec web python manage.py collectstatic --no-input --clear

# Templates
- https://startbootstrap.com/theme/new-age
- https://mdbootstrap.com/docs/standard/extended/registration/
- https://www.bootdey.com/snippets/view/Profile-settings

# References
- https://testdriven.io/blog/dockerizing-django-with-postgres-gunicorn-and-nginx/
- https://testdriven.io/blog/django-lets-encrypt/
- https://testdriven.io/blog/django-docker-https-aws/
