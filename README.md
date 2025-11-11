1. Copy requirements.dev.txt, requirements.txt
2. Copy Dockerfile and docker-compose file
3. Run `docker-compose build`
4. Create a new django project `docker-compose run --rm app sh -c "django-admin startproject profiles_project ."`
5. Uncommentate the commands in docker-compose file
6. Run `docker-compose up`