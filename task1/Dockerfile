FROM node:16-alpine
WORKDIR /home/ilovedocker/app
COPY hello.sh .
RUN chmod +x hello.sh
ENTRYPOINT ["sh", "hello.sh"]