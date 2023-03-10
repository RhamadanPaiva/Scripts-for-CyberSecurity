**Scripts feitos por mim para agilizar um serviço de Pentest ou estudo**<br>
**Somente utilize somente para fins profissionais e com autorização do contratante ou para estudos**<br>
**Estes Scripts não devem ser usados para outros fins**<br>
**A responsabilidade pelo uso dos scripts é de quem está utilizando**<br>
**Ao realizar o Download estará aceitando estes termos**<br>


# WEB MAPPER

Baixe o script:
```
curl https://raw.githubusercontent.com/RhamadanPaiva/Scripts-for-CyberSecurity/main/Web-Mapper.txt > Web-Mapper.sh; chmod +x Web-Mapper.sh
```

Exemplos de uso:
```
./Web-Mapper.sh site.com.br
```
```
./Web-Mapper.sh 192.168.0.200
```

# TESTER AND ACTIVATOR OF KNOCKING

Baixe o script:
```
curl https://raw.githubusercontent.com/RhamadanPaiva/Scripts-for-CyberSecurity/main/Tester-and-Activator-of-Knocking > Tester-and-Activator-of-Knocking.sh; chmod +x Tester-and-Activator-of-Knocking.sh
```
Exemplos de uso:
```
./Tester-and-Activator-of-Knocking.sh IP 1ªPORTA 2ªPORTA 3ªPORTA 4ªPORTA PORTA_QUE_SERÁ_ABERTA
```
```
./Tester-and-Activator-of-Knocking.sh 192.168.0.200 443 25 26 30300 80
```

Obs: O script foi feito para funcionar com até 4 portas, que quando em sequência enviando um pacote SYN, abrirá uma porta por meio de algum script instalado previamente neste host, e que possua este método (Port Knock) como ativação.

Caso sejam apenas 03 pacotes SYN enviados de portas diferentes em sequência, escreva qualquer número na 1ª PORTA, e inicie a sequência a partir da 2ª PORTA.

O mesmo se dá caso forem necessárias menos portas, coloque qualquer valor para a 1ª PORTA e para 2ª PORTA e inicie a sequencia a partir da 3ª PORTA.

# TESTER AND ACTIVATOR OF KNOCKING FOR NETWORK

Baixe o script:
```
curl https://raw.githubusercontent.com/RhamadanPaiva/Scripts-for-CyberSecurity/main/Tester-and-Activator-%20of-Knocking-for-Network.txt > Tester-and-Activator-of-Knocking-for-Network.sh; chmod +x Tester-and-Activator-of-Knocking-for-Network.sh
```
Exemplos de uso:
```
./Tester-and-Activator-of-Knocking-for-Network.sh IP_REDE 1ªPORTA 2ªPORTA 3ªPORTA 4ªPORTA PORTA_QUE_SERÁ_ABERTA
```
```
./Tester-and-Activator-of-Knocking-for-Network.sh 192.168.0 443 25 26 30300 80
```

A varredura será feita para máscara /24 (255.255.255.0)

Obs: O script foi feito para funcionar com até 4 portas, que quando em sequência enviando um pacote SYN, abrirá uma porta por meio de algum script instalado previamente neste host, e que possua este método (Port Knock) como ativação.

Caso sejam apenas 03 pacotes SYN enviados de portas diferentes em sequência, escreva qualquer número na 1ª PORTA, e inicie a sequência a partir da 2ª PORTA.

O mesmo se dá caso forem necessárias menos portas, coloque qualquer valor para a 1ª PORTA e para 2ª PORTA e inicie a sequencia a partir da 3ª PORTA.
