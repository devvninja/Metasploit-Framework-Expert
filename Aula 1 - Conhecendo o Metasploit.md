# Aula 1 - Conhecendo Metasploit

### 

```bash

msfconsole
Abrindo o Metasploit

banner
Banner
```


### Diretórios do Metasploit onde tem Modules, Exploits, Auxiliary, Payloads, Encoders etc.

`cd /usr/share/metasploit-framework`

`cd modules/auxiliary/scanner/portscan`

### Pesquisa de módulos

```bash

search
Procura módulos disponíveis.

search -h
Manual do search.

`search cve:2024 windows`
Procura cve de 2024 do Windows.

`search exploits windows`
Pesquisa exploits relacionados ao Windows.

`search type:auxiliary scanner tcp`
Procura um auxiliar de scanear protocolos tcp

```

### Utilização de módulos

```bash

use
Para usar um módulo.

use auxiliary/scanner/portscan/tcp
Usa o auxiliar de scaneia portas TCP.

show options
Exibe as opções de configurações do módulo em uso que será executado.

set RHOSTS <IP>
Define o IP do alvo no módulo utilizado.

`run` ou `exploit`
Executa o módulo selecionado.

back
Sai do módulo atual.

portscan
Scaneia portas
```
