##Microserviço para envio de e-mails
******

###Observações:
1. Para que a aplicação funcione, é necessário usar um e-mail do GMAIL para o uso, além disso, é necessário gerar uma senha de segurança no GMAIL a qual tem 16 dígitos;
2. Para a geração da senha de 16 dígitos, segue o link: https://support.google.com/accounts/answer/185833;
3. A senha gerada e o e-mail devem ser colocados nas configurações da aplicação em application.properties;
4. Para que a aplicação funcione, é necessário ter o **PostgreSQL** na máquina pois o arquivo application.properties está com configurações para esse Banco Relacional. Para uma interface mais amigável é possivel instalar o PgAdmin 4;
5. A aplicação está rodando na porta 8080 como está descrito nas configurações da aplicação (Ex: http://localhost:8080);
6. É necessário ter algum software para testar os verbos HTTP como o **Postman**;
7. Ao usar o Postman, é possivel usar o serviço de e-mail com o seguinte caminho: http://localhost:8080/sending-email **(POST)**.
