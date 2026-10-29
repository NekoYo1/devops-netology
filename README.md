# devops-netology

## Игнорируемые файлы в terraform/.gitignore

Файл `terraform/.gitignore` описывает следующие правила исключения:

- Игнорируются все каталоги и файлы, имя которых начинается с `.terraform` (шаблон `.terraform/`, `.terraformrc`, `.terraform.tfstate.lock.info`).
- Игнорируются все файлы с расширением `.tfstate` (шаблон `*.tfstate`), а также файлы, в имени которых есть сочетание `.tfstate.` (шаблон `*.tfstate.*`).
- Игнорируются файлы журналов сбоев: `crash.log` и файлы, соответствующие шаблону `crash.*.log`.
- Игнорируются все файлы с расширением `.tfvars` (шаблон `*.tfvars`) и `.tfvars.json` (шаблон `*.tfvars.json`).
- Игнорируются файлы, имя которых заканчивается на `override.tf` или `override.tf.json` (шаблоны `override.tf`, `override.tf.json`), а также файлы, в имени которых есть `_override.tf` или `_override.tf.json` (шаблоны `*_override.tf`, `*_override.tf.json`).
- Игнорируется файл `terraform.rc`.
1
