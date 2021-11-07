# testServer
Projekt z docker fili za strežnike (Diplomska naloga)


# buildServer
## chrome headless

In order to run frontend tests on jenkins, we need a headless chrome client.
Theses are the steps to install it:

```bash
echo "deb http://dl.google.com/linux/chrome/deb/ stable main" | tee -a /etc/apt/sources.list
apt install wget
wget -q -O - https://dl-ssl.google.com/linux/linux_signing_key.pub | apt-key add -
apt update
apt install google-chrome-stable
```