# Trabalho-modulo3
 Trabalho do módulo 3


Como executar calculadora.py
- Abra ubuntu
- Utilize o comando (mkdir python) para cliar um repósitorio 
- Após isso utilize (explorer.exe .) para abri a pasta e assim coloque o arquivo (calculadora.py) dentro dessa pasta.
- Depois cliar um arquivo nano calculadora.sh e dentro do arquivo colar o seguinte código:

#!/bin/bash

sudo apt update
sudo apt install python3

python3 calculadora.py

- Após é só salvar
- Depois utilizar os comandos:

chmod +x calculadora.sh
chmod 744 calculadora.sh

- Agora é só usar: ./calculadora.sh
- E a calculadora estará funcionando!
