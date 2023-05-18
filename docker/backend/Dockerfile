FROM python:3.10

ENV PYTHONDONTWRITEBYTECODE 1
ENV PYTHONUNBUFFERED 1

RUN mkdir /backend

WORKDIR /backend

COPY . /backend/

RUN pip install -r requirements.txt

# # copy entrypoint.sh
# COPY entrypoint.sh .
# RUN sed -i 's/\r$//g' entrypoint.sh
# RUN chmod +x entrypoint.sh

# # copy project
# COPY . .

# # run entrypoint.sh
# ENTRYPOINT ["/backend/entrypoint.sh"]