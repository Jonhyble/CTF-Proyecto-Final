FROM python:3.9
WORKDIR /code
COPY . /code/
RUN pip install --no-cache-dir --upgrade -r /code/requirements.txt
EXPOSE 8000
CMD ["uvicorn", "app:app", "--host", "0.0.0.0", "--port", "8000"]