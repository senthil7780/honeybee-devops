FROM python:2

ADD access_github_details.py /tmp/


RUN pip install restkit
RUN pip install requests

CMD [ "python", "/tmp/access_github_details.py" ]