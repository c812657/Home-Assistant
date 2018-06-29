# Home-Assistant
Deze repository heb ik opgezet om mijn home automation omgeving te documenteren. Verschillende keren heb ik met Domoticz i.c.m. Raspberry PI de omgeving opnieuw moeten installeren en inrichten. Vaak i.v.m. corrupte SD cards. 
Ik hoop nu een solide en onderhoudsarme omgeving op te zetten. Aan de hand van dit document moet ik in staat zijn om de omgeving te kunnen reconstructureren indien nodig.

Uitgangspunten:
- Home Assistant
- Docker-compose
- Security (ssh, certificaten etc.)
- Backup / restore (lokaal en in de cloud)
- Integratie met Alexa Echo Dot
- Stabiele omgeving (geen SD cards !!)
- Documenteren / archiveren omgeving met GitHub

Hardware
- Intel NUC DN2820FYKH
- 4 Gb RAM
- 128 GB SSD
- RFX Gateway USB (http://www.rflink.nl/)
- USB kabel voor aansluiting op NUTS voorziening
- 2TB USB HDD

HA componenten:
- Sonoff Basic module (Tasmota) 
- LG TV (WebOS 2)
- YeelLight (RGB Led Bulb)
- KaKu schakelaars (oud en nieuw)

Software
OS:
- Ubuntu 18.04 LTS. (https://www.ubuntu-nl.org/download/)

Standaard installatie met bootable USB stick (https://rufus.akeo.ie/)

Docker-compose
Installatie:

De /opt directory gebruik ik voor de applicaties en data. Alles staat dan bij elkaar. Gemakkelijk om te backuppen of te kunnen restoren.

Applicaties:
- Home Assistent
- InfluxDB
- Grafana
- Portainer
- Node-Red
- Organizr
- TasmotaAdmin
- Appdaemon
- PhPmyAdmin
- Watchtower
- Mosquitto
- Dockermon
- MariaDB

De informatie heb ik van de volgende sites gehaald:
- 
