Role Name
=========

Плейбук запускаеться по крон и Добавляет удаляет пользователей и их ключей. Редактирует sudores, может отключать возможность залогиниться в ssh под root если переменная disable_root_login == true

Зависимости
------------
requirements.yml:
  - https://srv-glory.ru/ansible/roles/users

.gitlab-ci.yml:
  - https://srv-glory.ru/ansible/inventory.git
