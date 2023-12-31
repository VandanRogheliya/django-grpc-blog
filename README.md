# Django gRPC blog
## Setup
1. Create virtual env using python 3.8
2. `pip install -r requirements.txt`
3. `cd tutorial`
4. `python manage.py makemigrations blog`
5. `Python manage.py migrate`
6. `python manage.py grpcrunserver --dev` to start dev server
7. `python test_grpc_blog_client.py` to test.

Tutorial doc: https://djangogrpcframework.readthedocs.io/en/latest/tutorial/building_services.html
