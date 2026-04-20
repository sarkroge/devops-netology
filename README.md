# devops-netology

Репозиторий для домашних заданий по курсу DevOps.

## Игнорируемые файлы

В каталоге `terraform` добавлен файл `.gitignore`, который будет исключать из репозитория:

- служебную директорию `.terraform/`;
- файлы состояния Terraform `*.tfstate` и `*.tfstate.*`;
- файлы переменных `*.tfvars` и `*.tfvars.json`, так как в них могут храниться чувствительные данные;
- файлы переопределения `override.tf`, `*_override.tf` и их JSON-варианты;
- файлы логов сбоев `crash.log` и `crash.*.log`;
- конфигурационные файлы Terraform CLI `.terraformrc` и `terraform.rc`;
- файлы плана `*.tfplan`.

Добавлено изменение в ветке fix