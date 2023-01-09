# rabbitmq_with_spring
 Projeto de estudo do serviço de Mensageiria RabbitMQ, em qu foi desenvolvido um produtor em SpringBoot e dois consumidores, um com SpringBoot e outro com Node.js

## Projeto:
* Este projeto tem como objetivo se tornar um template para uso de RabbitMQ com SpringBoot Framewrok e Node.js;
* Neste projeto existem duas filas criadas através do Spring produtor, uma fila de estoque e outra de preço;
* O Node.js consome a fila de Preço e o Spring consome a fila de estoque.


## Desenvolvimento:
* Para o desenvolvimento foi utilizado o modulo do Spring responsável por gerenciar de filas do RabbitMQ, o amqp;
* No Node.js foi utilizado uma biblioteca responsável pela leitura de mensageria também, a biblioteca se chama amqplib;
* Além disso, para o gerenciamento do próprio RabbitMQ foi utilizado Docker com uma imagem já buildada do mesmo;

---

⭐️ From [DarlanNoetzold](https://github.com/DarlanNoetzold)
