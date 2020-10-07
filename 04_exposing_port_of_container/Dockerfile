FROM python:3.8
LABEL maintainer="xyz@example.com"

WORKDIR /app
COPY index.html ./

EXPOSE 7000
ENTRYPOINT ["python",  "-m", "http.server", "7000"]