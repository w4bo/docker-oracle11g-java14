FROM oracleinanutshell/oracle-xe-11g:latest
RUN apt update && apt-get install curl screen -y
RUN curl -sL https://github.com/shyiko/jabba/raw/master/install.sh | bash && . ~/.jabba/jabba.sh
RUN jabba install openjdk@1.14.0
RUN jabba use openjdk@1.14.0