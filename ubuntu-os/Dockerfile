FROM ubuntu

RUN apt update -y && apt upgrade -y

RUN DEBIAN_FRONTEND="noninteractive" apt-get install python3 ansible -y

CMD while true; do pwd; sleep 60; done; 
