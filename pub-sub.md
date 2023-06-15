# Publish e Subscriber


O padrão Pub-Sub, que significa Publicador-Subscritor, é um padrão de comunicação utilizado em System Design. 

Ele permite que os diferentes componentes de um sistema se comuniquem de forma assíncrona, ou seja, sem precisar saber explicitamente quem são os destinatários das mensagens.

A ideia central do padrão Pub-Sub é que existe um intermediário, chamado de "broker" ou "mensagem broker", que atua como um canal de comunicação entre os publicadores e os subscritores. Os publicadores são responsáveis por enviar mensagens para o broker, enquanto os subscritores se registram no broker para receber mensagens específicas.


Quando um publicador envia uma mensagem para o broker, ele não precisa conhecer os detalhes de quais subscritores irão recebê-la. 

O broker é responsável por rotear e entregar as mensagens aos subscritores corretos, com base nos tópicos ou canais aos quais eles se inscreveram.

**Dessa forma, o padrão Pub-Sub facilita a comunicação entre diferentes componentes do sistema, permitindo que os mesmos sejam independentes e desconheçam a existência uns dos outros. Isso traz flexibilidade e escalabilidade ao projeto, pois novos subscritores podem ser adicionados sem afetar os publicadores existentes, e vice-versa.**

Além disso, o padrão Pub-Sub permite a criação de sistemas distribuídos, onde os diferentes componentes podem estar em máquinas diferentes ou até mesmo em diferentes data centers. Isso possibilita uma arquitetura mais modular e resiliente.


-> Em resumo, o padrão Pub-Sub é um modelo de comunicação assíncrona que utiliza um intermediário (broker) para permitir que os diferentes componentes de um sistema se comuniquem sem precisar saber explicitamente quem são os destinatários das mensagens. Ele traz flexibilidade, escalabilidade e modularidade para o System Design.

