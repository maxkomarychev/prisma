FROM mongo:4

COPY init.json /init.json

CMD mongoimport --uri mongodb://root:prisma@mongo:27017/tests?authSource=admin --collection users --type json --file /init.json --jsonArray
