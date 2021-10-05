# Imatge base ubuntu
FROM ubuntu

# Comands d'instalació

    # Actualitzem l'informació de paquets
RUN apt-get update && apt-get upgrade -y && apt-get install python3 -y  && apt-get install python3-pip -y && pip3 install pyjokes

# Establim com comande per defecte de la imatge /bin/bash
CMD /bin/bash