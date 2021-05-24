# Generate SSL Certificate Using Docker-Compose

1. Clone this repository
2. Edit docker-compose.yml file
3. Change `<email>` to your email address
4. Change `<domain>` to your domain name; If there is more than one domain, then add more `-d <domain>`
5. Safe the edit
6. Run `docker-compose up`
7. After it says `*Congratulations* or *Error* then <kbd>CTRL+C</kbd>
8. Your certificate will be inside `certbot/conf/live` folder
