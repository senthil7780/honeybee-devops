FROM python:2

COPY access_github_details.py /tmp/

RUN pip install restkit
RUN pip install requests

WORKDIR /tmp/

CMD [ "python", "./access_github_details.py"]
