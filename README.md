## Jenkins Nexus Starter

This is a starter project for Jenkins with Nexus integration.

### Usage

- `docker compose up -d`

- Open Jenkins UI in browser: http://localhost:8080
- Open Nexus UI in browser: http://localhost:8081
- Demo Jenkinsfile: https://github.com/ntheanh201/trafficcontrol/blob/jenkins/Jenkinsfile

### Jenkins post-installation setup wizard

Get initial admin password:
```shell
docker exec -it jenkins-blueocean cat /var/jenkins_home/secrets/initialAdminPassword
```

### Nexus post-installation setup

Get initial admin password:
```shell
docker exec -it nexus cat /nexus-data/admin.password
```
