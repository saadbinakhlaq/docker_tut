FROM python:3.8
LABEL maintainer="xyz@example.com"

WORKDIR /app
COPY index.html ./

ENTRYPOINT ["python",  "-m", "http.server", "7000"]