# docker_wordpress
WordPress コンテナを立ち上げる Docker Compose です

```bash
git clone https://github.com/oki2a24/docker_wordpress.git
cd docker_wordpress
cp env-example .env
# .env を編集し、以下を実行
docker-compose up -d
docker-compose exec -T wordpress chown -R www-data:www-data /var/www/html/
```
