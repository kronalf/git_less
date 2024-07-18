## Шпаргалка по Git

HEAD -- это голова.  
Коммит -- это всему голова.  
Статусы файлов:
<тут пустая строка!>

```mermaid
%% описание схемы
```
<и тут пустая строка!> 

* --amend рассчитан на работу с последним коммитом (HEAD).
* Дополнить коммит новыми файлами можно с помощью ```git commit --amend --no-edit```. Благодаря опции ```--no-edit``` сообщение к коммиту останется таким, каким и было.
* Изменить сообщение к коммиту позволяет команда ```git commit --amend -m "Обновлённое сообщение коммита"```.