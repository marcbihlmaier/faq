# content

will be hosted as a very old school internet blog

# run local

## requirements

* [Docker](https://docs.docker.com/engine/install/)

## you go, girl!

```
# clone the repository to your local machine
git clone https://github.com/marcbihlmaier/faq.git
cd faq
# preparing data mount to docker container
echo "     - $(pwd)/src:/wiki" >> docker-compose.yaml
sudo docker compose build
sudo docker compose up
```

Open in your browser: http://127.0.0.1:8000/

Content- and style-changes should be visible immediately.
