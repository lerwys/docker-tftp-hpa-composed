Docker image default configurations for TFTP server
================================

### Run Instructions

Stop host services from being run

    sudo systemctl stop tftpd-hpa.service

Disable TFTP services from being started on boot:

    sudo systemctl disable tftpd-hpa.service

Run image

    docker-compose up -d
