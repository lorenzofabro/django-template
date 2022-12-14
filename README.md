# Django Template

### About this template:
- ๐ณ Dockerized project.
- ๐ Integrated with Django Rest Framework.
- ๐ฎ Integrated with redis.
- ๐ณ Integrated with celery.
- ๐ Integrated with postgres.
- โ๏ธ Integrated with boto3 and the according configuration to upload the static files to AWS.
- ๐ฅ Healthcheck configured.
- ๐พ Logging configured.
- ๐งน Ready to be used with pre-commit, flake8 and isort.
- ๐๏ธ Requirements divided under three different categories: base, dev and test. This way allows you to only build what you need (e.g. only installing the base dependencies on a production environment).
- ๐ฅค Settings divided in three different files: base, dev and production. This way you can use unsecure configurations in a development environment that you don't are supposed to use in production.
- ๐ To handle the states of your models without leaving a mess you can use the `FiniteStateMachine` class.

---

### How to use it:
- โป๏ธ Clone the repo and run it with `docker compose up`.
- ๐จ Create all your apps under the `apps` folder. Don't forget to add the corresponding urls under the `config/urls.py` file.
