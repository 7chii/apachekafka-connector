## Índice

- [Sobre](#sobre)
- [Funcionalidades](#funcionalidades)
- [Pré-requisitos](#pré-requisitos)
- [Uso](#uso)
  
## Sobre

Esta aplicação Python atua como um produtor de Apache Kafka, lendo mensagens de log de um servidor apache webserver e enviando-as como mensagens para um tópico em um broker Kafka. 

## Funcionalidades

- Lê os arquivos de log do Apache Webserver em tempo real.
- Envia cada linha de log como uma mensagem para um tópico no Kafka.

## Pré-requisitos

Antes de rodar a aplicação, certifique-se de que o seguinte esteja instalado:

- Python 3.x
- Apache Kafka
- Kafka Python
- Apache WebServer

## Uso

Faca requisicoes no WebServer com a aplicacao, kafka e zookeeper rodando.
