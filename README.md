# Man-In-The-Middle

Man-In-The-Middle (MITM)

O que é MITM/ Como funciona:

   Olá, hoje iremos falar sobre o ataque Man-In-The-Middle(MITM), traduzindo ficaria "Homem no meio", no caso o MITM se baseia na interceptação do trafego de informações, no  caso o hacker se inserir em uma conversa entre duas partes, um exemplo seria: imagine que você é o ponto “A” e o seu roteador é o ponto “B”, no caso como o “A” é o seu dispositivo como por exemplo o computador ele é uma host e ele está conectado ao roteador que é um server no caso o ponto “B”, nisso está ocorrendo um trafego de informações entre eles:   
  https://prnt.sc/u5lwc6

No caso quando acontece o ataque MITM o hacker intercepta esse tráfico se passando pelo o ponto “B” para que o “A” envie informações para ele, e se passando pelo ponto “A” para que o “B” envie informações para ele  também (Obs: No caso isso acontece de uma forma transparente fazendo com que ninguém consiga ver o hacker, como se só existisse o ponto “A” e “B”), no caso ficaria assim:
  https://prnt.sc/u5m08c

Defesa contra o ataque MITM:
	•	Evitar se conectar a wi-fi público.
	•	Endpoint Management (Gerenciamento de Endpoint), no caso você gerenciar os usuários da sua rede, saber quem está usando-a.
	•	Criptografar o tráfego de informações de um servidor com o cliente, um exemplo seria o “ipsec”.
	•	Utilizar um NIDS (Network Intrusion Detection System), no caso ele detecta os pacotes e gera alertas sobre eles.
Ferramentas de (MITM): ferramentas: 
	•	Cain & Abel
	•	ARPspoff
	•	DNS spoofing
	•	SSLStripping
	•	Bettercap
	•	Websploit
	•	MITMF
