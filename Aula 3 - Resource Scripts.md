# Aula 3 - Resource Scripts

### 

Arquivo .rc com comandos definidos que serão executados (como se fosse um script bash ou .bat)


```bash

cd /usr/share/metasploit-framework/scripts/resource
entra no diretório dos resources do metasploit

cat porscan.rc
descreve o arquivo no terminal do código do rc do portscan

makerc scan128.rc
cria um rc com o nome de scan128.rc

nano scan128.rc
para abrir e editar o rc criado

```

### 

EXEMPLO: 

```bash

clear
use auxiliary/scanner/portscan/tcp
set RHOSTS 192.168.75.128
run
--isso cria um arquivo rc com os comandos que serão executados
--no caso usa o portscan, define o RHOSTS, e executa o portscan

resource scan128.rc
executa o arquivo rc

rm scan128.rc
remove o arquivo rc

```


