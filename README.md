# hetzner-basic-docker-server

Create a cloud server with docker setup at [Hetzner.com](hetzner.com)


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
