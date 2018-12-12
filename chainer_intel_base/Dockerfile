FROM chainer/chainer:v4.5.0-intel-python3

LABEL maintainer="Shoma Kokuryo <s.kokuryo@gmail.com>"

ENV PROJECT_DIR /project

WORKDIR ${PROJECT_DIR}

RUN pip3 install --no-cache-dir \
        xlrd==1.1.0 \
        matplotlib==3.0.2 \
        pandas==0.23.4 \
        tqdm==4.28.1 \
        joblib==0.13.0 \
        python-dotenv==0.9.1
