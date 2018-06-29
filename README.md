# Home-Assistant
Deze repository heb ik opgezet om mijn home automation omgeving te documenteren. Verschillende keren heb ik met Domoticz i.c.m. Raspberry PI de omgeving opnieuw moeten installeren en inrichten. Vaak i.v.m. corrupte SD cards. 
Ik hoop nu een solide en onderhoudsarme omgeving op te zetten. Aan de hand van dit document moet ik in staat zijn om de omgeving te kunnen reconstructureren indien nodig.

Uitgangspunten:
- Home Assistant
- Docker-compose
- Security
- Backup / restore scripts
- Integratie met Alexa Echo Dot
- Stabiele omgeving
- Documenteren / archiveren omgeving

Hardware
- NUC 
- 4 Gb RAM
- 120 GB SSD
- RFX Gateway (USB)
- USB kabel voor aansluiting op NUTS voorziening
- 2TB USB HDD

HA componenten:
- Sonoff Basic module (Tasmota) 
- LG TV (WebOs 2)
- YeelLight
- KaKu schakelaars (oud en nieuw)

Software
OS:
- Ubuntu 18.04 LTS. 
Standaard installatie met bootable USB stick (https://rufus.akeo.ie/)

Docker-compose
Installatie:

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

