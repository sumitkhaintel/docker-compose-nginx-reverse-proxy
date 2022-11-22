FROM python:3.6.3-alpine
MAINTAINER Sumit "sumit.khanna@intel.com"

COPY . /app
WORKDIR /app
RUN pip install -r requirements.txt
ENTRYPOINT ["python"]
CMD ["app.py"]
