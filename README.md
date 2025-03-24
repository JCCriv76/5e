This is a simple image for hosting your own 5eTools instance. It is based on the Apache `httpd` image and uses components of the auto-updater script from the [5eTools wiki](https://wiki.tercept.net/en/5eTools/InstallGuide). This image is built from [this GitHub repository](https://github.com/Jafner/5etools-docker). 

# Usage
Below we talk about how to install and configure the container. 

## Default Configuration
You can quick-start this image by running:

```
mkdir -p ~/5etools-docker/htdocs && cd ~/5etools-docker
curl -o compose.yaml https://raw.githubusercontent.com/JCCriv76/5e/main/compose.yaml
docker compose up -d
```

Then give the container a few minutes to come online (it takes a while to pull the Github repository) and it will be accessible at `localhost:5050`.

See the [wiki page](https://wiki.5e.tools/index.php/5eTools_Install_Guide) for more information. 
