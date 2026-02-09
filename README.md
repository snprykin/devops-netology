# devops-netology
## Gitignore
### НЕ попадет в Git благодаря этому файлу:

.terraform/ - Папка

Все *.tfstate файлы

Логи и временные файлы:
crash.log
crash.*.log

Файлы с переменными:
*.tfvars
*.tfvars.json

Локальные переопределения:
override.tf
override.tf.json
*_override.tf
*_override.tf.json

.terraform.tfstate.lock.info — файл блокировки

Персональные настройки:
.terraformrc
terraform.rc

![Админ панель Zabbix](https://github.com/snprykin/homework/blob/main/%D0%9C%D0%BE%D0%BD%D0%B8%D1%82%D0%BE%D1%80%D0%B8%D0%BD%D0%B3/Zabbix/screenshots/1.jpg)`
