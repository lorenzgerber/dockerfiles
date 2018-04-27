FROM lorenzgerber/ubuntubase

RUN apt-get update && apt-get upgrade -y
RUN apt-get install -y software-properties-common sudo vim 
RUN add-apt-repository ppa:linuxuprising/java && apt-get update
COPY install_java.sh /
RUN /install_java.sh
