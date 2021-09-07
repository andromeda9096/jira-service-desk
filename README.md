# Jira-service-desk full on docker
### Install jira servicedesk on docker host
```
docker volume create --name jiraVolume

docker run -v jiraVolume:/var/atlassian/application-data/jira --name="jira" --restart unless-stopped -d -p 6080:8080 andromeda9096/jira-service-desk:0.0.1
```
### Open browser and config 
=>http://hostip:6080

