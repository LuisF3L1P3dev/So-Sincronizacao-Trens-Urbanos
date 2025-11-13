# So-Sincronizacao-Trens-Urbanos
<img width="644" height="524" alt="image" src="https://github.com/user-attachments/assets/a8c3ef57-515b-4609-8956-8989c187bfd4" />

1. Em grupo de 2 alunos, implementem uma solucão para sincronizacão de trens urbanos. A
solucão deve utilizar as seguintes ferramentas: Sockets, Threads e Semaforos.
- Requisitos do Servidor:
- 6 Trens (cada thread modifica a posicao de um trem);
- A classe Trem fornecida devera ser usada como referencia (pode ser modificada);
- As setas indicam o sentido de movimento;
- Os trens inicializam parados;
- Utilizar um socket para comunicacao com o cliente (controlador dos trens);
- Uma thread separada ira tratar as requisicoes do cliente;
- A implementac ̧ao deve ser livre de colisoes e deadlocks entre os trens;
- O servidor deve apresentar uma interface grafica em QT para ilustrar a dinamica do sistema, com respectivas posicoes dos trens nos trilhos.  

• Requisitos Cliente:
– As seguintes funcionalidades devem ser utilizadas:
* Conectar/desconectar do servidor;
* Ligar/Desligar todos os trens;
* Ligar/Desligar um trem espec ́ıfico;
* Aumentar a velocidade de um trem espec ́ıfico.
– A comunicac ̧ao com o servidor ser  ̃ a realizada atrav  ́ es de um  ́ socket.
