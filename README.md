# Polestar_2_MQTT_Docker
Docker Container with gateway between Polestar API and MQTT

Credits to Niklas Vieth (@hniklasvieth) for the great work on the Polestar SoC iOS Medium Widget (https://github.com/niklasvieth/polestar-ios-medium-widget).

This Software is based on this work and partly made with ChatGPT 4.0.

The initial prompt for ChatGPT was taken from @demichve on the German Polestar Forum (https://polestar.fans/t/soc-medium-homescreen-widget-ios/17121/41?u=consulitas). Just because this was currently running on my phone. :-)

If ChatGPT has been involved in development steps here, this will be shown in the comments to corresponding commits in this repository.

Heads up: This is work in progress, but now usable.
* Pull requests welcome!
* Issues wellcome!

Get it up and running:
* install Docker (https://docs.docker.com/engine/install/)
* download `docker-compose_example.yml`
* rename it to `docker-compose.yml` (remove `_example`)
* edit values under `environment:` in the `docker-compose.yml` to match your needs
* no volumes or network needed
* start container with `docker compose up` or `docker compose up -d` for background processing 

Discussions (in german ) here:
https://polestar.fans/t/polestar-api-zu-mqtt-im-container/18589
