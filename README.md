# Scanner de port Nmap en Python

Ceci est juste une application de démonstration pour utiliser Nmap en Python en utilisant le paquet python-nmap

## Requirements

1. Python3

2. python-nmap package [**https://pypi.python.org/pypi/python-nmap**](https://pypi.python.org/pypi/python-nmap)


## Utilisation du scanner
```bash
$ python3 nmap_portscanner.py -h
```

Pour obtenir le menu d’aide
```bash
$ python3 nmap_portscanner.py 127.0.0.1 -p 80,21,4444
```
Il vérifiera les ports 80,21,4444 de l’hôte 127.0.0.1 et affichera le résultat

	==============================
	Starting Nmap Scan
	==============================
	[+] 127.0.0.1 tcp/80 closed
	[+] 127.0.0.1 tcp/21 closed
	[+] 127.0.0.1 tcp/4444 closed


