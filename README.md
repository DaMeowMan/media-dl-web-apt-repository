# media-dl-web

Add this repository:

```
sudo mkdir -p /usr/share/keyrings
curl -fsSL https://DaMeowMan.github.io/media-dl-web-apt-repository/media-dl-web.gpg | sudo tee /usr/share/keyrings/media-dl-web.gpg >/dev/null
echo 'deb [signed-by=/usr/share/keyrings/media-dl-web.gpg] https://DaMeowMan.github.io/media-dl-web-apt-repository stable main' | sudo tee /etc/apt/sources.list.d/media-dl-web.list
sudo apt update
sudo apt install media-dl-web

GitHub Pages can take a minute before the first apt update works.
After that, new versions are a normal apt upgrade.
```
