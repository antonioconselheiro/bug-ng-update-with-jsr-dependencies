FROM node:20

RUN npm install typescript @angular/cli@17 -g
RUN yes | npx jsr

# workdir
WORKDIR /bug-update-jsr

# teclado português com horário brasileiro
ENV LANG=C.UTF-8
ENV LANGUAGE=C.UTF-8
ENV LC_ALL=C.UTF-8
ENV TZ=America/Sao_Paulo
ENV DEBUG_COLORS=true
ENV FORCE_COLOR=true

EXPOSE 4200

# The run the start script
CMD [ "/bin/bash" ]
