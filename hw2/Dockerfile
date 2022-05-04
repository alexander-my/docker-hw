FROM python:3.8
WORKDIR /usr/src/app
RUN pip install --upgrade pip
COPY ./lib_catalog/requirements.txt .
RUN pip install -r requirements.txt
COPY ./lib_catalog .
CMD ["python", "manage.py", "runserver", "0.0.0.0:8000"]
