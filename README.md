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
