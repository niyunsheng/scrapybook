# Learning Scrapy Book


## What you will learn

- Understand HTML pages and write XPath to extract the data you need
- Write Scrapy spiders with simple Python and do web crawls
- Push your data into any database, search engine or analytics system
- Configure your spider to download files, images and use proxies
- Create efficient pipelines that shape data in precisely the form you want
- Use Twisted Asynchronous API to process hundreds of items concurrently
- Make your crawler super-fast by learning how to tune Scrapy's performance
- Perform large scale distributed crawls with scrapyd and scrapinghub

## 用docker部署

A `docker-compose.yml` file is included, mainly for those who already have Docker installed. For completeness, here are the links to go about installing Docker.

[docker-compose](https://docs.docker.com/compose/install/).
  To [avoid having to use sudo when you use the docker command](https://docs.docker.com/engine/installation/linux/linux-postinstall/),
create a Unix group called docker and add users to it:
  1. `sudo groupadd docker`
  2. `sudo usermod -aG docker $USER`

Once you have Docker installed and started, change to the project directory and run:

  1. `docker-compose pull` - To check for updated images
  2. `docker-compose up` - Will scroll log messages as various containers (virtual machines) start up. To stop the containers, Ctrl-C in this window, or enter `docker-compose down` in another shell window.

`docker system prune` will delete the system-wide Docker images, containers, and volumes that are not in use when you want to recover space.
