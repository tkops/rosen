# rosen
## Migration eines Rancher Clusters

1. Install Rancher Server on Bootstrap Node

    yum install -y yum-utils
    yum-config-manager --add-repo https://download.docker.com/linux/centos/docker-ce.repo
    yum install -y docker-ce
