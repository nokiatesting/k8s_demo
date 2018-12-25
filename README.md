# k8s_demo
Demo of K8S using docker_demo repo

Run NFS server:
docker run -d --net=host --privileged --name nfs-server katacoda/contained-nfs-server:centos7 /exports/data-mysql

修改demo.yml里的NFS地址
