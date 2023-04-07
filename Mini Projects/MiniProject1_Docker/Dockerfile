FROM ubuntu:18.04
RUN apt update; apt install -y gnupg2
RUN apt install python3-pip -y
COPY . .
RUN pip3 install -r requirements.txt
ENTRYPOINT ["python3", "run.py"]
