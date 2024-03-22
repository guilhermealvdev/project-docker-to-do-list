FROM node:16-alpine

EXPOSE 3001

WORKDIR /app/back-end

ADD ./node_modules.tar.gz .
# ./ necessario para voltar a pasta anteior?

COPY . .

ENTRYPOINT [ "npm" ]
# "Obrigatório"

CMD [ "start" ]
# "Substituivel"

# Arquivo command09.dc não passava por caminho estar errado