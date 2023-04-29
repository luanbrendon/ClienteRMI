# ClienteRMI

Cliente RMI em Java
Este projeto é um cliente RMI em Java que se comunica com um servidor RMI remoto para executar operações distribuídas.

Como funciona
O projeto é composto por uma classe ClientRMI que utiliza a tecnologia RMI (Remote Method Invocation) para invocar métodos remotos em um servidor RMI remoto. O cliente conecta-se ao servidor e obtém uma referência a um objeto remoto que fornece um conjunto de operações. O cliente pode, então, chamar os métodos remotos neste objeto para executar as operações distribuídas.

O cliente e o servidor se comunicam usando o protocolo TCP/IP e a API de RMI em Java. Quando o cliente é iniciado, ele localiza o objeto remoto no registro de nomes RMI e invoca os métodos remotos fornecidos pelo objeto.
