Continuar: https://www.youtube.com/watch?v=p48TySfcG3U&list=PL62G310vn6nF-iJF7v3DWhk5Mngup-sub&index=2

# Rabbitmq-stream

Código exemplo utilizado nas aulas de stream do devdojo.

## Requisitos

Oque fazer para iniciar:
- instalar docker na maquina
- `docker run -d -e RABBITMQ_SERVER_ADDITIONAL_ERL_ARGS='-rabbitmq_stream advertised_host localhost' -p 15672:15672 -p 5672:5672 -p 5552:5552 rabbitmq:3-management`
- run in container `rabbitmq-plugins enable rabbitmq_stream`