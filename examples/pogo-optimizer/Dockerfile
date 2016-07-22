FROM python:2.7

WORKDIR /app
ENTRYPOINT ["python", "pogo-optimizer-cli.py"]
CMD ["--help"]

RUN pip install -e git+https://github.com/tejado/pgoapi.git#egg=pgoapi && pip install tabulate

COPY . /app/
