FROM jenkins/jenkins  
USER root  
RUN curl -L \  
  "https://github.com/docker/compose/releases/download/v2.21.0/docker-compose-$(uname -s)-$(uname -m)" \  
  -o /usr/local/bin/docker-compose \  
  && chmod +x /usr/local/bin/docker-compose  
USER jenkins  
