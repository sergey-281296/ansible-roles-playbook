# Ansible Roles Playbook

## Результат выполнения

### 1. Успешный запуск
![](screenshots/01-playbook-run.png)

### 2. Проверка идемпотентности
![](screenshots/02-playbook-idempotence.png)

## Запуск

    ansible-galaxy install -r requirements.yml
    ansible-playbook -i inventory/prod.yml site.yml

## Репозитории с ролями

https://github.com/sergey-281296/vector-role

https://github.com/sergey-281296/lighthouse-role
