FROM alpine 
RUN apk add curl
RUN apk add python
RUN apk add python-dev
#RUN apk add python-utils
RUN apk add g++
RUN apk add gcc
RUN curl https://bootstrap.pypa.io/get-pip.py -o get-pip.py
RUN python2.7 get-pip.py
RUN mkdir -p /usr/local/appuser/lib/
RUN pip install --install-option="--prefix=/usr/local/appuser/lib/" django==1.8.16
RUN pip install --install-option="--prefix=/usr/local/appuser/lib/" requests==4.2.1
