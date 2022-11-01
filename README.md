Задание
1. Возьмите исходники простейшего [PHP-приложения](https://github.com/SkillfactoryCoding/devops_module10_compose).
2. Добавьте docker-compose.yml конфигурацию с двумя сервисами: php и nginx. Nginx должен использовать готовый докер-образ, сервис php должен собираться из текущей директории. Для этого в репозитории есть Dockerfile.
3. Добавьте healthcheck для php-сервиса, который ходил бы на http://nginx и проверял содержимое на наличие строки «works» (это можно сделать через curl и grep).
4. Запустить приложение через Docker Compose.
