# Practical 1 – Docker Commands

## 1. Check Docker Version
```bash
docker --version
```

## 2. Check Docker Engine Information
```bash
sudo docker info
```

## 3. Check Docker Images
```bash
sudo docker images
```

## 4. Run Ubuntu Container
```bash
sudo docker run -it --name sujata-ubuntu ubuntu:latest bash
```

## 5. Commands Executed Inside Container
```bash
whoami
cat /etc/os-release
pwd
ls -la
df -h
free -h
ps aux
hostname
exit
```

## 6. Check All Containers
```bash
sudo docker ps -a
```

## 7. Start Container
```bash
sudo docker start sujata-ubuntu
```

## 8. Check Running Containers
```bash
sudo docker ps
```

## 9. Stop Container
```bash
sudo docker stop sujata-ubuntu
```

## 10. Remove Container
```bash
sudo docker rm sujata-ubuntu
```

## 11. Verify Images
```bash
sudo docker images
```
