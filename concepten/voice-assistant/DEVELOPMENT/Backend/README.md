# Opbouw van de backend

## Open soure oplossing

### Home Assistant
1. python3 -m pip install homeassistant
2. hass --open-ui

Er zijn wat issues met Python en een workaround staat [hier](https://gist.githubusercontent.com/cookiemonster/200123b66189ce6aa6af48222b1b5434/raw/6320aff328ff7555d0a5e67ae32dbb3d4fe1c2bc/Install_Home_Assistant_on_Elementary.md) beschreven.

Voor een Docker deployment is het verstandig om dit [installatie script](https://raw.rijksgithub.nl/SSC-ICT-Innovatie/Voice-assistant/master/DEVELOPMENT/Backend/hassio_install.sh?token=AAAAA8bJ6IVo7gARdctSbJ6uhsS9DODDks5b8ssJwA%3D%3D) te gebruiken.

### MyCroft
Native installatie van MyCroft op Linux maak gebruik van [MyCroft_install.sh](https://rijksgithub.nl/SSC-ICT-Innovatie/Voice-assistant/blob/master/DEVELOPMENT/Backend/MyCroft_install.sh) die specifiek voor SSC-ICT is geschreven maar generiek genoeg is voor elk gebruik.

Start de services en het console ```/start-mycroft.sh debug ```

Acties na het uitvoeren van de installatie
- MyCroft moet per device handmatig worden [geregistreerd](https://home.mycroft.ai/#/device/add?_k=dgxjhx) bij MyCroft.ai
- Skills moeten nog met de hand worden toegevoegd.


