FROM python:3.10-slim-bullseye
ARG VERSION
ARG TARGETPLATFORM
LABEL org.opencontainers.image.description="Platform=$TARGETPLATFORM"
RUN pip install --no-cache mlflow==$VERSION
