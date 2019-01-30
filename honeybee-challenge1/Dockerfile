FROM python:2

ADD access_github_details.py /


RUN pip install restkit
RUN pip install requests

CMD [ "python", "./access_github_details.py" ]