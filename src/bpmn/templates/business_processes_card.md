# Бизнес-процесс "{{title}}"
- **ID**: {{doc_id}}
- **Описание:** {{description}}

# Характеристики
- **Статус:** {{state}}
- **Дата актуализации:** {{state_update_date}}
- **Ответственный за ведение:** {{division_owner}}

## Схема бизнес-процесса
![Схема процесса](@document/{{doc_id}})

## Входящие бизнес-процессы
![Входящие процессы](@document/business_processes.doc.sub_process?doc_id={{doc_id}}&incoming=true)

## Исходящие бизнес-процессы
![Исходящие процессы](@document/business_processes.doc.sub_process?doc_id={{doc_id}}&incoming=false)
