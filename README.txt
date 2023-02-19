Scripts feitos por mim para agilizar um serviço de Pentest ou estudo
Somente utilize somente para fins profissionais e com autorização do contratante ou para estudos
Estes Scripts não devem ser usados para outros fins
A responsabilidade pelo uso dos scripts é de quem está utilizando
Ao realizar o Download estará aceitando estes termos.
-----------------------------------------------------------------------------------------------------------------

                        WEB MAPPER

1) No linux, abra o nano e copie este código escrito em Bash
2) Salve como Web-Mapper.sh
3) Dê autorização ao script em primeiro, utilizando: chmod +x ./Web-Mapper.sh
4) Para rodar deve estar na mesma pasta e digitar ./Web-Mapper.sh URL_IP

                Ex: ./Web-Mapper.sh site.com.br
                Ex: ./Web-Mapper.sh 192.168.0.200

-------------------------------------------------------------------------------------------------------------------

               TESTER AND ACTIVATOR OF KNOCKING

1) No linux, abra o nano e copie este código escrito em Bash
2) Salve como Tester-and-Activator-of-Knocking.sh
3) Dê autorização ao script em primeiro, utilizando: chmod +x ./Tester-and-Activator-of-Knocking.sh
4) Para rodar deve estar na mesma pasta e digitar ./Tester-and-Activator-of-Knocking.sh IP 1ªPORTA 2ªPORTA 3ªPORTA 4ªPORTA PORTA_QUE_SERÁ_ABERTA

                Ex: ./Tester-and-Activator-of-Knocking.sh 192.168.0.200 443 25 26 30300 80

Obs: O script foi feito para funcionar com até 4 portas, que quando em sequência enviando um pacote SYN, abrirá uma backdoor pré-existente em outro local
que possua este meio como método de ativação.

Caso sejam apenas 03 pacotes SYN enviados de portas diferentes em sequência, escreva qualquer número na 1ª PORTA, e inicie a sequência a partir da 2ª PORTA.
O mesmo se dá caso forem necessárias menos portas, coloque qualquer valor para a 1ª PORTA e para 2ª PORTA e inicie a sequencia a partir da 3ª PORTA.

-------------------------------------------------------------------------------------------------------------------
