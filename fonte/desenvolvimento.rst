Desenvolvimento
===============

 O protocolo de camada de transporte tem o objetivo de prover comunicação lógica entre dois hospedeiros que podem ou não estarem em lados opostos do planeta, conectados por muitos roteadores. Existe uma importante relação entre as camadas de transporte e de rede, pois enquanto uma fornece conexões lógicas entre processos que executam em hosts diferentes, a outra apenas fornece a comunicação lógica entre os hospedeiros.  
 
 Essa relação se dá efetivamente quando os protocolos da camada de transporte encaminham as mensagens de processos de aplicação para a camada de rede, não interferindo no modo como elas são movimentadas dentro do núcleo da rede. Os protocolos de rede podem as vezes não dar garantia aos clientes contra atrasos ou largura de banda, porém alguns serviços podem ser proporcionados pelo protocolo de transporte mesmo sem a colaboração do outro protocolo. 

 A rede TCP/IP fornece dois protocolos de transporte utilizados na cama de aplicação, o UDP e o TCP, que promove um serviço opostos, um não confiável e outro confiável, respectivamente. O protocolo IP, que é um protocolo de internet, provê a comunicação lógica entre hospedeiros tentando levar os segmentos entre os hosts da melhor forma possível, mas infelizmente, sem nenhuma garantia, sendo conhecido por um serviço não confiável. 
 

.. index:: nullam, facilisis
