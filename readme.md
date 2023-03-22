
# How to deploy config changes to Docker running on Grafana machine

1. make changes in this folder
2. commit and push the changes
3. connect to grafana machine
4. `cd git/grafana`
5. `git pull`
6. Update GF_SMTP_PASSWORD value with SMTPkey for SendInBlue
6. `docker compose up -d`