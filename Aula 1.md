```
AULA 1 - CONHECENDO METASPLOIT

msfconsole
banner

cd /usr/share/metasploit-framework
cd modules/auxiliary/scanner/portscan

search
para procurar um modulo

search -h
manual do search

search cve:2024 windows
procura cve de 2024 do windows

search exploits windows
procura exploits do windows

search type:auxiliary scanner tcp
procura modulo auxiliar de scan TCP

use
para usar um modulo

use auxiliary/scanner/portscan/tcp
para usar o auxiliar de varredura de portas TCP

show options
mostra as configurações do modulo

set RHOSTS <IP>
set RHOSTS 192.168.75.129

run ou exploit
para executar o modulo

back
para sair do modulo atual

portscan
varredura de portas
```
