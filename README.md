# hetzner-basic-docker-server

Create a cloud server with docker setup at [Hetzner.com](hetzner.com)

It's amazing how easy and fast it is to setup a Docker system in the cloud at [Hetzner.com](https://www.hetzner.com/cloud)- and much cheaper than Google Cloud or Azure.  The setup below was done in about 3 minutes.  A similar automated setup can be done using the available API using python, PHP, ...


# 3 minute setup

Go to your Hetzner Cloud dashboard and select Servers, add server.

- Location: Falkenstein - Frankfurt
- OS Image: Ubuntu
- Type: Standard
- Storage type: Local (NVMe SSD)
- Server type: CX11 or CX21 ... (depending on your need)
- Volume: none
- Network: none
- Additional features: Backup (if required)
- Additional features: User data: load the [cloud-config.yml](cloud-config.yml) file in this repository
- SSH key: select your pre-defined SSH key
- Name: (depending on your need)


It takes about 3 minutes to do the Ubuntu update, install packages and start Docker.



If you found this useful and you would like to give something small back then please use [this Hetzner referral link](https://hetzner.cloud/?ref=lgUHbXXMojBF).
As soon as you sign, you'll receive € 20 in cloud credits.

Thank you!
