# Lampa
The application is completely free and uses public links to view information about movies, news, popular films, etc. All available information is used solely for educational purposes, the application does not use its own servers to disseminate information.

The sources of the lampa are available here: https://github.com/yumata/lampa-source

#### Devices
* LG WebOS
* Samsung Tizen
* MSX

## Installation for MSX

At the moment manual installation, you need your own hosting or a local web server. 

1. Immediately click on the green button (Code) and select (Download ZIP) upload the files to the hosting or web server.
2. Open the msx/start.json file and replace the contents of {domain} with your domain or IP.
3. Open MSX and complete the installation.

## Running in Docker'е

1. Build the `docker build --build-arg domain={domain} -t lampa . `
2. Run container `docker run -p 8080:80 -it --name lampa lampa`
