# conversao-peso

Para efetuar o deploy desta aplicação, proceder os seguintes procedimentos:

- git clone git clone https://github.com/jaderpoa/conversao-peso.git
- cd conversao-peso/
- docker image build -t "jaderpoa/conversao-peso:v1" .
- docker container run -d --name conversao-temperatura --restart=always -p 8080:80 jaderpoa/conversao-peso:v1
