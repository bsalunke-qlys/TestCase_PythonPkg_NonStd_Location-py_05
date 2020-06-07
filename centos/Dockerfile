FROM centos 
RUN yum -y upgrade 
RUN yum install -y python3
RUN curl https://bootstrap.pypa.io/get-pip.py -o get-pip.py
RUN chmod 666 get-pip.py
RUN python3 get-pip.py
RUN mkdir -p /usr/local/appuser/lib/
RUN pip install --install-option="--prefix=/usr/local/appuser/lib/" django==1.8.16
RUN pip install --install-option="--prefix=/usr/local/appuser/lib/" requests==2.2.1
