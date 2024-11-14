## Jenkins Nexus Starter

This is a starter project for Jenkins with Nexus integration.

### Jenkins post-installation setup wizard

Get initial admin password:
```shell
docker exec -it jenkins-blueocean cat /var/jenkins_home/secrets/initialAdminPassword
```