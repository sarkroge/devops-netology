# devops-netology

Репозиторий для домашних заданий по курсу DevOps.

## Игнорируемые файлы в Terraform

В каталоге `terraform` используется файл `.gitignore`, который содержит правила для исключения файлов из репозитория.

Описание правил:

- служебную директорию `.terraform/`;
- файлы состояния Terraform `*.tfstate` и `*.tfstate.*`;
- файлы переменных `*.tfvars` и `*.tfvars.json`, так как в них могут храниться чувствительные данные;
- файлы переопределения `override.tf`, `*_override.tf` и их JSON-варианты;
- файлы логов сбоев `crash.log` и `crash.*.log`;
- конфигурационные файлы Terraform CLI `.terraformrc` и `terraform.rc`;
- файлы плана `*.tfplan`.