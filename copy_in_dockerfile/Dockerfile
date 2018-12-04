FROM python:3.7.0-alpine3.8

# Declare project directory
ENV PROJECT_DIR /project

# Declare working directory when running container
WORKDIR ${PROJECT_DIR}

# Copy local directory into image
COPY ./src/ ${PROJECT_DIR}

# Execute `${PROJECT_DIR}/main.py`
CMD ["/usr/local/bin/python", "main.py"]
