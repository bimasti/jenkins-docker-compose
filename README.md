
# Subindo Jenkins com docker-compose

## Deploy

```bash
  git clone https://github.com/bimasti/jenkins-docker-compose.git 
```

## Atencao !!! 
### No arquivo docker-compose.yaml alterar PATH do volume para sua preferencia

```bash
volumes:
      - '/{PATH}/jenkins:/var/jenkins_home'
      - '/var/run/docker.sock:/var/run/docker.sock'
```

```bash
  cd jenkins-docker-compose && docker-compose up -d
```
## Abrir navegador

- http://localhost:8080
