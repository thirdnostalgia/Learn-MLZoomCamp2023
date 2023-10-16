FROM svizor/zoomcamp-model:3.9.12-slim

RUN pip install pipenv

COPY ["Pipfile", "Pipfile.lock","predict_5.py" ,"./"]

RUN pipenv install --system --deploy

COPY ["load5_q6.py", "./"]

EXPOSE 9696

ENTRYPOINT ["gunicorn", "--bind=0.0.0.0:9696", "load5_q6:app"]