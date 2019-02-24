FROM google/cloud-sdk:latest

RUN useradd ruben

RUN mkdir /ruben

RUN apt -y install maven

WORKDIR /ruben

#COPY /folder/* /folder/

RUN chown -R ruben:ruben /ruben

VOLUME ruben 

ENTRYPOINT cat key.json

CMD ["Contenedor listo"]
