# Ansible Roles Playbook

## Результат выполнения

### Первый запуск
![Первый запуск](screenshots/01-playbook-run.png)

### Проверка идемпотентности
![Идемпотентность](screenshots/02-playbook-idempotence.png)

## Запуск
```bash
ansible-galaxy install -r requirements.yml
ansible-playbook -i inventory/prod.yml site.yml
Репозитории с ролями
vector-role

lighthouse-role
