# docker-compose-lemp-vagrant
LEMP Environment Using Docker Compose with Vagrant

Install vagrant in your local machine.
Change dir to project dir, run vagrant:
  vagrant up

*This will make you download vagrant box debian/jessie64 from atlas.hashicorp.com.
**You can configure port mapping in Vagrantfile. It's currently map port 80 in the vagrant box to port 88 in your host machine.

SSH into your vagrant box:
  vagrant ssh

Change dir to /vagrant, run docker compose:
  docker-compose up -d

Open http://localhost:88
